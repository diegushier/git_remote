# git_remote
This is a quick script for using git for those who cannot access git from they local servers due to the token security.

The installer script located in the ```installer``` folder creates the script in the main folder.

A second folder ```var``` is also created and there, there is a file ```.env``` where you need to save your user and git token.

When the installation is complete, the only thing that lefts is use the script ```./git_remote``` and the repository you want to use.

Your credentials will be stored in the git system and you will have cloned your repo. 

The script can be changed in order to use **fetch** **push** or **pull**.

<h3> UPDATE </h3>

In order to make life easier, the caller script for installing is ```installer_script```.
