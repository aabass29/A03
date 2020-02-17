**_Tutorial on Git, Github & Webstorm_** - **For MacOS**

**_Git_** - https://git-scm.com/downloads

_**WebStorm**_ - https://www.jetbrains.com/student/ 


**_Step 1_**: Download the provided links we will use in the semester 

**_Step 2_**: Create Github account using your UCID and email

Github - https://github.com/join


**_Step 3_**: Once you have downloaded Git and Webstorm and created a Github account, open up Webstorm and press 
**Create New Project** (**Name your project A03**) and select **Empty Project**. A folder should be created that will 
have your matching files. (should display an  .idea folder)


**_Step 4_**: Click the file tab and select NEW -- select HTML file ---select HTML5. Name the HTML file **index**. 


**_Step 5_**: One you have created the matching files, we need to connect Webstorm to your Github account. Click on the 
Webstorm tab --- **select Preferences** --- **select Version Control** --- select **Git** --- **choose the location to 
the path** ---- click **Test** to make sure Webstorm is connected to Git. If Git is installed correctly, then  
“Git Executed Successfully” should appear. If  Git was not installed, download Git as described in Step 1 


**_Step 6_**: On Preferences, select **Appearance and Behavior** --- select **System Settings** --- select **Passwords**
--- add a location to the password file


**_Step 7_**: Go back to your project, Click the **VCS** tab -> scroll to **Import into Version Control** --- select 
**Create Git Repository**. Select the directory file we made (A03) and click **OK**


**_Step 8_**: Now we need to Commit to the changes to GIT, so select **VCS** --- select **Git** -> Click on the index 
and README files --- add a Commit comment ---- **press Commit** (Since its the first commit ever, a dialog box will open
to set the Git username and email. Use your NJIT email. Click Set --- then select Commit)
 
 
_**Step 9**_: Now we can add the project to Github, so select **VCS** tab --- select Import into Version Control --- 
select **Share Project on Github**. Input the repository name IS117AO3 and click share (A message should appear 
“Successfully shared project on GitHub”). The file should be posted on the internet


**_Step 10_**: On Github, we need to a new file to the GitHub Repository. So go to **Repositories** --- click **New** 
--- Name it **README.MD**. Add a comment and make the file public


**_Step 11_**: Go back on Webstorm and commit changes to Git. Once the changes have be committed, we need push the 
change to Github Remote Repository. To push the change to Github select **VCS** --- s**elect Git** ---- **select Push** 
(If a message appears to reject the push, click merge so the remote changes can push)


**_Step 12_**: The file should now be on Github. Now we need to set up the Github pages. On Github, Click **Settings** 
--- Check the repository name --- Choose GitHub Page Location --- Select **Master branch**


**_Step 13_**: You can check your Github pages, Copy the Github.io URL into any browser and should display code                                                






**_Definitions_**

GIT - An open source version control system

GITHUB - a Git repository hosting service, but it adds many of its own features. Provides a Web-based graphical 
interface 

Repository -  is like a folder for your project. Your project's repository contains all of your project's files and 
stores each file's revision history

Clone - a remote repository to your local machine. If you run into errors, there are some common troubleshooting 
solutions

Commit - used to save your changes to the local repository

Push - used to upload local repository content to a remote repository

Pull -  used to fetch and download content from a remote repository and immediately update the local repository to match 
that content

Branch - is a unique set of code changes with a unique name

Merge - takes the contents of a source branch and integrates them with a target branch.

Merge Conflict - happen when you merge branches that have competing commits,

Fetch - downloads commits, files, and refs from a remote repository into your local repo

Remote - downloads commits, files, and refs from a remote repository into your local repo

_**References**_

GitHub (2019) GitHub Guides Tutorial. Retrieved  March 19, 2019, 
    from https://guides.github.com/activities/hello-world/ 

Hendela, Arthur "Introduction to Github and Webstorm" Slides

Atlassian. “Learn Git with Bitbucket Cloud: Atlassian Git Tutorial.” Learn Git, Atlassian, 
    www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud.
