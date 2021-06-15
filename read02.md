# What is Git? 
---  
* ### Snapshots

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.
* ### Local Operations

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

* ### Tracking Changes

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

* ### Loss of Data

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

* ### States 
Files in Git can reside in three main states: committed, modified and staged.

1. #### Committed
Data is securely stored in a local database



2. #### Modified
File has been changed but not committed to the database


3. #### Staged
Flagged a file’s changed version to be committed in the next snapshot 

---

### Git can be installed in three ways:

* Install as a package
* Install via another installer
* Download and compile the source code


### Initial Customization 
After making sure Git has been installed, you should perform some customization steps, which should only need to be completed once on any machine. To change settings, you can repeat these steps.

* #### Configuration of Variables  
 An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.
 * ### Identity Setting  
 After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.


Type the following into Terminal or Command Line:

---
***git config --global user.name "Jane Smith"***

***git config --global user.email "example@email.com"*** 

---
To confirm that you have the correct settings, enter the following command:
---   
***git config --global user.name (should return Jane Smith)***

***git config --global user.email (should return example@email.com)***  

---

## Setting up a Git Repository

### Importing

To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

1. Switch to the target project’s directory

Example: 
--- 
***$ cd test (cd = change directory)***

---
2. Use the git init command  
***$ git init***

3. To start tracking these repository files, perform an initial commit by typing the following:

---
***$ git add *.c***  
***$ git add LICENSE***  
***$ git commit -m “any message here”***  

----

















