---
title: Editing a page
---

If you haven’t done so already, the first thing you need to do is head over to [Github](https://github.com/) and create your free account.
{: class="lead"}

There are three steps to editing a page. First, you need to locate the page you wish to edit. Then you need to make your edits. Finally, you'll want to submit the changes (submit a 'pull request') and provide some comments on what you've proposed to change.

## 1: Locate the page

There are a few different ways of doing this. **Method A** is probably the simplest, and most likely what you'll want to do. **Method B** gets us a little further and helps give us to see the folder hierarchy of the site in a clean interface, and **Method C** gets us into the Github platform entirely, which is the most flexible way of looking at the code, and will be most helpful when actually [adding more pages](/adding/).

##### Method A: Locate from the Playbook site

While reading any page of the Playbook you’ll see an '**Improve this page**' button on the right side of the screen (but not in mobile). Hovering over this button will show three buttons, two that take you directly to an editable version of that page -- and then these help pages (lest you forget).

<div class="note">

###### Permissions

When the editable page opens it will (most likely) contain a message saying *“You're editing a file in a project you don't have write access to”*. If this is your first edit to Playbook it will say *“We've created a fork of this project for you to commit your proposed changes to”*. This is normal and part of the workflow.

</div>


#### Method B: Locate by browsing the Prose.io interface

As I said before in the intro, Prose.io is a third-party service that lets us look at the simple text files underlying the site in a slick interface. The **content-heavy** files of this site can be browsed from Prose.io. So for example, the root of the site is [here](http://prose.io/#peacecorps/ict4d-playbook/), and the 'Program Areas' section is [here](http://prose.io/#peacecorps/ict4d-playbook/program-areas/) -- see how it's just folders and files? Neat, huh?

It’s helpful to understand that the page URLs (mostly) correspond to the file structure you see here. So, if you wanted to edit the Playbook introduction page, given that it’s URL is `{ site.url }}/introduction/` we know this file can be found in the `guide` directory with the filename `introduction.md` *Note: the extension (.md) is stripped from the URL.* Following these links you should see a preview of the page you wish to edit. From here click the edit icon `<span>[pencil icon]</span>` to start editing.



#### Method C: Locate by browsing the Github repository

Going straight to the source -- the **entire file structure** of this site can be browsed on Github. For example, the root of the site is [here](https://github.com/{{ site.github_username }}/{{ site.github_repo }}), and the Program Areas section is [here](https://github.com/{{ site.github_username }}/{{ site.github_repo }}/tree/gh-pages/program-areas/). Just like with the Prose.io interface from Method B, the page URLs correspond to the file structure you see here. So, if you wanted to edit the Playbook introduction page, given that it’s URL is `{{ site.url }}/introduction/` we know this file can be found in the `guide` directory with the filename `introduction.md` *Note: the extension (.md) is stripped from the URL.* Just like with Prose, following these links you should see a preview of the page you wish to edit. From here click the edit icon `<span>[pencil icon]</span>` to start editing.


## 2: Make your edits

With the editable content in front of you, you’re probably either thinking “great, let’s get editing”, or “hang on, this looks a bit weird”. In case it’s the latter, let’s have a closer look.

The important thing to recognise is the Markdown syntax. For example, where you see a line commencing with two hash marks:

    ## How to run an Hour of Code lesson

This is the Markdown way of creating a level two heading. On the site it will be outputted like so:

## How to run an Hour of Code lesson

Another common formatting requirement is bullet points, or lists. These are achieved in Markdown by using asterisks, like so:

    * Environment
    * Education
    * Health

giving you:

*   Environment
*   Education
*   Health

Links are created like so:

    Find out more about [Madagascar](http://madagascar.peacecorps.gov/).

result:

Find out more about [Madagascar](http://madagascar.peacecorps.gov/)

<div class="note">

###### Pro Tip!

To get a link to a specific heading on this site, hover over it then click the section icon `<span>[section icon]</span>`. This will put the URL into your address bar.

</div>

More Markdown examples can be found on the [Writing in Markdown](/writing-in-markdown/) page, which is a great reference. You can also check out a [10-minute tutorial](http://markdowntutorial.com/) for some hands-on practice, and finally, the detailed overview [here](http://daringfireball.net/projects/markdown/syntax) that started it all.

If you are unsure of your markup while editing, you can switch to the preview tab `<span>[eye icon]</span> Preview changes` to see how it will be rendered.

Quick aside, in Github, the first thing you'll see is the ‘Front Matter’, which will look like this:

    ---
    title: Introduction
    ---

The front matter must be the first thing in the file, must adhere to the above syntax, and must be set between triple-dashed lines. Numerous variables can be set here, but you’ll usually just need `title`. The title set here will be used as the main heading for the page, as well as in the browser tab.

<div class="note">

###### Note

The Github previews will look stylistically different from the live site. A different font will be used for example.

</div>

Once you are happy with your changes, add a summary of what you've changed in the field below the editable text. Then click ‘_Propose file change_’.

## 3: Make a pull request

You will now be presented with a ‘pull request’ form. So far, the changes you have made are to your own copy, or fork of the Playbook. A pull request simply sends a request to the authors/maintainers of the live Playbook, asking them to include your changes - and put them live! Add any comments you have for the Playbook team, then press ‘_Create pull request_’.

Your work here is done :) If you need to make related changes though, any new commits pushed to your branch will automatically be added to the pull request.

I know it seems complicated -- but this is Peace Corps. If it's taught us anything, it's that having rules for collaboration and communication in place end up helping everyone. :smile:

