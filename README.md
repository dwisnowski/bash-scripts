intellij-live-templates
===

A collection of useful IntelliJ live templates to enable deft UI development.



## IntelliJ settings
1. In Intellij click File>import settings and select the settings jar in this project.
	-- Do this once for each of the settings jars you wish to import.
		--- at the time of writing this, there are 3 (templates, keymaps, pomodoro)
2. Choose what you want.
3. Your done!

#### Usage
1. please view the live templates inside intellij as these change often and would be more work to document here.


## Bash Scripts - The Easy way to install all scripts into your bash shell:
1. Paste the following into your ~/.bashrc or ~/.bash_profile:
	source /c/bench/intellij-live-templates/master_script.txt
2. Restart your console.
3. Your done!

#### Usage
1. This was the installations of all the bash scripts found below.  For usage, please read further into the specific script you are attempting to use.




## Bash Aliases
1. Paste 'source /c/bench/intellij-live-templates/master_script.txt' into your ~/.bashrc or ~/.bash_profile.
2. Restart your console.
3. Your done!

#### Usage
1. Please open up this file to see all the alias you now have at your disposal.





## Update script - for updating from github
1. Paste 'source /c/bench/intellij-live-templates/master_script.txt' into your bashrc or Copy the contents of the update_script.txt into your ~/.bashrc or ~/.bash_profile.
2. Restart your console.
3. Your done!

### Usage
1. On the commandline enter 'update' inside the folder that has your git project.
Note: This command was designed to update based on whether your project has an origin or upstream and will follow the appropriate location.




## Bump it up script - for npm bumping a module.
1. Paste 'source /c/bench/intellij-live-templates/master_script.txt' into your bashrc or Copy the contents of the bumpitup_script.txt into your ~/.bashrc or ~/.bash_profile.
2. Restart your console.
3. Your done!

### Usage
1. On the commandline enter 'bumpitup' inside the folder that has your git project.
Note: This command was designed to unlink all deps, update master, prune git and npm, and finally bump the repo.





## Die Branches Die - script for pruning old branches from your repo.
1. Paste 'source /c/bench/intellij-live-templates/master_script.txt' into your bashrc or Copy the contents of the diebranchesdie_script.txt into your ~/.bashrc or ~/.bash_profile.
2. Restart your console.
3. Your done!

#### Usage
1. On the commandline enter 'diebranchesdie' inside the folder that has your git project.
Note: This command was designed to prune all branches that are not tracked on origin.  At the moment this command will kill all local branches that have work in them if their is no branch on origin, so becareful.  An update will come out for this one to fix the problem in the near future.




## Linkem and Unlinkem - scripts for npm linking app-ui-server based projects.
1. Paste 'source /c/bench/intellij-live-templates/master_script.txt' into your bashrc or Copy the contents of the linkem_scripts.txt into your ~/.bashrc or ~/.bash_profile.
2. Restart your console.
3. Your done!


#### Usage
1. On the commandline enter 'linkem <projectnamehere>' from anywhere.
Note: This command was designed link projects that follow the app-ui-server project setups. For example, I have a project called scout that has the following folders/repos/projects associated with it: scout-app, scout-ui-core, scout-server-core.  This command will link, babel, and webpack in the right order and right locations automatically.  The script then tells you how to start the project and unlink the project if needed.  So on the commandline I would enter 'linkem scout' to run this funciton.

2. On the commandline enter 'unlinkem <projectnamehere>' from anywhere.  (i.e. 'unlinkem scout')

3. Please make sure that you use /c/bench for your projects and that the folder names for the projects remain unchanged for these scripts to work !!!!!!!!!

