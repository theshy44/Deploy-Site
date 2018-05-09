# Introduction
Deploying means that making the content or software accessible and available for use. The website that you'll deploy will be public or live on the internet, it will be accessible to anyone with open internet access at anytime, anywhere in the world.
## By the end of this task you will have:
* generated a static site
* Deployed it to the internet
* Given the website a custom domain name

NOTE: WE'LL MAKE EXTENSIVE USE OF THE COMAND LINE AND GIT IN THIS TASK.

# Jekyll: Oveview
The focus of this task will be on the process of deploying the website not creating it. we'll use a tool known as JEKYLL to quickly generate a website. Jekyll is a simple static site generator. 
## Installing Jekyll
Before we can generate a website, we must install jekyll. jekyll is a ruby gem and can be installed from the command line, once jekyll is installed. We can us it to generate your site.
* 1. Install Jekyll by typing on the terminal 
[installation guide](https://jekyllrb.com/docs/installation)
Great! now that jekyll is installed, let's generate your website. To do so, we'll use jekyll new command an specify a directory name. The directory will contain all your sit defult content that can be customised later.
* 2. In the terminal, use Jekyll new command to generate your static website with a directory name "one-page-website"
```
jekyll new one-page-website
```
The command will create a directory called one-page-website with jekyll site content.use ls command to verify that the directory was successfully generated

## preview your site locally
On the web, a server host your site file amd makes your website available for everyone to see. However, viewing a website locally means that you're viewing the site on your computer. The site is not vaialble on the public internet, instead, your computer is acting as the server that host your site. To view your site you must first navigate to your site directory using the cd command.

* 3. View your site locally using
```
jekyll serve
```
this command starts a local server that will serve the files to your computer. By default the address for local server is 
```
Http:localhost:4000/
```
### Jekyll's Directory Structure
The website that Jekyll generates differs from a website that you'd create on your own. It offers a standard directory structure, as well as components that help speed up development.

It's important to understand Jekyll's default directory structure and contents of your site:

_config.yml - This is a configuration file that contains many values that need to be edited only once. These values are used across your site, for example, your site's title, your e-mail, and more. Note that this is a .yml file.

_includes/ - This directory contains all the partials (code templates that keep you from repeating your code over and over) that your site uses to load common components, like the header and the footer.

_posts/ - This directory is where blog posts are stored. New blog posts can be added and will be rendered with the site's styling, as long as the file name follows Jekyll's standard naming convention.

_layouts/ - This directory contains templates that are used to style certain types of posts within the site. For example, new blog posts will use the HTML layout defined in post.html.

# Deploy your website for github page
* 1. Create a repo
* 2. Initialize an empty repo locally using
```
git init
```
use the cd command to navigate to your site directory before creating an empty repo
* 3. Add the Remote
git needs to know what repo will store your site content. to specify the repo using git w'll ad the remote and label it as origin
```
git remote add origin "url"
```
* 4. Commit your changes
```
git add .
```
```
git commit -m "save my work"
```
* 5. Deploy your site
```
git push -u origin master
```
