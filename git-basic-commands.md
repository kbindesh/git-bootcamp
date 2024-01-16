# Git Commands

## Pre-requisites
   - Git must be installed on your system.

## Configure Git
   - First in order to check if the Git is properly installed, open the command prompt/shell and execute below command:
     ```
     git --version

     # Above command should give you current installed version of the Git; something like this
     git version 2.41.0.windows.3
     
     ```
          
   - To configure Git, you must define some global variables: `user.name` and `user.email`. Both are required for you to make commits.
   - Set the `user.name` configuration variable with the below command:
     ```
     git config --global user.name "<USER_NAME>"

     # Replace <USER_NAME> with the user name you want to use.

     ```
     
   - Now, set the `user.email` configuration variable with the below command:
     ```
     git config --global user.email "<USER_EMAIL>"
     
     # Replace <USER_EMAIL> with your e-mail address
     ```
   
   - You may run the following command to check that your name and email info are saved:
     ```
     git config --list

     or

     git config -l

     # You must see user.name and user.email variables updated with your details
     ```
## Setup your Git Repository

## Get help from Git

## Git Basic Commands
