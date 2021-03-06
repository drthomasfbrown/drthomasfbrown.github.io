---
published: false
---

This blog is built using Jekyll and hosted on Github for free. Everything is managed via the Internet browser on my Chromebook -- I have not downloaded any software at all. I've been interested in Jekyll for years, but I didn't want to have to install Ruby and learn it. It seemed like too much technical overhead. At the same time, I wanted to be able to write to text files in Markdown, enjoy the free hosting on Github, and have a high level of control over my site's look and functionality.

The solution: [Jekyll Now](https://github.com/barryclark/jekyll-now). Installation is a breeze. You create a Github account. You "fork" Jekyll Now, which basically means you make a copy from the author's Github account into your own account. You open your local copy's config file and enter your own site name and address, and you have a blog. It takes five minutes. Detailed instructions [are here](http://www.smashingmagazine.com/2014/08/build-blog-jekyll-github-pages/).

The way it works is that the Jekyll software is built into Github pages, so you don't need to run it on your own computer. You just "commit" (save) your file in the appropriate Github folder, and Github automatically runs your writing through Jekyll, thereby transforming it into a blog post or page.

### Writing and editing

You can create and write posts and pages directly in the browser using Github's own editor. You can also write in the browser using [prose.io](prose.io), which is a more full-featured editor that sits on top of Github. Use it for free. I generally use prose.io to write a long post, and use the native Github editor for making small corrections.

### Adding features to your blog

The initial Jekyll Now install is bare bones. Justin James has written [an excellent series of tutorials](http://digitaldrummerj.me/blogging-on-github-part-1-Getting-Started/) that will help you to get started with Jekyll Now, and to flesh out your web site with more features. I have used his tutorials to add a category search, a Google search, and Disqus comments to my blog.

One caution: When I cut and pasted his code, I introduced some extra tab indentations that were not in his original code. This caused the code not to work right, until I went back and undid the superfluous tabs. Other than that error that I introduced myself, everything worked perfectly.

A second caution: The css for the Search feature goes before the import statements at the bottom of the css file. If you put it at the top it won't work right.

### Customizing the look of your blog

You have full access to the css and layout files for your blog in your Github account. You can change anything you want. I have played around with some Google web fonts, but eventually went back to the original Jekyll Now fonts. I did make my avatar photo a tad larger -- because I am one beautiful monkey.

The biggest disadvantage of doing this in the browser is that Github sometimes takes a few minutes before your changes are processed. When you are trying to make cosmetic design changes, you kind of want to see what they look like right away. Also, sometimes you don't know if they worked or not until you've spent five minutes refreshing the screen to see if anything happened after your last commit. It's not an ideal way to do web design, to say the least.
