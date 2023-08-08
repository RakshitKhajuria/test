# How to Contribute

We welcome contributions from the community to help us achieve our mission of making safe and reliable NLP models a reality. If you're interested in contributing, follow the steps below:

## Step 1: Finding an Issue

1. Visit our [Issue Tracker](https://github.com/YourUsername/LangTest/issues) to find a list of open issues.
2. Look for issues that align with your skills and interests. Feel free to ask for clarification or more information on any issue.

## Step 2: Contribution Process

<img align="right" width="300" src="https://github.com/RakshitKhajuria/first-contributions/assets/71117423/be22d54d-5b62-4a23-b213-0268ed195021" alt="fork this repository" />

### Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

### Clone the repository

<img align="right" width="300" src="https://github.com/RakshitKhajuria/test/assets/71117423/b07c7d60-ab80-4b7f-b972-58fcd1f50741" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://github.com/RakshitKhajuria/test/assets/71117423/8eef9f61-283d-4bad-9e7f-8a526e33615e" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/username/langtest.git
```

where `username` is your GitHub username.

### Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd langtest
```

Now create a branch using the `git checkout -b` command:

```
git checkout -b your-branch-name
```

### Make necessary changes and commit those changes 

Add those changes to the branch you just created using the `git add` command:

```
git add .
```
Now commit those changes using the `git commit` command:

```
git commit -m "Add feature XYZ" 
```

### Push changes to GitHub

Push your changes using the command `git push`:

```
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.



## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://github.com/RakshitKhajuria/test/assets/71117423/86cb56af-1dad-467e-afc1-f4594615783b" alt="create a pull request" />

Before submitting the pull request make sure to add description and type of change you've just added. For pull request template click [here](https://github.com/JohnSnowLabs/langtest/blob/main/PULL_REQUEST_TEMPLATE.md)

<img style="float: right;" src="https://github.com/RakshitKhajuria/test/assets/71117423/5c629508-53a7-4444-b036-15f694df675c" alt="submit pull request" />

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

## Where to go from here?

Congrats! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll often encounter as a contributor!

Celebrate your contribution and share it with your friends and followers by going to [web app](https://firstcontributions.github.io/#social-share).

You could join our slack team if you need any help or have any questions. [Join slack team](https://join.slack.com/t/firstcontributors/shared_invite/zt-1n4y7xnk0-DnLVTaN6U9xLU79H5Hi62w).
