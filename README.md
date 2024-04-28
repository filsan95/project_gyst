# GIT: Adding a file

**To add a file: (locally via cloning repo)**
<ol>1. (Terminal) See current directory (pwd), and change directory (cd) to file you want to clone repo to (use ls to see list of files)</ol>
<ol>2. (Terminal) git clone &lt;insert https&gt; — copy https link from the repository on web version of Github</ol>

```shell
# Your shell commands here
git clone <insert https>
ls -l

<ol>3. (Terminal) cd &lt;insert repo filename&gt; - change directories  again and go to the repository (this can be found on ls)</ol>
<ol>4. (Terminal - Nano/ Vim) Create or Edit a file (ie. nano filename.extention) - the nano editor will open up and you can add contents you wish to add to your repo</ol>
<ol>5. OR (IDE) Create a file using VS Code or ATOM and save to clone repo file on computer</ol>
<ol> 6. (Terminal) git add . — this adds all the changes made to the repo </ol>
<ol>7. (Terminal) git status — will show the changes made (added files)</ol>
<ol> 8. (Terminal) git commit -m “&lt;insert update message&gt;”</ol>
<ol> 9. (Terminal) git remote -v </ol>
<ol>10. (Terminal) git push origin main — origin main is the default, then enter username and personal access token </ol>
