# Git-Tutorial

# Installation
- Windows
  1. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/windows_download.png)  
  2. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_1.png)  
  3. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_2.png)  
  4. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_3.png)  
  5. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_4.png)  
  6. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_5.png)  
  7. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_6.png)  
  8. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_7.png)  
  9. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_8.png)  
  10. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_9.png)  
  11. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_10.png)  
  12. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_11.png)  
  13. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_12.png)  
  14. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_13.png)  
  15. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_14.png)  
  16. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_15.png)  
  17. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/git_setup_16.png)  
  - Set PATH
    1. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/set_path_1.png)  
    2. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/set_path_2.png)  
- Linux  
  $ sudo apt-get install git  
- Verification  
  $ git --version  

# Command Line in Windows  
Right-click in a target directory and click *Git Bash Here* to create a terminal.  
<br/>![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/cmdline.png)  
  
# Configuration
- Username  
  $ git config --global user.name \<username\>  
  ex : git config --global user.name HappyDog  
- Email  
  $ git config --global user.email \<email\>  
  ex : git config --global user.email happydog@gmail.com  
- Verification  
  $ git config --list  

# Repository Creation in Github
1. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/repo_1.png)  
2. ![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/repo_2.png)  
  
# Commands
- Clone a repository  
  $ git clone \<repo\>  
  1. Copy the source of a repository in github.  
  <br/>![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/clone_1.png)  
  2. Clone this repository via command.  
  <br/>![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/clone_2.png)  
- Push a revision to your repository  
  - Add revised files  
    $ git add \<file1\> \<file2\> ...  or git add . (. means all revised files)  
  - Commit this revision  
    $ git commit -m "\<your comment\>"  
  - Push this revision to your repository  
    $ git push  
  1. </br>![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/push_1.png)  
  2. </br>![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/push_2.png)  
  3. </br>![image](https://github.com/devildonkey1392/Git-Tutorial/blob/main/Pic/push_3.png)  
- Pull the latest version from the repository  
  If you are co-working, you must retrieve the latest version in your repository before you push a revision.  
  $ git pull  
