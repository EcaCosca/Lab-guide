<h1>
Github lab assignments guide
</h1>
<br>
In the repo that you are going to be working with let’s click on FORK
<img width="102" alt="Screen Shot 1443-02-27 at 5 03 23 PM" src="https://user-images.githubusercontent.com/63668672/135865423-d1f70715-f2e8-415f-9afb-8752049492f0.png">

<br>
Check name in the top left, it should be yours, after that go to Code > Copy URL

<br>
Open your Terminal and navigate to your homworks_labs folder inside of T1000 on your Desktop.

<br>
cd Desktop\T1000\homeworks_labs
<br>
Clone the github repo from the remote locacion you forked it from, into your computer.
<br>
git clone <paste url from the clipboard>

<br>
Navigate inside of the cloned folder
<br>
cd <name of cloned folder>
<br>
Open the project on VS CODE

  <br>
Change something in the project.

  <br>
Back in the terminal check the changes you have just made.
<br>
  git status
<br>
  Stage the changes you want to commit.
<br>
  git add .
<br>
  Commit the changes you added to your local repository.
<br>
  git commit -m “First Commit”
<br>
  Push your changes to you forked repository on github.
<br>
  git push origin main
<br>
  Back on github, let’s go to the project URL and do a pull request.
<br>
  Pull requests > New pull request 

<br>
Now add the title to be “[FS102021]  Your Name” > Leave a comment > Create Pull Request
