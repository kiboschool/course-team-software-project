# Using GitHub Wiki

GitHub Wiki is a feature provided by GitHub that allows for the creation of detailed documentation for your projects hosted on GitHub. It's a convenient way to organize and share extensive information, guidelines, or documentation with your team members and the project's audience. Each GitHub repository can have its own wiki, and the content is easily editable by anyone with access to the repository.

## How to Use GitHub Wiki

### Creating and Editing Wiki Pages

<aside>
If the wiki tab is not visible on your repository, you can enable it by going to the repository's settings and checking the "Wikis" box under "Features". You might need to change the repository's visibility to "Public" to enable this feature.
</aside>

1. **Create a New Page**: Click on "Create the first page" or "New Page" if you’re adding to an existing Wiki. You'll be taken to an editor.

2. **Title and Content**: Give your page a title and start adding content. GitHub wikis support Markdown, so you can format text, insert code snippets, images, and links.

3. **Save the Page**: Once you're done, summarize your changes at the bottom of the page and click "Save Page".

### Collaborating and Managing the Wiki

1. **Editing Pages**: To edit a page, navigate to that page in the wiki and click the "Edit" button. Make your changes and save them.

2. **Adding Collaborators**: Collaborators with write access to the repository can edit the wiki. You can manage access through the repository's settings.

3. **Cloning the Wiki**: GitHub Wikis are Git repositories. You can clone them to your local machine by clicking on the "Clone this wiki locally" link on the right sidebar of the wiki page. This allows offline editing and usage of Git commands for version control.

4. **Navigation and Sidebar**: For easier navigation, you can create a custom sidebar. Edit the "_Sidebar" page (or create it if it doesn't exist) to add links to your wiki pages.

5. **Version Control**: Just like code, changes to wiki pages are tracked. You can view the history of changes and revert to previous versions if needed.

### Best Practices for GitHub Wiki

- **Organize Content**: Structure your content logically. Use headings, subheadings, and a table of contents if necessary.

- **Consistent Style**: Maintain a consistent writing and formatting style for readability.

- **Regular Updates**: Keep the wiki updated with the latest project changes and decisions.

- **Encourage Collaboration**: Engage your team members to contribute to the wiki, ensuring a comprehensive and collective knowledge base.

- **Use for Documentation**: Utilize the wiki for extensive documentation like setup instructions, usage guides, project roadmaps, and FAQs.

GitHub Wiki is a flexible tool that helps in keeping your project's documentation organized and accessible. It’s an excellent way to ensure that everyone involved in the project is on the same page.

## Adopting the Template Wiki

You are free to create your own wiki pages and use whatever organization you want, as long as the sprint updates and team charter are accessible there.  If you would like to adopt the provided template, please follow the following steps (these are reproduced from Week 1 for your convenience).

**Clone the Template Wiki Locally**: Clone the template wiki to your local machine:

`git clone git@github.com:kibo-tsp-jan-24/tsp-wiki-template.git`

**Change Directory into Cloned Repository**: Change into the new cloned directory 

`cd tsp-wki-template`

**Remove Existing Origin**: Use the command 
`git remote remove origin` 
to remove the current origin (which you will not use again).

**Add New Origin**: You now want to add a new origin that corresponds to the repository that you created in Step 1 above. By appending `wiki` to the name of your repo, you can update the Wiki associated with that repo.  

For example, if your code repository is called `my-new-repo.git`, the wiki associated with that repository is `ny-new-repo.wiki.git`  In this case, you would add the new origin as follows: 

`git remote add origin git@github.com:my-new-repo.wiki.git` 

(**Note the addition of `wiki` into the repo name**).

**Push the Wiki**: Use this command to push to the new origin

`git push --set-upstream origin master --force`

This will entirely over-write the content and history of the wiki attached to the `my-new-repo` repository with the content and history from the wiki template.  

**Update the Wiki**: From this point on, you can edit the wiki either via the Wiki tab on the GitHub page for your repo, or you can edit it in your local repository, using git to commit and push any changes as you make them.