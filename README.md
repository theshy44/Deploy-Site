# Deploy Your Website With Web Server For Chrome
Deploying means that making the content or software accessible and available for use. The website that you'll deploy will be public or live on the internet, it will be accessible to anyone with open internet access at anytime, anywhere in the world. Here is the starting [Guide](https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en)



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
