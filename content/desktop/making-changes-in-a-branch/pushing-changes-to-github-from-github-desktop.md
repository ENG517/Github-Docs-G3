---
title: Pushing changes to GitHub from GitHub Desktop
shortTitle: Pushing changes
intro: 'As you commit changes to your project locally, you can push those changes to {% data variables.product.prodname_dotcom %} from {% data variables.product.prodname_desktop %} so that others may access them from the remote repository.'
permissions: People with write permissions can push changes to a repository.
redirect_from:
  - /desktop/contributing-to-projects/pushing-changes-to-github
  - /desktop/contributing-and-collaborating-using-github-desktop/pushing-changes-to-github
  - /desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/pushing-changes-to-github
  - /desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/pushing-changes-to-github-from-github-desktop
versions:
  feature: desktop
---
# Pushing changes to GitHub from GitHub Desktop
As you make changes to files on your local project through GitHub Desktop, you can push those changes to GitHub so that others can view and access your edits to a repository.

> **Note:** To push changes to a repository, you must have write permissions. These permissions are managed by your repository's admin.

## About pushing changes to {% data variables.product.prodname_dotcom %}
When you push changes, you send the committed changes in your local repository to the remote repository on {% data variables.product.prodname_dotcom %}. If you change your project locally and want other people to have access to the changes, you must push the changes to {% data variables.product.prodname_dotcom %}.

## Before pushing changes to {% data variables.product.prodname_dotcom %}
Before pushing changes, update your local branch to include any commits that have been added to the remote repository. This ensures that you have the latest version of the repository before you merge your work.
> **Note:** If someone has made commits on the remote that are not on your local branch, {% data variables.product.prodname_desktop %} will prompt you to fetch the new commits before pushing your changes to avoid merge conflicts.

For more information, see "[AUTOTITLE](/desktop/working-with-your-remote-repository-on-github-or-github-enterprise/syncing-your-branch-in-github-desktop)."

{% data reusables.desktop.protected-branches %}

{% ifversion repo-rules %}

## Pushing changes with rulesets
Repository administrators can also enable rulesets for a branch, which will prevent a push from completing if a ruleset has not been followed. For example, a ruleset may require a specific branch naming convention, or an issue number at the start of a commit message. {% data variables.product.prodname_desktop %} will warn about rulesets to help prevent your branch from getting into a state where you would be unable to push your changes. For more information, see "[AUTOTITLE](/repositories/configuring-branches-and-merges-in-your-repository/managing-rulesets/about-rulesets)."

{% endif %}

## How to push changes to {% data variables.product.prodname_dotcom %}

1. After you've committed your changes to the local branch, click **Push origin** in the repository bar.

   ![Screenshot of **Push origin** button](https://docs.github.com/assets/cb-17787/mw-1440/images/help/desktop/push-to-origin.webp)



2. Optionally, click **Preview Pull Request** to open a preview dialog where you can review your changes before creating a pull request. For more information, see "[AUTOTITLE](/desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request-from-github-desktop)."

   ![Screenshot of the "No local changes" view. A button, labeled "Preview Pull Request", is highlighted with an orange outline.](/assets/images/help/desktop/mac-preview-pull-request.png)



>{**Note:** {% data variables.product.prodname_desktop %} will reject a push if it exceeds certain limits.
>* A push contains a large file over {% data variables.large_files.max_github_size %} in size.
>* A push is over {% data variables.large_files.max_file_size %} in total size.
>If you configure {% data variables.large_files.product_name_long %} to track your large files, you can push large files that would normally be rejected. For more information, see "[AUTOTITLE](/desktop/configuring-and-customizing-github-desktop/about-git-large-file-storage-and-github-desktop)."



## Further reading

* "[AUTOTITLE](/get-started/learning-about-github/github-glossary#push)" in the {% data variables.product.prodname_dotcom %} glossary
* "[AUTOTITLE](/desktop/making-changes-in-a-branch/committing-and-reviewing-changes-to-your-project-in-github-desktop)"
* "[AUTOTITLE](/get-started/using-git)"
