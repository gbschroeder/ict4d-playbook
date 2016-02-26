---
title: Contributing to this site
---

Thanks for helping to develop the Peace Corps ICT4D Playbook! This guide couldn't be done without the input of Volunteers, staff, and partners -- so please don't be shy about jumping in to add, edit, and improve it!
{: class="lead"}

If you want to just dive right in and start editing -- by all means! Absolutely anyone can make changes (or submit 'pull request' as changes!) -- it works very much like a wiki in that respect. Check out the [Editing](/editing/) page to learn how to sign up for a Github account and submit a [ticket for a change](https://github.com/peacecorps/ict4d-playbook/issues/new), edit the content itself, or edit the site itself in a few differents ways.

If you simply can't wait -- or just want to dip your toes into the waters of Peace Corps' ICT4D Initiatve -- then shoot us a tweet at [@peacecorpsict4d](https://twitter.com/peacecorpsict4d) or just send [an email](mailto:ict4d@peacecorps.gov) and it'll be handled with the utmost care.

Speaking of 'we' -- check out the [Community](/community/) page for more links to folks in Peace Corps ICT4D -- it's not just one office or unit sitting behind a desk in Washington, D.C. -- it's all Volunteers, staff, counterparts, and humans who want to help make the world a better place by leveraging technology!

OK -- now on to the nuts and bolts of how this ship is put together...

## How this site is built

This entire Playbook is hosted and shared on a platform called [Github](https://github.com). It's not just the host or server for the website—but it contains all of the content, the code that runs the site, this documentation, basically everything that's needed to run this site, all the version changes, and all the code glue that holds it together.

Basically, the way that it works is that all of the raw content is packaged as text files (Markdown) and folders, like a wiki (also called a 'flat-file' system). There's no database, no secret server content, no fuss, no muss. Why would we build it this way and not just throw it on the main Peace Corps server? Very simple -- for collaboration, transparency and sustainability.

The ICT4D team 'eats our own dog food' and practices what we preach. What better way to do that than to demonstrate that we—

- work in the open, that
- we build things iteratively, that
- we use open-source technologies wherever possible, and that
- we do everything with an eye towards keeping things **simple**.

This way, the next group of folks to improve the site (you?) won't have to rebuild it from scratch.

Let's dig a little deeper behind the scenes. Basically there are four components you need just some basic familiarity with:

- [Markdown](#markdown)
- [Prose.io](#proseio)
- [Github](#github)
- [Jekyll](#jekyll)



___



### Markdown

[Markdown](https://daringfireball.net/projects/markdown) is a markup language with plain text formatting, designed so that it can be converted to HTML. Markdown can be used to create rich text using a plain text editor.

Markdown is your key to formatting the text on the Playbook. Honestly -- you should learn it anyway as it is a much better way to write/format text for blogs, technical projects, even your resume!

By learning a few intuitive rules you’ll be able to ensure your text is formatted with headings, list, quotes etc, without writing any HTML. For examples, head to the [Writing in Markdown](/contribute/writing-in-markdown/) section.



___



### Prose.io

[Prose.io](http://prose.io/) is a simple content editor for GitHub designed for managing websites.

While it's possible to use Github's own editing features from the website to create and modify Markdown files, it's a **lot** cleaner and faster link up your Github account with Prose.io, and edit from that interface.

You can go directly to the [Peace Corps ICT4D Playbook](http://prose.io/peacecorps/ict4d-playbook), authorize your account with Github, navigate to the appropriate file, and begin editing away!



___



### Github

[GitHub](https://github.com) is a web-based repository hosting service, which amongst other things offers revision control and source code management via a web-based graphical interface.

Any changes you wish to make, whether they be edits to an existing page, or creating a new one, can be done via the Github website (it is also possible to download and edit the files on your local machine, instructions forthcoming).

All the files for this site can be browsed and edited from the [Github website](https://github.com/peacecorps/ict4d-playbook). You will need to [sign up](https://github.com/) for a (free) Github account. For full instructions, see [Editing a page](/contribute/editing/).



___



### Jekyll

[Jekyll](https://jekyllrb.com) is a static site generator, which allows us to host websites based on our GitHub repositories. Jekyll takes the content, renders Markdown, and produces a complete, static website ready to be viewed on the web.

All you really need to know about Jekyll is the method it uses to include metadata (ie. page title). Each page needs to start with a section it calls Front Matter, containing the page title. An example is provided in the [Adding a page](/contribute/adding/) section.



___


