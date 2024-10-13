# Starter Templates

To help you get started on the project, we are providing a couple of starter templates for your code and for your project documentation. This is a brief introduction to those templates with instructions on how to adopt them. Though you already have familiarity with Git, we will dive deeper in the coming weeks to 

## GitHub Repository

We have provided two implementations of a basic app that supports multiple users creating and viewing their own posts.  The first implementation uses JavaScript with [Express](https://expressjs.com/).  The second implementation uses Python with [Flask](https://flask.palletsprojects.com/en/3.0.x/).  In both cases, the templates leverage [Bootstrap](https://getbootstrap.com/) for basic styling, [SQLite](https://www.sqlite.org/index.html) as the database, and [Prisma](https://www.prisma.io/) as the ORM.  

To help you get started on the right foot, the templates have some initial examples of unit testing (which you should improve and update), and support for linting and formatting. Pease refer to each template's README file for full details.

- [Express Starter Template](https://github.com/kibo-tsp-jan-24/tsp-express-starter-template)
- [Flask Starter Template](https://github.com/kibo-tsp-jan-24/tsp-flask-starter-template)
- [GitHub Wiki Template](https://github.com/kibo-tsp-jan-24/tsp-wiki-template)

## Instructions

The following steps for getting up and running are provided here and discussed here so that you can get a quick start on your project.  More details about using GitHub Repositories, GitHub Projects, and GitHub Wiki are provided in Week 2.

### Step 1: Create a GitHub Repository

1. **Choose a Team Member to Create the Repository**: One team member should create a new repository on GitHub. Go to [GitHub](https://github.com/) and sign in.
2. **Create a New Repository**: Click on the "+" icon in the upper right corner and select "New repository". Note: Alternatively, if you are going to make use of a starter template, then one team member should fork that appropriate repository using the Fork button on the appropriate GitHub repository from above and update the repository's settings as described below.
3. **Repository Settings**:
   - **Name**: Choose a meaningful name for your project.
   - **Description**: Briefly describe your project.
   - **Visibility**: Set to private.
   - **Initialize this repository with**: Choose to add a README and .gitignore (select the appropriate language/framework).  No license is necessary.
4. **Create Repository**: Click the “Create repository” button (if you did not fork an existing repository).

### Step 2: Add Team Members as Collaborators

1. **Access Settings**: In the repository, go to “Settings”.
2. **Manage Access**: Click on “Manage access” and then “Invite a collaborator”.
3. **Invite Team Members**: Enter your teammates’ GitHub usernames and send the invitations.
4. **Invite Instructor**: Enter your instructor's GitHub username providing using their GitHub username (`mhassanist`).

### Step 3: Adopt the Wiki Starter Template

1. **Enable the Wiki**: If you can't see the "Wiki" tab in your GitHub repository, go to “Settings” and then “Features.” Enable the Wiki feature there. You might need to make your repository public to enable the wiki.

2. **Create a sample page**: From Github, click on the "Wiki" tab.  Click on "Create the first page" and create a sample page.  This will create a new wiki for your repository.  

To adopt the wiki template, follow the below steps:

1. **Clone the Template Wiki Locally**: The template wiki to your local machine: `git clone git@github.com:kibo-tsp-jan-24/tsp-wiki-template.git`
2. **Change Directory into Cloned Repository**: Change into the new cloned directory (`cd tsp-wki-template`)
3. **Remove Existing Origin**: Use the command `git remote remove origin` to remove the current origin (which you will not use again).
4. **Add New Origin**: You now want to add a new origin that corresponds to the repository that you created in Step 1 above. By appending `wiki` to the name of your repo, you can update the Wiki associated with that repo.  For example, if your code repository is called `my-new-repo.git`, the wiki associated with that repository is `ny-new-repo.wiki.git`  In this case, you would add the new origin as follows: `git remote add origin git@github.com:my-new-repo.wiki.git` (**Note the addition of `wiki` into the repo name**).
5. **Push the Wiki**: Use this command to push to the new origin `git push --set-upstream origin master --force`.  This will entirely over-write the content and history of the wiki attached to the `my-new-repo` repository with the content and history from the wiki template.  
6. **Update the Wiki**: From this point on, you can edit the wiki either via the Wiki tab on the GitHub page for your repo, or you can edit it in your local repository, using git to commit and push any changes as you make them.
