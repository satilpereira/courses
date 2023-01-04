# Git and GitHub begginners course

## I. Introduction

Hi everyone, I'm Satil and this is Luiz. We're both full-stack developers and we've been working with Git and GitHub for a while now. We're passionate about helping others learn these tools and we're excited to share our knowledge with you in this course. Whether you're a beginner or an experienced user, we're confident that you'll learn something new and valuable in this course.

## II. Setting up Git

In this lesson, we'll start by setting up Git on our computers.
First, we'll need to download the Git software from the official website. There are versions available for Windows, Mac, and Linux.
Once the download is complete, we'll run the installer and follow the prompts to set up Git.
After installation is complete, we can open a terminal or command prompt and type ```git --version``` to verify that Git has been installed correctly.
Next, we'll configure Git by setting our user name and email address. This is important because every commit we make will be associated with this information. To set our user name and email, we'll use the following commands:
```shell
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```
## III. Basic Git workflow

- In this lesson, we'll learn the basic workflow for using Git to track changes in our files.
- First, we'll create a new repository. A repository is a collection of files that are being tracked by Git. To create a new repository, we'll use the ```git init``` command.
- Next, we'll make some changes to a file in our repository. For example, we might create a new text file and add some text to it.
- Before we can commit these changes, we need to stage them using the ```git add``` command. This tells Git to include the changes in our next commit.
- Now we're ready to commit our changes. We'll use the ```git commit``` command, and include a commit message to describe the changes we've made.
- We can view the commit history of our repository using the ```git log``` command. This will show us a list of all the commits that have been made, along with their commit messages.
- If we need to revert a change, we can use the ```git revert``` command followed by the commit hash. This will create a new commit that undoes the changes made in the specified commit.

## IV. Branching and merging

- In this lesson, we'll learn about branching and merging in Git.
- Branching allows us to create a separate line of development for our repository. This is useful when we want to make changes to our code without affecting the main branch.
- To create a new branch, we'll use the ```git branch``` command followed by the name of the branch. For example, ```git branch new-feature```.
- To switch to a different branch, we'll use the ```git checkout``` command followed by the name of the branch. For example, ```git checkout new-feature```.
- When we're ready to merge our changes back into the main branch, we'll use the ```git merge``` command followed by the name of the branch. For example, ```git merge new-feature```.
- If there are conflicts between the two branches, we'll need to resolve them manually. Git will mark the conflicts in the files and we'll need to edit the files to resolve the conflicts. Once we've resolved the conflicts, we can commit the changes to complete the merge.

## V. Collaborating using remote repositories

- In this lesson, we'll learn how to collaborate with others using remote repositories.
- A remote repository is a copy of our repository that is hosted on a server, such as GitHub. By pushing our changes to a remote repository, we can share our work with others and collaborate on projects.
- To work with a remote repository, we first need to add it to our local repository using the ```git remote add``` command. For example, ```git remote add origin https://github.com/myusername/myrepo.git```.
- We can then push our local changes to the remote repository using the ```git push``` command. For example, ```git push origin main```. This will send our commits to the "main" branch of the remote repository.
- If other people have pushed changes to the remote repository, we can pull their changes down to our local repository using the ```git pull``` command. For example, ```git pull origin main```. This will fetch the latest changes from the "main" branch of the remote repository and merge them into our local repository.

## VI. GitHub

- In this lesson, we'll learn about GitHub and how to use it to host our Git repositories.
GitHub is a popular platform for hosting and collaborating on Git repositories. It provides tools for project management, code review, and more.
- To create a new repository on GitHub, we'll need to sign up for an account and then click the "New repository" button. We can then give our repository a name and a description, and choose whether it should be public or private.
- Once our repository is created, we can push our local repository to GitHub using the same commands as when working with a remote repository. For example, ```git push origin main```.

- To collaborate with others on GitHub, we can use pull requests. A pull request is a request to merge changes from one branch into another. We can create a pull request by selecting the branches we want to merge and clicking the "Create pull request" button. Other people can then review the changes and approve or request changes to the pull request.
- GitHub also provides tools for project management, such as issues and project boards. We can use these tools to track tasks, bug reports, and other items related to our project.

## VII. Conclusion

- Congratulations on completing the course! I hope you've learned a lot about Git and GitHub and are feeling confident in your ability to use them in your work. Remember to continue practicing and learning as you use Git and GitHub in your projects. If you have any questions or need further assistance, don't hesitate to reach out. Thank you for joining me in this course, and happy coding!

<hr />

## Hands on project for the course:
- For the "Setting up Git" lesson, students could practice setting up Git on their own computers and configuring their user name and email address.
- For the "Basic Git workflow" lesson, students could practice creating a new repository, making changes to a file, staging and committing those changes, and viewing the commit history.
- For the "Branching and merging" lesson, students could practice creating a new branch, making changes to a file, switching between branches, and merging branches. They could also practice resolving merge conflicts if necessary.
- For the "Collaborating using remote repositories" lesson, students could practice adding a remote repository, pushing and pulling changes to and from the remote repository, and collaborating with others using a remote repository.
For the "GitHub" lesson, students could practice creating a repository on GitHub, pushing their local repository to GitHub, and using pull requests to collaborate with others on GitHub.

<hr />

## Cheat sheet
- Verify Git version: ```git --version```
- Configure Git: ```git config --global user.name "Your Name"```, ```git config --global user.email "your@email.com"```
- Create a new repository: ```git init```
- Stage changes: ```git add```
- Commit changes: ```git commit -m "Commit message"```
- View commit history: ```git log```
- Revert changes: ```git revert <commit hash>```
- Create a new branch: ```git branch <branch name>```
- Switch to a different branch: ```git checkout <branch name>```
- Merge branches: ```git merge <branch name>```
- Add a remote repository: ```git remote add <repo name> <repo URL>```
- Push changes to a remote repository: ```git push <repo name> <branch name>```
- Pull changes from a remote repository: ```git pull <repo name> <branch name>```
- Clone a repository: ```git clone <repo URL>```



