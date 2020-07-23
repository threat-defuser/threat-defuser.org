

# THREAT-DEFUSER website

The sources behind https://threat-defuser.org.

Templates and sass sources adapted from https://github.com/bennetthardwick/simple-dev-blog-zola-starter
(MIT license).


### How this works

The website sources are hosted on GitHub (here) and the website is deployed via
GitHub pages.

The source code resides on the `master` branch and upon ever change it
auto-generates the `gh-pages` branch which containes the generated HTML code.

The HTML code is generated using [Zola](https://www.getzola.org/) static site
generator.

To edit content, you most of the time only need to edit Markdown files and
[Zola](https://www.getzola.org/) auto-generates HTML from these.


### How to contribute changes

To add/edit content, modify files inside the <content> folder.  You can modify
these via the web or using GitHub Desktop or using the command line by opening
pull requests (change proposals).

If you want to add new pages to the navigation bar or modify the navigation
bar, modify `navigation` in <config.toml>.

You can change the looks if you know your way around CSS/SASS.

You can modify the page layouts by editing files inside the <templates> folder.


### How to preview changes locally

Install [Zola](https://www.getzola.org/), then run:
```
$ zola serve
```
