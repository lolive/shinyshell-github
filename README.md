# Package "Shinyshell-github":

This package contains the following functions:


## deleterepo GITHUB_USER REPO_NAME :

<pre>
Delete a repo on GitHub

Delete the repo REPO_NAME on the GitHub of user GITHUB_USER
</pre>


## listrepos GITHUB_USER :

<pre>
List your repositories on GitHub

List the GitHub repositories of user GITHUB_USER
</pre>


## new_package_on_github PACKAGE GITHUB_USER :

<pre>
</pre>


## newrepo GITHUB_USER GITHUB_REPO_NAME :

<pre>
Create a repo on Github

Create a new repo for user GITHUB_USER named GITHUB_REPO_NAME.
May be you want to run this after: 
set_remote_github ${GITHUB_REPO_NAME#shinyshell-} ${GITHUB_USER}  ${GITHUB_REPO_NAME}
</pre>


## push_package PACKAGE GITHUB_USER :

<pre>
</pre>


## push_packages GITHUB_USER :

<pre>
Push all your Shinyshell packages on Github

Each of your Shinyshell packages synchronized with a Github repo will be pushed
on Github.
</pre>


## set_github_user  :

<pre>
</pre>


## set_remote_github PACKAGE GITHUB_USER GITHUB_REPO_NAME :

<pre>
(Init and) set the remote github repo for a shinyshell package

(Init and) set the remote github repo for a shinyshell package
Example:
set_remote_github sparql lolive shinyshell-sparql
</pre>


## view_remote_github  :

<pre>
</pre>

