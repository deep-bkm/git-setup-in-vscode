# git-setup-in-vscode
Inital git setup in vscode

Installing Git in Visual Studio
Step 1: Download and install Visual Studio Code in your system using the official website. 

Step 2: Download and install git in your system using the official website. 

Step 3: After Installing, you can check if it is installed properly or not by typing the following command in the Command Prompt:

git –version

Step 3: Now create an account on GitHub.

Step 4: Configure your Git account with your GitHub. To do this Open Command Prompt and Type:

git config –global user.name “YourUserNameOnGithub”

git config –global user.email “YourEmail”

Here, replace YourUserNameOnGithub with your GitHub-username, and YourEmail with the email-id used while creating an account on GitHub.

Step 5: After configuring your details, you can check by using the command, your GitHub username and email will be displayed, this will make sure that your Git is linked with your GitHub:

git config –global –list

Enable Git in Visual Studio Code:

Step 6: Open Visual Studio Code

Step 7: Go to Settings in Visual Studio Code via File -> Preferences

Step 8: Now go to the Search Bar and type – “Git: Enabled”.

Step 9:  Now tick the CheckBox to Enable Git.

Now Git is Finally installed in your Visual Studio Code. You can view all Git changes in your Source Control Tab as shown in the below image:

##################
##################
##################

Clone and use a GitHub repository in Visual Studio Code

Open an integrated terminal from Terminal -> New Terminal.

Clone your repo with the following git command:

git clone https://github.com/YOUR-NAME-OR-ORGANIZATION/YOUR-REPO-NAME
Change your terminal into that new subdirectory:

cd YOUR-REPO-NAME
Then open in Visual Studio Code:

code .