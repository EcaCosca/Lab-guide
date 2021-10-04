Github lab assignments guide

The repo that you are going to be working with let’s click on FORK

Check name in the top left, it should be yours, after that go to Code > Copy URL

Open your Terminal and navigate to your homworks_labs folder inside of T1000 on your Desktop.

cd Desktop\T1000\homeworks_labs
Clone the github repo from the remote locacion you forked it from, into your computer.
git clone <paste url from the clipboard>

Navigate inside of the cloned folder
cd <name of cloned folder>
Open the project on VS CODE

Change something in the project.

Back in the terminal check the changes you have just made.
git status
Stage the changes you want to commit.
git add .
Commit the changes you added to your local repository.
git commit -m “First Commit”
Push your changes to you forked repository on github.
git push origin main
Back on github, let’s go to the project URL and do a pull request.
Pull requests > New pull request 


Now add the title to be “[FS102021]  Your Name” > Leave a comment > Create Pull Request
