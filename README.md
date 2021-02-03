this project will be contained in a new repository !! coming soon! 

# Express (Backend) Template

The server part of this template provides a basic [ExpressJS](https://expressjs.com/) template, i.e., the basic infrastructure for an Express application.

Read more on the backend part in [server/README.md](server/README.md)

# Vue.js (Frontend) Template

The client part of this template provides a basic [Vue.js](https://vuejs.org/) template, i.e., the basic infrastructure for a frontend SPA page.

Read more on the frontend part [client/README.md](client/README.md)

# Cloning the Repository

```bash
# Without Gitlab Registration
git clone https://gitlab.com/dit341/express-template.git

# With Gitlab Registration
git clone git@gitlab.com:YOUR_USERNAME/express-template.git
```

# Deployment

Deployment instructions for Heroku are found in [DEPLOYMENT.md](DEPLOYMENT.md)




To do so, follow these instructions (A longer, more detailed version is found [here](https://digitaldrummerj.me/git-syncing-fork-with-original-repo/)):


. Add the original repository as a so-called upstream repo:  
```git remote add upstream https://gitlab.com/dit341/express-template.git```
. Fetch all changes from the original repo:  
  ```git fetch upstream```
. Merge the changes in the original repo with your local master branch:  
```git merge upstream/master```  
Note that this might cause conflicts that you have to resolve manually!
. Once you are done, you can push the merged repository to your own (remote) repository:  
```git push origin master```
