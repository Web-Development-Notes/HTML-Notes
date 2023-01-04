# Contributions

This project aims to simplify and guide the way developers to get help when they have skipped some syntax from their heads or need 
assistance about how to tackle a specfic thing in HTML.

If you are looking to make your contribution in helping the world and be useful for others, follow the steps below.

_If you're not comfortable with command line, [here are tutorials using GUI tools.](#tutorials-using-other-tools)_


<img align="right" width="300" src="https://i.imgur.com/AtePuVR.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://docs.github.com/en/get-started/quickstart/set-up-git).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://i.imgur.com/7SvJGgj.png" alt="Clone this repository"/>

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://i.imgur.com/3rbSU2Y.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/Web-Development-Notes/HTML-Notes.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd HTML-Notes
```

Now create a branch using the `git switch` command:

```
git switch -c your-new-branch-name
```

For example:

```
git switch -c add-table
```

## Add information which you feel is missing in HTML-Notes repository and commit those changes


Now make a separate folder for adding any new information which you want to share with developers.

For example if you want to add something about tables then make a folder named `Table` then in this folder you will be making a `table.html` in which you will be adding all about you want to share.

### You should include:
- Code for how to do that thing
- Comments for explaning the different code pieces


If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add all those changes to the branch you just created using the `git add` command:

```
git add -A
```
Now commit those changes using the `git commit` command:

```
git commit -m "Brief description of your changes"
```


## Push changes to GitHub

Push your changes using the command `git push`:

```
git push -u origin your-branch-name
```

replacing `your-branch-name` with the name of the branch you created earlier.


## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

Soon I'll be merging all your changes into the main branch of this project. You will get a notification email once the changes have been merged.

## License
[MIT License](LICENSE)
