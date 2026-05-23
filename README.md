# ysons
Hosting the Website

Learning how to commit in git via vscode.!


## About GIT

yadav@Legion2025 MINGW64 /d/GIT/ysons/ysons (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

yadav@Legion2025 MINGW64 /d/GIT/ysons/ysons (main)
$ git init
Reinitialized existing Git repository in D:/GIT/ysons/ysons/.git/

yadav@Legion2025 MINGW64 /d/GIT/ysons/ysons (main)
$ git add .

yadav@Legion2025 MINGW64 /d/GIT/ysons/ysons (main)
$ git add README.md

yadav@Legion2025 MINGW64 /d/GIT/ysons/ysons (main)
$ git commit -m "Updating ReadMe.md for git commands"
[main 21c72bc] Updating ReadMe.md for git commands
 1 file changed, 28 insertions(+)


## Contact Form Setup

The contact form now works! To receive emails at info@ysons.in:

1. Go to [formspree.io](https://formspree.io) and create a free account
2. Create a new form and set the recipient email: `info@ysons.in`
3. Copy your unique Form ID from the dashboard
4. Replace `https://formspree.io/f/mquqkjqz` in `contact.html` with your Form ID URL

Alternatively, use Formspree's free form to start receiving emails immediately.

## Git Commands

%to set up the repository
1. download gitbash
2. go to a folder and do git clone https://github.com/sharatry/ysons.git
3. Open Directoy in vscode
4. In vscode change the terminal to use git bash

%To push any change
1. do git add . --> locates all files with changes in the dir.
2. stage a change: git commit -m "Meaningful comment related to the change"
3. git push --> push the change to main branch: it will ask for authenitcation if already not done
%To pull the content in vscode

 git pull .