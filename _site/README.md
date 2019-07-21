# modular-website

## File Structure

The main pages are all files in the main root folder -- ie index.html, blog.html, archive.html, about.html etc. Each of these contains front matter at the top that includes any jekyll variables, links the relevant layout and includes SEO and social sharing meta data.

The style.css file contains all the CSS styles you need to edit (in the assets folder) and the main.js file contains all the custom javascript. Don't worry about the demo.css file, it's just there for the blocks.html demo page.

The _site folder is the output of your website, don't touch this folder as anything you change in here will be overriden with each change you make to the site.

The _posts folder contains all of the blog posts which are named with the convention year-month-date-title.md

The _layouts folder contains four layouts, the default layout for every page which pulls in the head, site header and site footer. The archive layout is for the category archive pages, which group archived blog posts, and the post layout is the layout for each individual blog post page. The demo layout is only used for blocks.html demo page.

The _includes folder contains the head.html, the site-header and site-footer to keep these organised. It also contains the social-sharing code that's at the bottom of each blog post, and the post-loop-items that are used in all of the blog post loops.

The _archives folder contains category archive pages. All you need to do to add new categories is create a new file here (or duplicate one of the existing ones), and make sure the front matter is correct for each new one.
