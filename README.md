# OneDoc

Document Sharing System Software

### Team Members

- Khristian Brooks
- Connie Wu
- Songren Zhao
- Chantelle Levy

### How to Contribute

To contribute, clone the repo and create a new branch.

You can use the following code to create a new branch, replacing `newBranchName` with the name of the branch you are trying to create.
`git checkout -b newBranchName`

After you create this branch, run:
`git push --set-upstream origin newBranchName`
This will create a remote branch in Github that is a copy of the branch you created locally.

Once your local branch and remote branch is created you can make your changes on this branch. This branch is seperate from the master branch, so even if you make a huge mistake and mess up everything, it will not affect already existing code on master.

When you are done making your changes on your local branch, you can push your remotely push changes to GitHub:
`git push`

Now, it's time to create a Pull Request! In your browser, go to the repo in Github. Click the button to "Compare & pull request" button as shown in the image below:

<img src="/src/img/CreatingPR.png" width="500"/>

This will create a Pull Request with all your changes that can be viewed by other contributors to this repo. Once it has been approved, you can merge this pull request into master.

### To run from cloning:
Have Node.js/yarn installed on host machine  
Also have MySQL DBMS installed  
Or if preferred, customize the config file to use a different DBMS dialect  
Run the app on a terminal with the following commands in the project directory:  
&nbsp;&nbsp;&nbsp; $ yarn install  
&nbsp;&nbsp;&nbsp; $ yarn start

Also, have another terminal to run node server.js

Open http://localhost:3000 to view it in the browser.


### To access Specific Pages of the Project

- For guest to apply for OU, the user has to enter ```localhost:3000/ouapplication```
- For OU/SU to process the complains, the user has to enter ```localhost:3000/processcomplain```
- For OU to accept the invitation, the user has to enter ```localhost:3000/accordenyinv```
- For user to search for the files, the user has to enter ```localhost:3000/searchfiles```
- For user to search about other OU's information, the user has to enter ```localhost:3000/SearchOU```
- For user to send document invitation, the user has to enter ```localhost:3000/docInvitation```
