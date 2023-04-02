<a id="readme-top"></a>

[Back to Resources](/README.md)

# Contribution Guidelines

Firstly, thank you for your interest in contributing! At first it may seem an overwhelming volume of new terms and commands, but don't be put off by this.

Below is a full guide, with step-by-step instructions to help you make contributions. The skills you will learn from this can be applied to the majority of open source projects.

Remember, contributing to open source is a learning experience. Don't be afraid to ask questions, seek help, or make mistakes. We're all here to help each other learn and grow as contributors. Happy contributing!

## Checklist

After going through this guide once, this checklist can be used to practice the process.

1. Fork this repository to your own GitHub account.
2. Clone the forked repository to your local machine.
3. Create a new branch for your resources.
4. Make your changes, and test them thoroughly.
5. Commit your changes with a descriptive commit message.
6. Push your changes to your forked repository.
7. Open a pull request in this repository and provide a detailed description of your changes.

## Getting Started

Git and GitHub will both be required to continue with the following steps. There are a [collection of resources](README.md/#git--github) in the README that can help you understand these tools.

`Git` is a version control system that allows multiple people to work on the same codebase, keeping track of changes and enabling collaboration.

> Please make sure you have installed [Git](https://git-scm.com/book/en/v2) on your machine before continuing. Some computers will have it built in, but if you can't find it, you can download for [Mac](https://git-scm.com/download/mac) or [Windows](https://gitforwindows.org/).

`GitHub` is a web-based platform that provides hosting for Git repositories, making it easier for individuals and teams to collaborate on and manage their code projects.

> If you don't already have a GitHub account, sign up for one now so that you can become a contributor. It is free to do and can be found in the navigation bar.

## Step 1: Fork the `web-dev-resources` repository

`Fork` this repository to your own GitHub account: Click on the "Fork" button at the top-right corner of the repository.This will create a copy of this repository in your account. If you wish to know more, GitHub has further details on [forking a repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

## Step 2: Clone the repository

Now `clone` the forked repository to your machine.Go to your GitHub account, open the forked repository, click on the 'code' button and then click the copy to clipboard icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (**your** fork of this project). See the previous steps to obtain the url.

You have now [cloned the repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) to your machine, well done!

It should look something like this:

```
git clone https://github.com/YOUR-GITHUB-USERNAME/web-dev-resources.git
```

## Step 3: Create a branch for your feature/resource

`Create a new branch` for your feature or bug fix: Navigate into the cloned repository and create a new branch using the following command:

```
git checkout -b BRANCH-NAME
```

Be sure to replace "BRANCH-NAME" with a descriptive name for your branch, such as "add-new-feature" or "fix-bug-123".

## Step 4: Make your changes

Please follow the following format for adding a resource:

```
|[Name of Resource](link to resource) | Description |
```

If you are making a change to a table, to make sure that it is formatted correctly, you can use the commands `CMD + SHIFT + V` (Mac) or `CTRL + SHIFT + V` (Windows) and a preview should pop up for you to see how the code will be displayed. You can also right click on the markdown file in the sidebar and click on `Open Preview` to see how it will look.

## Step 5: Commit your changes with a descriptive commit message

Once you're satisfied with your changes, `stage` them for commit using the following command:

```
git add .
```

Staging a commit means selecting specific changes in your code that you want to include in the next commit.

Then `commit` your changes with a descriptive commit message using the following command:

```
git commit -m "DESCRIBE YOUR CHANGES HERE"
```

Be sure to replace "DESCRIBE YOUR CHANGES HERE" with a brief summary of the changes you made.

## Step 6: Push changes to your forked repository

Once you've committed your changes, push them to your forked repository using the following command:

```
git push origin BRANCH-NAME
```

Be sure to replace "BRANCH-NAME" with the name of the branch you created in step 3.

## Step 7: Open a pull request and describe the changes

Navigate to your forked repository on GitHub and click the "New pull request" button. Select the branch you just pushed from the "base" branch dropdown, and select the original repository and branch you forked from in the "compare" branch dropdown. Then provide a detailed description of your changes and click the "Create pull request" button.

Well done! Once the change has been reviewed, it will be merged into the main branch!

## Glossary

There are quite a few terms mentioned in this guide. Below you will find a table that contains the main git commands and why they are used.

| Git Command                              | Description                                                                                                                                                                                |
| ---------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `git clone [url]`                        | Creates a local copy of the remote repository on your machine. This is the first step when getting started with contributing to an existing repository.                                    |
| `git checkout -b [branch-name]`          | Creates a new branch and switches to it. This is important to keep your changes separate from the main branch and to make it easier to manage multiple contributions.                      |
| `git add .`                              | Adds all the changes made in the files to the staging area. This is important to prepare the changes for the next commit.                                                                  |
| `git commit -m "[commit message]"`       | Saves the changes made to the repository along with a brief description of the changes. This is important to keep track of what changes were made and why they were made.                  |
| `git push origin [branch-name]`          | Sends the committed changes to the remote repository in the branch you created. This is important to share your changes with the community and to make them available for review.          |
| `git pull --rebase upstream main`        | Retrieves the latest changes from the upstream repository and applies them to your local repository. This is important to ensure that your changes are made on top of the latest codebase. |
| `git push origin [branch-name] -f`       | Updates your pull request with new changes after addressing feedback. This is important to ensure that the updated changes are available for review.                                       |
| `git rebase -i HEAD~[number of commits]` | Squashes multiple commits into a single commit before pushing to the upstream repository. This is important to keep the commit history clean and organized.                                |

## Extra Resources

Git and GitHub are huge topics, but they are essential in the coding industry. There are some [recommended resources](README.md/#git--github) in the main README, however there are other useful videos to get up to speed with these tools:

- [FreeCodeCamp Git & GitHub](https://www.youtube.com/watch?v=RGOj5yH7evk)
- [Zero to Mastery Git Guide](https://www.youtube.com/watch?v=JN63v_czZqI)
- [Kevin Stratvert Git & GitHub Guide](https://www.youtube.com/watch?v=tRZGeaHPoaw)
