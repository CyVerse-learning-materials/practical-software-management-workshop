---
title: "GitHub"
teaching: 105
exercises: 0
questions:
- "What is GitHub?"
- "Why should I know about version control?"
- "Why is GitHub used by so many people?"
- "How can I use GitHub to collaborate?"
- "How do I format my text to make my documents clearer?"
objectives:
- "Create a GitHub account"
- "Create a GitHub repository"
- "Learn the basic structure of Markdown files"
- "Create a ReadMe and a Licence file in the new repository"
keypoints:
- "Version control is a powerful management and collaboration tool"
- "GitHub uses version control to keep track of changes to files"
- "GitHub is used as a repository for code and documentation"
- "All repositories should have clear documentation about how to use what is in it, and what rights people have"
---

### GitHub is an online version control tool
GitHub is an online service, owned by the Microsoft Corporation, that provides useful features for software developers and documentation creators to keep track of their files.

GitHub lets users create repositories which act like a folder on your computer that is used to keep files in a hierarchical file-and-folder system.

The underlying software that makes GitHub work is Git.

Git is a Decentralised Concurrent Versioning System, or DCVS. Simply put, the git computer program lets users keep track of the changes in their files. This process of tracking changes is called version control.

We will not be learning about the git command line software in this lesson - this is covered by the Software Carpentry lessons.

Instead we will be exploring the use of GitHub, without knowing any git commands, to set up repositories so that you can start to share code and documentation with others. 

### Creating a GitHub account
To start using GitHub, you will need to create a new user account.

If you already have a GitHub account, then please log in to GitHub by visiting the login page.

> ## Signing up to GitHub
> Open your web browser and go to <https://github.com>:
> - Click "Sign Up To GitHub"
> - Fill in the required information, i.e. a memorable username, a valid email address, and a strong password
> - If you do not pick a strong password, GitHub will ask you to supply a stronger one
> - GitHub may also ask you to solve a puzzle or CATCHPA to verify that you are a real human
> - Once verified, click "Next: Select A Plan"
> - Choose the free plan ($0 USD) by clicking "Choose Free" 
{: .callout}

You will also be asked to answer a few questions about your software development proficiency and what you will use GitHub for.

The free GitHub account includes the following features (correct at 2019):
- Unlimited public repositories
- Unlimited private repositories
- Limited to 3 collaborators for private repositories
- Issues and bug tracking
- Project management

### Create a new repository

All being well, once logged in you should see your GitHub activity dashboard. As you use GitHub more, you will see more information here about your repositories, repositories you are watching or contribute to, etc. For now we want to create a new repository

In the top left of the GitHub page, you should see your login name and a green button underneath to create a new repository:

![New Repository button](github_new_repo.png)

Click this button and you should be presented with the next screen where you tell GitHub information about your new repo:

![New Repository details](github_new_repo_details.png)

We need to pick a name for our repo, and GitHub even makes some amusing suggestions.

> ## Repository Naming Conventions
> You should call your repository something descriptive:
> - "my_repo" doesn't tell anyone what is in your repository
> - Conversely, "very_specific_repository_name_that_holds_all_my_things" is too long and too broad
> - Pick something concise yet specific: "practical_software_management" sounds good

Next, we need to give a description of your repository. This should be more detailed, usually with some project-specific information that will help someone decide at first glance if this repository contains the things they want.

You should select your repository to be public. With the free GitHub plan you can have private repositories, and you can share these private repos with three collaborators maximum. This is useful for small labs who wish to keep their code private whilst they are developing key features, but this isn't really suitable for larger labs. If you need more collaborators on private repositories, you will have to pay for one of GitHub's paid plans.

Select the checkbox that says "Initialise this repository with a README".

Leave .gitignore set to "None" (you can learn more about this in the Software Carpentry git lessons).

Finally, we need to add a licence to our repository. This is very important, as code or data with no licence is treated differently in different countries. Some countries take this as copyright attributed to the author. Some count this as public domain.

It is best practice to assign your project a licence from the start. For this example, we will choose the MIT licence, which is very permissive, meaning people can pretty much do what they want to your code as long as they credit you.

We will cover picking a licence in this lesson (LINK).

Note that this doesn't mean that someone can come along and start editing code in your repository! They will need to be given access to your repo to make changes or "Pull Requests" - we will cover this later.

![New empty repository](github_new_empty_repo.png)


{% include links.md %}
