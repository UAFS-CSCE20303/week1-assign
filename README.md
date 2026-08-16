## CSCE 20303: Web Systems - Week 1 Assignment

**Objective:** The purpose of this assignment is to introduce the Git protocol and GitHub. Git is a source code versioning software that is used by developers and software teams to manage code bases, test, and deploy code.

For this assignment:

### Copying a Repository on GitHub and to your local VM

**Fork** the assignment to your GitHub account. This will make a copy of the repository in your account where you have permissions to add and modify the repository (repo).

**Clone** your new repo to your local drive in your VM. Press the **green CODE button** on the Repo's page and make sure **SSH** is highlighted for the protocol and copy the URL.

**Clone the Repo** In your VM, open the terminal change to the projects directory _cd projects_ and use the the following command:

```
git clone <Paste Your Repo URL>
```

This will copy your repo to your local VM. Type _'ls -l'_ to list all of the files in the directory and you should see a directory with the name of your repo. Change to that directory using _'cd theName'_. If you type _'ls -l'_ again, you should see all of the files in your repo. (README.md, home.html)

Modify the HTML file(home.html) to display your name in between the <h2> tags. After making the change and saving it. Open Chrome and click on the Index link to list the files in your project directory and select home.html in the week1-assign directory.

### Update your Local Repository and Push your changes to GitHub

Git maintains a local repository in each repo folder on your local machine and the remote copy on GitHub.
Type the following commands to save your changes to your local repo and push the changes to GitHub.

```
git add *
git commit -m "Updated"
git push origin main
```

This will update your local repo and synchronize the changes to Github. If you refresh your Github repo page you should see the changes.
