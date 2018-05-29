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
