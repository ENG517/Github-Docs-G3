---
title: Cloning a repository from GitHub to GitHub Desktop
intro: 'You can use {% data variables.product.prodname_dotcom %} to clone remote repositories to {% data variables.product.prodname_desktop %}.'
redirect_from:
  - /desktop/contributing-to-projects/cloning-a-repository-from-github-to-github-desktop
  - /desktop/contributing-and-collaborating-using-github-desktop/cloning-a-repository-from-github-to-github-desktop
  - /desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-a-repository-from-github-to-github-desktop
versions:
  feature: desktop
shortTitle: Clone a GitHub repo
---
## Introduction
Cloning a repository allows you to save a copy of a repository hosted on GitHub to your computer. However, this copy is still connected to the original remote repository. Using GitHub Desktop and your text editor of choice, you will manage and edit the files in this repository on your local computer, and then post your updates for review.

## Prerequisites
Before you can clone a repository you must:
1. Have created and authenticated a GitHub account and have your credentials handy.
2. Sign in to **both** {% data variables.location.product_location %} and {% data variables.product.prodname_desktop %} before you start to clone.
{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.open-with-github-desktop %}
3. Install GitHub Desktop on to your computer. For more information on installing GitHub Desktop, see "[AUTOTITLE](/desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop)."
4. Check that you have permission to clone the repository. If you do not, contact the original creator or another admin of the repository to gain access.

> **Tip:** It can be helpful to create a new folder, or decide on an existing folder, within your local library for storing your repository before you begin the cloning process.

## Cloning the Repository
1. Open GitHub in your browser, and navigate to the repository you want to clone.
2. Click the dropdown arrow on the green "Code" button on the top right side of the repository's main page.
   
   ![Screen shot of the top bar of the repository's main page, highlighting in white the right most button labeled "Code"](https://i.imgur.com/nRdu8pA.png)
   
3. Select "Open with GitHub Desktop". _GitHub Desktop should automatically open when you click this option._
   ![Screenshot of the "Code" pop-up window.](https://i.imgur.com/Nk2eFkW.png)

   {% note %}
     > **Note:** You may recieve a pop-up, like the one below taken from Google Chrome, asking for permission. 
     ![Screenshot of Google Chrome's pop-up for opening GitHub Desktop](https://i.imgur.com/0F8Oq2C.png)
     > It is reccomended to select "always allow". 
     
     > If GitHub Desktop does not open, and you do not recieve a notification, check your browser's pop-up settings.
     {% endnote %}

4.  Once GitHub Desktop is open, click **Choose...** on the open pop-up. Use the resulting pop-up to select which folder you want to house the cloned repository in. 

       ![Screenshot of the "URL" tab of the "Clone a Repository" window. Next to the "Local Path" field, a button, labeled "Choose", is highlighted with an orange outline.](/assets/images/help/desktop/clone-choose-button-url-mac.png)

       {% note %}

       > **Note:** If the repository is configured to use LFS, you will be prompted to initialize {% data variables.large_files.product_name_short %}.
       {% endnote %}

5. Check that the address in the "Local Path" bar matches the location you just selected. 
  ![creenshot of the "URL" tab of the "Clone a Repository" window. In the "Local Path" field, the location you selected should be listed.](https://i.imgur.com/Bj8H9u5.png)
    > **Note:** The last portion of the address should *always* be the repository's name.
6.  Click **Clone**. If the repository contains many files, it may take a few minutes to finalize the clone.

{% tip %}

> **Tip:**  You also can use {% data variables.product.prodname_desktop %} to clone repositories that exist on {% data variables.product.prodname_dotcom %}.  For more information, see "[AUTOTITLE](/desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop)."

{% endtip %}
