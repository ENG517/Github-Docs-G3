# Pull Request Template

Use the below headings to structure the content of your Pull Request.

## Loy edits to pushing-changes-to-github-from-github-desktop.md



## Staging

### Focus on users' goals
* I added a title: *"Pushing changes to GitHub from GitHub Desktop"*
* Made the initial title a subtitle: *"About pushing changes to {% data variables.product.prodname_dotcom %}"*
* I added a context sentence to orient the user to the task: *"As you make changes to files on your local project through GitHub Desktop, you can push those changes to GitHub so that others can view and access your edits to a repository."*

### Present information that situates the user
* I split up the **About** section to have a conceptual part (*"About pushing changes to{% data variables.product.prodname_dotcom %}"*) and a prerequisite part (*"Before pushing changes to {% data variables.product.prodname_dotcom %}"*).
* I isolated the section about rulesets. This is more of an added set of information rather than a crucial piece of the puzzle for users when they go to push a change in GitHub.



## Coaching

### Added a crucial step
* I think that the step where you actually click **Push change** was missing before, so I added it in and included a screenshot for reference. I tried to keep it short and succinct.
* I made small edits to the language used in Step 2, which talks about how to **Preview a Pull Request** before pushing it. I made sure users know that this part is not necessary to perform in order to get the desired action, but it could be useful to a user's workflow.



## Alerting

### Added notes/block quotes
* I pulled pieces of conceptual information out of the "About" section and placed them as alerts in their own block quote. Here are some examples:
    > **Note:** To push changes to a repository, you must have write permissions. These permissions are managed by your repository's admin.
    
    > **Note:** If someone has made commits on the remote that are not on your local branch, {% data variables.product.prodname_desktop %} will prompt you to fetch the new commits before pushing your changes to avoid merge conflicts.
    
    > **Note:** If there are commits on the remote branch that you don't have on your local branch, {% data variables.product.prodname_desktop %} prompts you to fetch new commits from the remote. In the "New Commits on Remote" window, click **Fetch**.

These notes help inform the user of potential consequences (like not being able to make changes to a repository or merge conflicts happening) and solutions (like ensuring you have write permissions and committing changes before submitting a pull request).