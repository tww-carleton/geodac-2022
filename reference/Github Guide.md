 <h1 align="center"> GitHub Guide </h1> 

GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.
This tutorial teaches you GitHub essentials like repositories, branches, commits, and pull requests. 

In this quickstart guide, you will:

- [Create and use a repository](#creating-a-repository)
- [Start and manage a new branch](#branching)
- [Make changes to a file and push them to GitHub as commits](#making-and-committing-changes)
- [Open and merge a pull request](#opening-and-merging-pull-request)

To complete this tutorial, you need a [GitHub account](https://github.com/) and Internet access.

## Creating a repository

A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs.
<mark> *You will have to make a repository to upload all your project files for the final submission/ review.* </mark>

Often, repositories include a README file, a file with information about your project. README files are written in the plain text Markdown language. You can use this [cheat sheet](https://www.markdownguide.org/cheat-sheet/) to get started with Markdown syntax.

1. In the upper-right corner of any page, use the + drop-down menu, and select New repository.

  <p align="left" width="100%">
      <img src="https://docs.github.com/assets/cb-11427/images/help/repository/repo-create.png">
  </p>

2. In the repository name box enter your project title.

3. In the Description box, write a short description.

4. Select Add a README file.

5. Select whether your repository will be Public or Private. <em>For the Hackathon please create a public project repository.</em>

6. Click Create repository.

  <p align="left" width="100%">
        <img width="500" height="400" src="https://docs.github.com/assets/cb-106613/images/help/repository/hello-world-repo.png">
    </p>

## Branching

By default, your repository has one branch named `main` that is considered to be the definitive branch. You can create additional branches off of `main` in your repository. You can use branches to have different versions of a project at one time. This is helpful when you want to add new features to a project without changing the `main` source of code. The work done on different branches will not show up on the `main` branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to `main`.

When you create a branch off the `main` branch, you're making a copy, or snapshot, of `main` as it was at that point in time. If someone else made changes to the `main` branch while you were working on your branch, you could pull in those updates.

## Create a Branch

1. Click the **Code** tab of your repository

2. Click the dropdown at the top of the file list that says main.
 <p align="left" width="100%">
  <img src="https://docs.github.com/assets/cb-6252/images/help/branch/branch-selection-dropdown.png">
 </p>
 
 3. As soon as you click on the branch, you can find an existing branch or you can create a new one. 
 <p align="left" width="100%">
  <img width="800" height="400" src="https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2017/11/CreateBranches-how-to-use-GitHub-Edureka.png">
 </p>
 
Now you have two branches, main and readme- changes. Right now, they look exactly the same. Next you'll add changes to the new branch.

## Making and committing changes

**Commit Command:**
This operation helps you to save the changes in your file. When you commit a file, you should always provide the message, just to keep in the mind the changes done by you. Though this message is not compulsory but it is always recommended so that it can differentiate the various versions or commits you have done so far to your repository. These commit messages maintain the history of changes which in turn help other contributors to understand the file better. Now let’s make our first commit, follow the below steps:

1. Click on `readme- changes` file which we have just created.

2. Click on the `edit` or a ✏️ in the righmost corner of the file.

3. Once you click on that, an editor will open where you can type in the changes or anything. 

4. Write a commit message which identifies your changes.

5. Click **commit changes** in the end.

Refer to the below screenshot for better understanding:

<p align="left" width="100%">
  <img width="800" height="400" src="https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2017/11/Commit-how-to-use-github-Edureka.png">
 </p>

These changes will be made only to the `READM`E file on your `readme-changes` branch, so now this branch contains content that's different from `main`.

## Opening and merging pull request

### **Open a Pull request:** 

Pull request is the most important command in GitHub. It tell the changes done in the file and request other contributors to view it as well as merge it with the master branch. Once the commit is done, anyone can pull the file and can start a discussion over it. Once its all done, you can merge the file. Pull command compares the changes which are done in the file and if there are any conflicts, you can manually resolve it. Now let us see different steps involved to pull request in GitHub.

You can even open pull requests in your own repository and merge them yourself. It's a great way to learn the GitHub flow before working on larger projects.

1. Click the Pull requests tab of your repository.

2. Click New pull request

3. In the **Example Comparisons** box, select the branch you made, `readme-changes`, to compare with `main` (the original).

4. Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.

<p align="left" width="100%">
  <img width="600" height="200" src="https://docs.github.com/assets/cb-32937/images/help/repository/diffs.png">
 </p>

5. Click **Create pull request**.

6. Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.

7. Optionally, to the right of your title and description, click the ⚙️ next to **Reviewers**. **Assignees**, **Labels**, **Projects**, or **Milestone** to add any of these options to your pull request. You do not need to add any yet, but these options offer different ways to collaborate using pull requests. For more information, see ["About pull requests"](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests).

8. Click **Create pull request**.

Your collaborators can now review your edits and make suggestions.

### **Merge a pull request:**

In this final step, you will merge your `readme-changes` branch into the `main` branch. After you merge your pull request, the changes on your `readme-changes` branch will be incorporated into `main`.

Go through the below steps to merge pull request.

1. Click on **Merge pull request** to merge the changes into master branch.

2. Click **Confirm merge**

3. You can delete the branch once all the changes have been incorporated and if there are no conflicts. Refer to the below screenshots.

<p align="left" width="100%">
  <img width="800" height="400" src="https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2017/11/Merge-command-how-to-use-github-Edureka-1.png">
 </p>

You have now 
- Created an open source repository
- Started and managed a new branch
- Changed a file and committed those changes to GitHub
- Opened and merged a pull request

You can go ahead and make your reposiories the same way.

For more information about the power of branches and pull requests, see ["GitHub flow"](https://docs.github.com/en/get-started/quickstart/github-flow). For more information about getting started with GitHub, see the other guides in the [getting started quickstart](https://docs.github.com/en/get-started/quickstart).
