<<<<<<< HEAD
# :wave: The Basics of Git and GitHub 

## 🤓 Course overview and learning outcomes 

The goal of this course is to give you a brief introduction to GitHub. We’ll also provide you with materials for further learning and a few ideas to get you started on our platform.

## :octocat: Git and GitHub

**Git is a distributed Version Control System (VCS) that helps track changes as you work on new software development projects.** Git tracks the changes you make so you always have a record of what you’ve worked on and you can easily revert back to an older version of your code if need be. It also makes working with others easier—groups of people can work together on the same project and merge their changes into one final source! 

**GitHub is a collaboration platform.** From software to legal documents, you can count on GitHub to help you do your best work with the collaboration and security tools your team needs. With GitHub, you can keep projects completely private, invite the world to collaborate, and streamline every step of your project.

**GitHub is also a powerful version control tool.** GitHub uses Git, the most popular open source version control software, to track every contribution and contributor to your project—so you know exactly where every line of code came from. 

**GitHub helps people do much more.** GitHub is used to build some of the most advanced technologies in the world. Whether you're visualizing data or building a new game, there's a whole community and set of tools on GitHub that can get you to the next step. This course starts with the basics, but we'll dig into the rest later.

## 💻 GitHub features 

### Repositories 

A repository is where your project work happens. It contains all of your project’s files and revision history. You can work within a repository alone or invite others to collaborate with you on those files. As you work more on GitHub you will have many repositories. Use your GitHub dashboard to easily navigate to them. You must be logged in though! 

Repositories also contain README’s. You can add a README file to your repository to tell other people why your project is useful, what they can do with your project, and how they can use it. We are using this README to communicate how to learn Git and GitHub with you. :smile: 

Read more about repositories [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) and repository README’s [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Pull requests

Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add more changes if need be. 

Adding someone as a reviewer on your pull request is a signal to them that you want help or would like them to review the content. 

Read more about pull requests [here](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 

### Issues

Use issues to track enhancements, tasks, or bugs for your work on GitHub. Issues are a great way to keep track of all the tasks you want to work on for your project and let others know what you plan to work on. For larger projects, you can keep track of many issues on a project board. GitHub Projects help you organize and prioritize your work and you can read more about them [here](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). 

Pull requests and issues can also be linked together! You can link a pull request to an issue to show that a fix is in progress and to automatically close the issue when someone merges the pull request. 

Read more about issues and linking them to your pull requests [here](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 
=======
# :wave: The Basics of GitHub 

## 🤓 Course overview and learning outcomes 

The goal of this course is to give you a brief introduction to GitHub. We’ll also provide you with materials for further learning and a few ideas to get you started on our platform. 🚀

## :octocat: Git and GitHub

Git is a **distributed Version Control System (VCS)**, which means it is a useful tool for easily tracking changes to your code, collaborating, and sharing. With Git you can track the changes you make to your project so you always have a record of what you’ve worked on and can easily revert back to an older version if need be. It also makes working with others easier—groups of people can work together on the same project and merge their changes into one final source!

GitHub is a way to use the same power of Git all online with an easy-to-use interface. It’s used across the software world and beyond to collaborate and maintain the history of projects.

GitHub is home to some of the most advanced technologies in the world. Whether you're visualizing data or building a new game, there's a whole community and set of tools on GitHub that can get you to the next step. This course starts with the basics of GitHub, but we'll dig into the rest later.

## :octocat: Understanding the GitHub flow 

The GitHub flow is a lightweight workflow that allows you to experiment and collaborate on your projects easily, without the risk of losing your previous work.

### Repositories

A repository is where your project work happens--think of it as your project folder. It contains all of your project’s files and revision history.  You can work within a repository alone or invite others to collaborate with you on those files.

### Cloning 

When a repository is created with GitHub, it’s stored remotely in the ☁️. You can clone a repository to create a local copy on your computer and then use Git to sync the two. This makes it easier to fix issues, add or remove files, and push larger commits. You can also use the editing tool of your choice as opposed to the GitHub UI. Cloning a repository also pulls down all the repository data that GitHub has at that point in time, including all versions of every file and folder for the project! This can be helpful if you experiment with your project and then realize you liked a previous version more. 
To learn more about cloning, read ["Cloning a Repository"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

### Committing and pushing
**Committing** and **pushing** are how you can add the changes you made on your local machine to the remote repository in GitHub. That way your instructor and/or teammates can see your latest work when you’re ready to share it. You can make a commit when you have made changes to your project that you want to “checkpoint.” You can also add a helpful **commit message** to remind yourself or your teammates what work you did (e.g. “Added a README with information about our project”).

Once you have a commit or multiple commits that you’re ready to add to your repository, you can use the push command to add those changes to your remote repository. Committing and pushing may feel new at first, but we promise you’ll get used to it 🙂

## 💻 GitHub terms to know 

### Repositories 
We mentioned repositories already, they are where your project work happens, but let’s talk a bit more about the details of them! As you work more on GitHub you will have many repositories which may feel confusing at first. Fortunately, your ["GitHub dashboard"](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/about-your-personal-dashboard) helps to easily navigate to your repositories and see useful information about them. Make sure you’re logged in to see it!

Repositories also contain **README**s. You can add a README file to your repository to tell other people why your project is useful, what they can do with your project, and how they can use it. We are using this README to communicate how to learn Git and GitHub with you. 😄 
To learn more about repositories read ["Creating, Cloning, and Archiving Repositories](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-repositories) and ["About README's"](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes). 

### Branches
You can use branches on GitHub to isolate work that you do not want merged into your final project just yet. Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository. Typically, you might create a new branch from the default branch of your repository—main. This makes a new working copy of your repository for you to experiment with. Once your new changes have been reviewed by a teammate, or you are satisfied with them, you can merge your changes into the default branch of your repository.
To learn more about branching, read ["About Branches"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

### Forks
A fork is another way to copy a repository, but is usually used when you want to contribute to someone else’s project. Forking a repository allows you to freely experiment with changes without affecting the original project and is very popular when contributing to open source software projects!
To learn more about forking, read ["Fork a repo"](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo)

### Pull requests
When working with branches, you can use a pull request to tell others about the changes you want to make and ask for their feedback. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add more changes if need be. You can add specific people as reviewers of your pull request which shows you want their feedback on your changes! Once a pull request is ready-to-go, it can be merged into your main branch.
To learn more about pull requests, read ["About Pull Requests"](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests). 


### Issues
Issues are a way to track enhancements, tasks, or bugs for your work on GitHub. Issues are a great way to keep track of all the tasks you want to work on for your project and let others know what you plan to work on. You can also use issues to tell a favorite open source project about a bug you found or a feature you think would be great to add!

For larger projects, you can keep track of many issues on a project board. GitHub Projects help you organize and prioritize your work and you can read more about them [in this "About Project boards document](https://docs.github.com/en/github/managing-your-work-on-github/about-project-boards). You likely won’t need a project board for your assignments, but once you move on to even bigger projects, they’re a great way to organize your team’s work!
You can also link together pull requests and issues to show that a fix is in progress and to automatically close the issue when someone merges the pull request.
To learn more about issues and linking them to your pull requests, read ["About Issues"](https://docs.github.com/en/github/managing-your-work-on-github/about-issues). 
>>>>>>> dcb2252524df8462aff3e715812f2b9a11cba2cf

### Your user profile

Your profile page tells people the story of your work through the repositories you're interested in, the contributions you've made, and the conversations you've had. You can also give the world a unique view into who you are with your profile README. You can use your profile to let future employers know all about you! 
<<<<<<< HEAD

Read more about your user profile and adding and updating your profile README [here](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Using markdown on GitHub 

You might have noticed already, but you can minimally style your issues, pull requests, and files (as long as they are .md format!). Using Markdown in your issues, pull requests, and files helps organize your information and make it easier for others to read. You can also drop in gifs and images to convey your point!

Read more about using GitHub’s flavor of markdown [here](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 
=======
To learn more about your user profile and adding and updating your profile README, read ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme). 

### Using markdown on GitHub 

You might have noticed already, but you can add some fun styling to your issues, pull requests, and files. ["Markdown"](https://guides.github.com/features/mastering-markdown/) is an easy way to style your issues, pull requests, and files with some simple syntax. This can be helpful to organize your information and make it easier for others to read. You can also drop in gifs and images to help convey your point!
To learn more about using GitHub’s flavor of markdown, read ["Basic Writing and Formatting Syntax"](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax). 
>>>>>>> dcb2252524df8462aff3e715812f2b9a11cba2cf

### Engaging with the GitHub community

The GitHub community is vast. There are many types of people who use GitHub in their day to day—students like you, professional developers, hobbyists working on open source projects, and explorers who are just jumping into the world of software development on their own. There are many ways you can interact with the larger GitHub community, but here are three places where you can start. 

#### Starring repositories 

If you find a repository interesting or you want to keep track of it, star it! When you star a repository it’s also used as a signal to surface better recommendations on github.com/explore. If you’d like to get back to your starred repositories you can do so via your user profile. 
<<<<<<< HEAD

Read more about starring repositories [here](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 
=======
To learn  more about starring repositories, read ["Saving Repositories with Stars"](https://docs.github.com/en/github/getting-started-with-github/saving-repositories-with-stars). 
>>>>>>> dcb2252524df8462aff3e715812f2b9a11cba2cf

#### Following users 

You can follow people on GitHub to receive notifications about their activity and discover projects in their communities. When you follow a user, their public GitHub activity will show up on your dashboard so you can see all the cool things they are working on. 
<<<<<<< HEAD

Read more about following users [here](https://docs.github.com/en/github/getting-started-with-github/following-people).
=======
To learn more about following users, read ["Following People"](https://docs.github.com/en/github/getting-started-with-github/following-people).
>>>>>>> dcb2252524df8462aff3e715812f2b9a11cba2cf

#### Browsing GitHub Explore 

GitHub Explore is a great place to do just that … explore :smile: You can find new projects, events, and developers to interact with.

<<<<<<< HEAD
Check out GitHub Explore [here](https://github.com/explore). The more you intereact with GitHub the more tailored your Explore view will be. 

## :octocat: Understanding the GitHub flow 

The GitHub flow is a lightweight workflow that allows you to experiment with new ideas safely, without fear of compromising a project.

### Branching 

You can use branches on GitHub to isolate work that you do not want merged into your final project. Branches allow you to develop features, fix bugs, or safely experiment with new ideas in a contained area of your repository. You always create a branch from an existing branch. Typically, you might create a new branch from the default branch of your repository—`main`. 

Once your new changes have been reviewed by a teammate, or you are satisfied with them, you can merge your changes into the default branch of your repository.

Read more about branching [here](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches). 

### Cloning and forking 

When you create a repository it exists remotely outside of your local machine. You can clone a repository to create a local copy on your computer and then use Git to sync the two. 

You can clone a repository from GitHub to your local computer to make it easier to fix issues, add or remove files, and push larger commits. You can also use an IDE or editing tool of your choice as opposed to the GitHub UI. When you clone a repository, you copy the repository from GitHub to your local machine.
Cloning a repository pulls down a full copy of all the repository data that GitHub has at that point in time, including all versions of every file and folder for the project.
Read more about cloning here. 

A fork is another way to copy a repository, but is most commonly used when contributing to someone else’s project. Forking a repository allows you to freely experiment with changes without affecting the original project and is very popular when contributing to open source software projects.

Read more about forking [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).
=======
You can check out the GitHub Explore website [at github.com/explore](https://github.com/explore). The more you intereact with GitHub the more tailored your Explore view will be. 
>>>>>>> dcb2252524df8462aff3e715812f2b9a11cba2cf

## 📝 Optional next steps 

* Open a pull request and let your teacher know that you’ve finished this course.  
* Create a new markdown file in this repository. Let them know what you learned and what you are still confused about! Experiment with different styles!
<<<<<<< HEAD
* Create your profile README. Let the world know a little bit more about you! What are you interested in learning? What are you working on? What's your favorite hobby? [Here](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme) are steps on how to do that. 
* Go to your user dashboard and create a new repository. Experiment with the features within that repository to familiarize yourself with them. 
* Let us know what you liked or didn’t like about the content of this course. What would you like to see more of? What would be interesting or helpful to your learning journey? Take our survey. 
=======
* Create your profile README. Let the world know a little bit more about you! What are you interested in learning? What are you working on? What's your favorite hobby? Learn more about creating your profile README in the document, ["Managing Your Profile README"](https://docs.github.com/en/github/setting-up-and-managing-your-github-profile/managing-your-profile-readme).
* Go to your user dashboard and create a new repository. Experiment with the features within that repository to familiarize yourself with them. 
* [Let us know what you liked or didn’t like about the content of this course](https://support.github.com/contact/education). What would you like to see more of? What would be interesting or helpful to your learning journey? 
>>>>>>> dcb2252524df8462aff3e715812f2b9a11cba2cf

## 📚  Resources 
* [A short video explaining what GitHub is](https://www.youtube.com/watch?v=w3jLJU7DT5E&feature=youtu.be) 
* [Git and GitHub learning resources](https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources) 
* [Understanding the GitHub flow](https://guides.github.com/introduction/flow/)
* [How to use GitHub branches](https://www.youtube.com/watch?v=H5GJfcp3p4Q&feature=youtu.be)
* [Interactive Git training materials](https://githubtraining.github.io/training-manual/#/01_getting_ready_for_class)
* [GitHub's Learning Lab](https://lab.github.com/)
* [Education community forum](https://education.github.community/)
* [GitHub community forum](https://github.community/)
