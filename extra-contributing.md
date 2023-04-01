# Contributing Guidelines

We have no affiliation or association with any of the following resources. This is simply

## Getting Started

1. Fork this repository to your own GitHub account.
2. Clone the forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. Make your changes, and test them thoroughly.
5. Commit your changes with a descriptive commit message.
6. Push your changes to your forked repository.
7. Open a pull request in this repository and provide a detailed description of your changes.

## Getting Started

1. `Fork` this repository to your own GitHub account: Click on the "Fork" button at the top-right corner of the repository.

2. `Clone` the forked repository to your local machine: Open a terminal and navigate to the directory where you want to clone the repository. Then run the following command:

```
git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
```

Be sure to replace "YOUR-USERNAME" and "REPOSITORY-NAME" with your own GitHub username and the name of the repository you forked.

3. Create a new branch for your feature or bug fix: Navigate into the cloned repository and create a new branch using the following command:

```
git checkout -b BRANCH-NAME
```

Be sure to replace "BRANCH-NAME" with a descriptive name for your branch, such as "add-new-feature" or "fix-bug-123".

4. Make your changes, and test them thoroughly: Make the necessary changes to the codebase to implement your feature or fix the bug you're working on. Be sure to test your changes thoroughly to ensure they work as expected. If you are making a change to a table, to make sure that it is formatted correctly, you can use the commands `CMD + SHIFT + V` (Mac) or `CTRL + SHIFT + V` (Windows) and a preview should pop up for you to see how the code will be displayed. You can also right click on the markdown file in the sidebar and click on `Open Preview` to see how it will look.

5. Commit your changes with a descriptive commit message: Once you're satisfied with your changes, stage them for commit using the following command:

```
git add .
```

Then commit your changes with a descriptive commit message using the following command:

```
git commit -m "DESCRIBE YOUR CHANGES HERE"
```

Be sure to replace "DESCRIBE YOUR CHANGES HERE" with a brief summary of the changes you made.

6. Push your changes to your forked repository: Once you've committed your changes, push them to your forked repository using the following command:

```
git push origin BRANCH-NAME
```

Be sure to replace "BRANCH-NAME" with the name of the branch you created in step 3.

7. Open a pull request in this repository and provide a detailed description of your changes: Navigate to your forked repository on GitHub and click the "New pull request" button. Select the branch you just pushed from the "base" branch dropdown, and select the original repository and branch you forked from in the "compare" branch dropdown. Then provide a detailed description of your changes and click the "Create pull request" button.

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

## Guidelines

### Code Style

- Follow the code style guidelines used in this project.
- Use consistent indentation and whitespace.
- Use meaningful variable and function names.
- Write concise and readable code.

### Testing

- Write tests to cover your changes.
- Ensure that existing tests pass.
- Write documentation for your tests.

### Documentation

- Document your changes in the README or other relevant documentation files.
- Write concise and informative commit messages.
- Include helpful comments in your code.

### Pull Requests

- Open a pull request with a clear description of your changes.
- Provide context for your changes and explain why they are necessary.
- Be responsive to feedback and be willing to make changes based on feedback.
- Ensure that all tests pass and that your code adheres to the project's code style guidelines.
- Follow the pull request template provided in this repository.

## Code of Conduct

This project has a code of conduct that all contributors are expected to follow. Please review the code of conduct (link to CODE_OF_CONDUCT.md) before contributing.

## License

By contributing to this project, you agree to license your contributions under the MIT License (link to LICENSE.md).

```

```

```

```

```

```
