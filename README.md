### Basic Git Installation
1. Install Git in Windows, go to Source Control
of VSCode and click Download Git for Windows

2. or go to this https://git-scm.com/download/win

3. select Windows either 32/64 bit depending on your System

4. follow the steps, mostly click Next by default 
except VSCode as the editor instead of Vim

5. Go back to VSCode Source Control Tab or Reload it, you 
can start clean by opening a new VSCode Window

6. Open Terminal, New Terminal

7. at the Terminal on the bottom right of your screen, 
select type of terminal, click Git Bash

![image](https://user-images.githubusercontent.com/47092464/234513151-9ecaf0f3-aa06-409a-8fff-3e52cd03fe42.png)


8. on your terminal `cd Desktop` or any other location 
you want/required by the project like `htdocs`, 
then clone a existing repo on GitHub `git clone "the remote repo`

9. open a New Folder on VSCode and select the one you just cloned

10. start editing, `git add .`, `git commit -m "message"`, `git push`

11. the first time you push, it will fail the authentication, 
go to VSCode Settings search for `git.terminalAuthentication` and uncheck the option

12. git push again, there will be a pop-up to authorize 
authenticating Git via your browser, make sure the active browser is logged in to GitHub

### GitHub Desktop
Once you learned Git basics, it's better to use GitHub Desktop, 
it's a Git UI version,  because you
can see exactly the files that have changed and those you will be 
committing and in actual development, mostly you will be using branches
to control the changes like you can sumbit a PR first

you may want to take a look at this

https://github.com/jdevstatic/my-github-desktop-commit-workflow

or simply use the basic Source Control of VSCode
