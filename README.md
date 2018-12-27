# Package "Shinyshell-github":

This package contains the following functions:

<pre>

## deleterepo GITHUB_USER REPO_NAME :

Delete a repo on GitHub

Delete the repo REPO_NAME on the GitHub of user GITHUB_USER

</pre>
<pre>

## listrepos GITHUB_USER :

List your repositories on GitHub

List the GitHub repositories of user GITHUB_USER

</pre>
<pre>

## new_package_on_github PACKAGE GITHUB_USER :


</pre>
<pre>

## newrepo GITHUB_USER GITHUB_REPO_NAME :

Create a repo on Github

Create a new repo for user GITHUB_USER named GITHUB_REPO_NAME.
May be you want to run this after: 
set_remote_github ${GITHUB_REPO_NAME#shinyshell-} ${GITHUB_USER}  ${GITHUB_REPO_NAME}

</pre>
<pre>

## push_package PACKAGE GITHUB_USER :


</pre>
<pre>

## push_packages GITHUB_USER :

Push all your Shinyshell packages on Github

Each of your Shinyshell packages synchronized with a Github repo will be pushed
on Github.

</pre>
<pre>

## set_github_user  :


</pre>
<pre>

## set_remote_github PACKAGE GITHUB_USER GITHUB_REPO_NAME :

(Init and) set the remote github repo for a shinyshell package

(Init and) set the remote github repo for a shinyshell package
Example:
set_remote_github sparql lolive shinyshell-sparql

</pre>
<pre>

## view_remote_github  :


</pre>
