This is package github of Shinyshell.

This package contains the following functions:


## deleterepo GITHUB_USER REPO_NAME :

Delete the repo REPO_NAME on the GitHub of user GITHUB_USER


## listrepos GITHUB_USER :

List the GitHub repositories of user GITHUB_USER


## new_package_on_github PACKAGE GITHUB_USER :



## newrepo GITHUB_USER GITHUB_REPO_NAME :

Create a new repo for user GITHUB_USER named GITHUB_REPO_NAME.
May be you want to run this after: 
set_remote_github ${GITHUB_REPO_NAME#shinyshell-} ${GITHUB_USER}  ${GITHUB_REPO_NAME}


## push_package PACKAGE GITHUB_USER :



## push_packages GITHUB_USER :

Each of your Shinyshell packages synchronized with a Github repo will be pushed
on Github.


## set_github_user  :



## set_remote_github PACKAGE GITHUB_USER GITHUB_REPO_NAME :

(Init and) set the remote github repo for a shinyshell package
Example:
set_remote_github sparql lolive shinyshell-sparql


## view_remote_github  :


