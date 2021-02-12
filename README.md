# GitHub Quickstart
## Video Walkthrough
<a href="https://drive.google.com/file/d/1W5bZrGmuDORsmtCzD08Vwx31hw8Ab3nu/view?usp=sharing">Watch</a>
## Clone Repository
To work on this project, you need to first clone the repo to your local machine. Open a terminal window (Git Bash, DOS prompt, Terminal, Cmder) and change directory to the place where you would like to store the project files. Paste the command below to clone the project files to that location.
```
git clone https://github.com/dgitts/predict-customer-churn.git
```
## Create & switch to your branch
Create your own branch using the command below. You only need to create your branch once.
```
git checkout -b notebooks/oscar
```
This will create and switch you to your own branch. Replace 'oscar' with your own name.
## Working on your branch
Create your notebook(s) in Jupyter Notebook and save them to your name folder. For example if Oscar creates a notebook called data_cleaning.ipynb the file should be saved in oscar's folder in the project files.
```
/predict-customer-churn/notebooks/oscar/data_cleaning.ipynb
```
Once you finish a minor or major feature that you want to share with your team, please commit your changes to the repo and push them.
Go to terminal window and change to the project directory. Use the status command to confirm what changes have been made to your branch.
```
git status
```
If you are ok with the changes, add all your changes then commit them using the following commands.
```
git add .
git commit -m "added data cleaning"
```
Use a short descriptive message for your updates, above we described this commit as "added data cleaning".
Next, pull down any updates to your branch from GitHub
```
git pull origin notebooks/oscar
```
Then push your changes up to GitHub
```
git push --set-upstream origin notebooks/oscar
```
And that's it!
