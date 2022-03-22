
# Hosting a resume in Github Pages

## Purpose 

Practical steps for hosting and formatting a resume on a static site with Markdown, Github Pages, and Jekyll while adhering to the specific basic principles of modern technical writing as stated in Andrew Etter's book *Modern Technical Writing*.

## Prerequisites

- A markdown-formatted resume or portfolio.
- A Github account. Click [here](https://docs.github.com/en/get-started/signing-up-for-github/signing-up-for-a-new-github-account#about-new-accounts-on-githubcom) on how to open an account. 

## Instructions

### 1. Create a resume by using a Lightweight Markup Language

- XML files are required to develop websites, according to Andrew Etter in *Modern Technical Writing*. They are, however, a language with their own rules that, like a programming language, necessitates learning the syntax (i.e. Javascript). This limits the contributions of current technical writers, who may not be familiar with programming languages. According to Etter, putting the content in a lightweight markup language makes generating a well-formatted XML easier. The lightweight markup languages are human-readable and have a simple syntax, which also helps boost contributions from people with little to none background of programming.
- Several Lightweight Markup languages are available such as Markdown, reStructuredText and AsciiDoc as described in *Modern Technical Writing* by Andrew Etter. For the purposes of this specific instructions, we will be using Markdown to demonstrate the objective of hosting a resume. Markdown is described to be the most widely used lightweight markup language as it has a straightforward syntax in *Modern Technical Writing* by Etter. 
- Andrew also states that there are several specialized text editor for specific operating system for Markdown syntax and they are provided below: 
    - [MarkdownPad](http://markdownpad.com/) (For Windows)
    - [iA Writer](https://ia.net/writer) (For macOS)
    - [ReText](https://www.linuxhelp.com/how-to-install-retext-7-0-1-on-ubuntu-18-04) (For Linux)
- Due to limited set of features in a Markdown, different 'flavors' were added in extension. Since, the resume will be hosted in Github, please use the instructions [here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for basic formatting syntax in Github. To learn more about Github Flavors Markdown specifications, click [here](https://github.github.com/gfm/) 


### 2. Creating a repository in Github and add files to repository

Since now you already have an account in Github, the next step is to create a repository where your Markdown-formatted files will be stored. The steps are provided below:

- Login to your Github account. 
- Click on "Repositories"
- Click on "New"
- Type "UserName.github.io" on the textbox under "Repository Name"
    - The name of the repository must be your github account user name followed by .github.io
- Click on "Create Repository". 


The next step is to push(adding) the resume to the repository. There are alternatives way to do this which includes pushing files through command line from the local machine or doing it directly through the browser. The steps below will demonstarate on how to add files directly through the browser. For those who would like to do it through the command line, follow these steps as provided in [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) and [here](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository#adding-a-file-to-a-repository-using-the-command-line), respectively.


The steps to add files directly through browser: 

- Change the name of your "resume.md" to "index.md"
- Go to the repository made under the name "UserName.github.io" 
- Click on "Add file"
- Click "Upload files"
- Upload your "index.md" file to the repository by clicking "Commit changes"


The resume has now been uploaded to the website. Take a look at it by visiting "UserName.github.io" through the browser.


> Github is a distributed version control system. A distributed version control system, as mentioned by Etter in *Modern Technical Writing*, provides greater speed, permits offline work, and is preferable for parallel work on the same file. Because the repository has already been set up, this is now accessible on github, where different individuals may work on the same file, such as the readme.md, and push their modifications. If a modification is made, the repository's owner will be able to first determine whether the change is essential. The modification will be verified by the person with the power to approve it (it can be several person, given they have approval for that repository), and the code will be changed. As a result, as Etter said, it is unquestionably better. Instead of waiting for a single person to make a modification, all participants may work on a file simultaneously without worrying about what the other may modify.


### 3. Hosting the resume on static website

> Notice that the resume on the website appears fairly basic, just like it does on github. As a result, we will utilise the static site Jekyll to apply a theme that will give the website a fashionable appearance. This is accomplished by using a theme on Github Pages, as proposed by Andrew Etter in his book *Modern Technical Writing*. 

Below are the steps that are required to host a resume with a static site theme:
- Go to your repository that you made above. 
- Click on "Settings"
- Scroll below to locate "Github Pages" and click on link provided. 
- Locate "theme chooser" and click on "Change theme" after getting directed to the Github Pages.
- Change the theme to which you prefer. 
    - In your repository, a "_config.yml" file will appear. It indicates that you theme has been applied to your site.
- Visit your static website through "UserName.github.io" and the resume will be displayed with the selected theme. 



Visit the website now and it should look like this:
![gif](resume.gif)

> As also suggested by Etter, static site generators usually do not have any dependencies and have a simple migration. We can see that, generating a theme using Github Pages directly applies the changes to our website. Hence, a simpler migration. 


## More Resources


1. [Markdown Tutorial](https://www.markdowntutorial.com/)
2. [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) 
3. [Jekyll Tutorial](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)


## Authors and Acknowledgements

Written by Chowdhury Abdul Mumin Ishmam following the guidlines and principles of *Modern Technical Writing* by Andrew Etter. 


## FAQs


1. Why is my resume not showing up?
> Check to determine whether your basic syntax and formatting corresponds to Github Markdown guidelines. If they do, be sure to name the repository "Your Github UserName.gihub.io." For your site to be produced, this name standard must be followed.


2. Why is Markdown better than word processor?
> A word processor has a wide range of buttons and functionalities that are required to style the content as you write it. Markdown, on the other hand, provides a much easier syntax that allows you to layout your site after it has been written using CSS and HTML.
