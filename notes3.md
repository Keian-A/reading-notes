# Revisions and the Cloud

## Day 2 Class 1 notes

#### GitHub is a resource to save and backup saves of code to the cloud using git, with improvements of its own.

git and GitHub allow:
- Snapshots
    - These allow many changes to be saved so coders can always revert to a previous snapshot, or save.
- Local Operations
    - These allow many people to work on the same project at the same time from remote locations.
- Tracking Changes
    - This allows for ease of viewing of previous snapshots and what changes were made to each one.
- Loss of Data
    - This allows ease of mind in case of personal data corruption, or loss of data on one's system to be backed up through previous snapshots saved on GitHub.

## Terminal commands for git

#### 
- git clone "github_repository_link" -> will clone the contents of a GitHub repository onto your remote system.
- git add ". (or) file_name" -> will save your edited files and prepare them to get commited.
- git commit -m "message here" -> will get your files that are added to the commit and prepares a message which will display on GitHub to show changes.
- git push origin main -> will send the commited files to the main branch in your GitHub repository.
- git status -> you should constantly get in the habbit of using this after every git command to check the status of where you are at with [A-C-P](ACP.md).

[<-- Back](README.md)