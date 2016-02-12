---
title: Adding a page
---

Most of what you need to know to add a new page is covered under ‘[Editing a page](/editing/)’, so make sure you have first read through that section.

'Adding a page' follows a similar process to editing. Instead of locating your page, your first step is to locate your new page’s parent directory (or folder) -- we want to see where this thing should live.



## 1: Create the page

First locate the parent directory, or folder, in which your file will live. If you are adding a page to the Toolkits, for example, you should be in the '**Toolkits**' directory, where you’ll see a list of all the Toolkit pages.

Above the list of pages is a breadcrumb trail `{{ site.github_repo }} / toolkits /`, to the right of which is a plus symbol `**+**`. Click the plus symbol to create your new page.



## 2: Name your file

You should now have a new file editor page open. The first editable section you are presented with is the ‘_Name your file_’ field. As we touched upon when looking at [editing files](/editing/), the file name corresponds to the URL of the page on the site. There are a few of rules to follow here:

*   The file name should reflect the title of the new page
*   Must be unique
*   Should be all lowercase
*   Words should be separated by hyphens (-)
*   File name should end with the extension '_.md_' (the .md extension indicates a markdown file)

As an example, if you were creating a page titled '_My Cool Page_', you would use a file name of:

    my-cool-page.md

Assuming you are creating this in the '_toolkit_' directory, this would result in a URL of _{{ site.url }}/toolkit/my-cool-page_

<div class="note">

###### Note

The actual words used in your file name are not crucial. It’s fine to use a more succinct version of your page title, for example.

</div>

## 3: Formatting your content

This step is the same as when editing a page. You need to start your file with the Front Matter, then add your content, formatting it using Markdown. Here is a template to get you started:

    ---
    title: My Cool Page
    authors:
     - Fred Bloggs
    ---

    ## A large introductory paragraph.

    Regular paragraphs, separated by empty lines.

    ### A heading

    Another paragraph.

     * Maybe
     * a
     * list

When you’re done, click ‘_Propose new file_’.

## 4: Make a pull request

Once you have created your page(s) and updated the contents document, you're ready to make your pull request. Click the pull request icon to the right of the screen `<span>[git pull-request icon]</span>`, then click ‘_New pull request_’.

You should now be able to see listed below, all the changes that you wish to contribute. If everything looks as it should, click ‘_Create pull request_’.

Give your pull request a title and description, then click ‘_Create pull request_’. You have now contributed your pages to the Playbook! :)


