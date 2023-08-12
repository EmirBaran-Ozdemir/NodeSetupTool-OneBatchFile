# NodeSetupTool-OneBatchFile
Tired of the repetitive process of setting up Node.js projects? Look no further! Introducing a powerful tool designed to simplify your Node.js project setup.  

## What does this script do

This batch script is designed to automate the process of updating a Git repository and installing its dependencies across multiple directories containing package.json files. It's particularly useful when you have a project with multiple subdirectories, each potentially containing Node.js projects, and you want to update the repository and install the required packages efficiently.
  
## How to use
Just download the batch file and put it and your project folder side by side into the same directory. Here is an [example project].  


## Note
 - Make sure you have Git and Node.js (with npm) installed and available in your system's PATH.
 - This script assumes that the repositories use the origin remote. If you don't want to stick with the origin remote you can change the 
```bat
for /f "delims=" %%i in ('git config --get remote.origin.url') do set "repo_url=%%i"
```
line with your remote repo link (remote.<your_remote_name>.url).

[example project]:<https://github.com/furkan-karadag/TasteMuseum/>
