---
layout: default
title: Add a Page
collection: contribute
redirect_to: https://playbooks.idmanagement.gov/contribute/#add-a-page
permalink: contribute/addpage/
---

Before you add a new page, see the list of existing issues. You can add a new issue to propose a topic, or comment on an existing issue. By creating or discussing an issue, you can clarify a problem, identify a solution, and propose a format for a new page. When you’re ready, comment on the related issue that you want to write the new page.

To add a page and open a pull request, you must first [create a GitHub account](https://github.com/join){:target="_blank"}. We recommend that you [configure two-factor authentication](https://help.github.com/en/articles/configuring-two-factor-authentication){:target="_blank"} for your GitHub account.

## Create a Page

1. (Optional) If you want to begin with a template page, navigate to the [template.md](https://github.com/GSA/ficam-arch/blob/staging/template.md) file.

	The template file includes some instructions for how to organize a page.

2. In the upper right corner, click the **Raw** button to view the raw code.

3. Copy the content of the template.

4. Navigate to the ficam-arch/pages folder, and in the upper right corner, click the **Create new file** button.

	![A screenshot of the Code tab of the FICAM-Arch Github repository, where the user has clicked Add file, then Create new file.]({{site.baseurl}}/img/contribute/CreateNewFile.png)
	
5. At the top of the screen, enter a name for your new page with the extension **.md**.

	The **.md** extension identifies a markdown file.
	
	![A screenshot of the file path of the new page, where there is a text box to edit the file name.]({{site.baseurl}}/img/contribute/NameNewFile.png)
	
6. In the body of the file, paste the content that you copied in step 3.

	Use this template as a guideline for your page.

## Submit a Page

1. Scroll to the **Commit new file** box.

	![A screenshot of the Commit new file box, where you can type a description for the file and choose where to commit the change.]({{site.baseurl}}/img/contribute/CommitNewFile.png)

2. Enter a name and description for your new page.

3. Select the **Create a new branch for this commit and start a pull request** radio button.

	This allows the file to go through the proper review process before publishing.
	
4. Click the **Propose new file** button.

	The **Open a pull request** page appears.
	
	![A screenshot of the Open a pull request page, where you can type a description for the pull request and submit the request.]({{site.baseurl}}/img/contribute/OpenPullRequest.png)
	
5. If there is a corresponding issue that identifies a need for this page, include the issue number in the description.

6. Click the **Create pull request** button.

	The site administrators receive a notification about the new page, and they can revuew and publish the page.
