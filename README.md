# Jr Devs Meetup: Git Intro 

In the Terminal:

Download the repo.
```sh
git clone https://github.com/ejonelunas/Git-intro-Jr-Devs.git
cd Git-intro-Jr-Devs
```

Create or edit a file. Don't forget to save your changes! Here's a example of a possible change.
```sh
mkdir contributing-members
touch contributing-members/YOUR_USERNAME.txt
```
If you use this example update, replace `YOUR_USERNAME` with your username.

"Stage" your changes:
```sh
git add .
```

Examine the staging area. Does this look good to you?
```sh
git status
```

If the staging area looks good, commit your changes.
```sh
git commit -m "adding a member"
```

Can you upload your changes?

```sh
git push
```

No, you can't. Why? Because this repo doesn't allow unauthorized users to make changes. You need to ask the owner of the repo to accept your change (aka "make a pull request").

Link to your fork (aka copy) of the repo.

If you don't have one, you'll need to create a GitHub account, visit the original page (https://github.com/ejonelunas/Git-intro-Jr-Devs) and click on the `Fork` button in the upper right corner.

Once you have a copy of the repo in your own account, link it to the directory on your computer. Replace `YOUR_USERNAME` with your GitHub username.
```sh
git remote add fork https://github.com/YOUR_USERNAME/Git-intro-Jr-Devs.git
```


Upload your changes to your fork (your copy on GitHub).
```sh
git push fork
```

That works because your fork is yours, so you are authorized to make changes to it.

When you're done making and uploading your changes, visit your copy of the repo on GitHub (https://github.com/YOUR_USERNAME/Git-intro-Jr-Devs) and click on the `New pull request` button. 

Examine the summary of your changes. You are asking for changes you made to your _head fork_ to be added to the original author's  _base fork_. If those changes look correct, click on `Create pull request`. Write a little message explaining why you think this code will be useful to them.

The owner(s) of the repo will receive an email and a message on GitHub indicating that you have made a _pull request_ - a request that they pull your new code into their existing repository. There will be a dedicated page on GitHub where you can talk about the change (find it at https://github.com/ejonelunas/Git-intro-Jr-Devs/pulls). If the owner(s) accept the change, they'll _merge_ your code into theirs.
