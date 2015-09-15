#Git & GitHub

## Due: Sept. 25, 2015, 3 p.m.

The purpose of this exercise is to see that you can work with files using git and getting them GitHub. It is also designed to get you prepared to submit your first project.

By now you should have GitHub Desktop installed on your computer and registered for a GitHub account.

Before you begin this exercise, make sure you have done the following:

- Set up your profile so your name appears.
- Validate your email address with GitHub.

If you fail to complete the first task listed above, I will not know who submitted the tasks below and **you will receive a zero (0)**. If you do not complete the latter, your web page will not work and **you will receive a zero (0)**. (And you will *still* have to do this all over again to submit the first project.)

**SUGGESTION:** If you can follow instructions (and being at a top university, you *should* be able to), this should be an easy assignment. Print out this page and mark off each step as you finish it. This will provide you with an assurance that you have completed what is being asked of you.


### Grading

This assignment is due **Sept. 25, 2015 at 3 p.m.** If it is submitted at Sept. 25, 2015 at 3:00:01 p.m., it will be deemed late. Two (2)
points will be deducted for each day the assignment is late.

Each section of this exercise is worth five (5) points. Failure to complete the section(s) as instructed will result in a zero (0).

If you are concerned about the *content* being submitted, please don't hesitate to view examples I have provided in my account. These provide an example of a correctly submitted assignment. (But remember, do not copy and paste the code and/or content; that's forbidden and will be deemed plagiarism.)

- [git-and-github](https://github.com/thegeekprof/git-and-github)
- thegeekprof.github.io: [repo](https://github.com/thegeekprof/thegeekprof.github.io), [site](http://thegeekprof.github.io)


### What is Git?

**Git** is version control software. It tracks every change you make to a file. Using git while doing web design is helpful because it forces you break down the process into manageable steps and group changes to code logically. When you make a mistake, you can 'roll back' to the last step when you know everything worked.

**GitHub** is a web site where people can store open-source code for free. An even better feature is GitHub can serve as a web host for simple,  static web sites, which is what we create for this class.

We will demonstrate how you can incorporate git into your workflow in a later class. For now, become familiar with the basic process of committing changes and pushing them to GitHub.

If terminology seems confusing, please refer to the [GitHub Glossary](https://help.github.com/articles/github-glossary/). Important terms are also linked throughout these instructions. You may also want to consult GitHub's extensive [help](https://help.github.com/) section and GitHub Desktop's [user guides and FAQ](https://help.github.com/desktop/).


## Part I: Get to know Git &amp; GitHub (5 points)

1. In the top right corner of this page, click '[Fork](https://help.github.com/articles/github-glossary/#fork)'. This will create a copy of the `git-and-github` [repository](https://help.github.com/articles/github-glossary/#repository) in your GitHub account.

   After GitHub redirects you to the forked copy, you should see: `username/git-and-github` (where username is *your* username) and a message below which says "forked from `umiami-web-design/git-and-github`".

2. Now we need to [clone](https://help.github.com/articles/github-glossary/#clone) this forked repository. Click the button in the right column which says "Clone in Desktop." This will start the process to save the repository to your computer. (If you receive an alert message, "External Protocol Request," this is okay. Click "Launch Application.") When GitHub Desktop appears and prompts you "Clone", do so. Make sure you note *where* you are saving this repository on your computer.

3. To access the repository, you may either navigate through the directories on your computer or right-click (ctrl-click) on the `git-and-github` repository in GitHub Desktop and choose "Open in Finder". Open the included `q-and-a.txt` file and answer the questions. Save `q-and-a.txt`.

 Return to GitHub Desktop. You should see a note at the top which reads: "1 uncommitted change". The panel just right of the left column shows which files have changed, in this case, `q-and-a.txt` with a checkbox next to it.

 The panel on the right side of GitHub Desktop shows you the changes made to `q-and-a.txt`. When you add to a file, GitHub desktop displays theses changes in green; when you delete, changes are shown in pink.

4. Below the list of files changed, fill in the "summary" field. It can be something simple such as, "Answered questions."

  Always make your commit summary descriptive. ("Made a change" isn't very helpful to someone picking up your writing, code, etc.) The "description" field is optional, but can be used to provide more detail if necessary.

  If everything is set -- the answers in your file are correct, the summary is descriptive -- click "Commit to master." This locks the changes in place.

5. At this point, you could make more changes to files, commit them, make more changes and commit them... or, you can [push](https://help.github.com/articles/github-glossary/#push) the committed changes to GitHub. Click "Sync" in the top right corner. (If you receive a message to allow your computer access to a keychain, this is okay. Click "Allow".)

6. Return to your web browser and view the `git-and-github` repository you forked into your own GitHub account. (This may still be displayed in your browser; if so, just refresh the page.) You should see the `q-and-a.txt` file has been updated. If you select it, you will see the changes.

7. In the `username/git-and-github` repository, above the file listing a similar message should be present: "This branch is 1 commit ahead of umiami-web-design:master." This means you have made a change which has not yet been picked up by the (my) master `git-and-github` repository you made a fork of.

  Click the link next to the message which reads "[Pull Request](https://help.github.com/articles/github-glossary/#pull-request)". This will take you a page which allows you to compare your updated/changed version with the master version. If everything appears correctly -- again, the answers in your file are correct, the summary is descriptive -- click "Create pull request." (You may be prompted to modify your commit message; simply click "Create pull request" again.)

8. Notice you have been re-directed to the `umiami-web-design/git-and-github` repository. If you click on the pull request icon in the right column, you should see a list of pull requests, including your own.

  This means you have successfully submitted Part I of this exercise!


### Part II: Set up your web site (5 points)

1. On GitHub, create a new repository. Name it *username.github.io* where username is *your* GitHub username. Type the username exactly as it appears as GitHub is case sensitive. Click the checkbox next to 'Initialize this repository with a README'.

2. Click 'Set up in Desktop'. When prompted to clone the repository, make sure "Clone As:" is *username.github.io* (again, where username is *your* username). Make note of the directory you are saving this cloned repo in. You will need to know this later.

3. Access the cloned repository on your computer. Open the directory (or README file) to Atom. This should get you set up to work in the correct directory.

4. Create a simple web page and save it as `index.html`. Remember to include all parts of a proper web page: `doctype`, `html`, `head`, `meta`, `title` and `body` tags.

  Add an `h1` tag with your name and a `p` tag with a short introduction, something like "Hi, this is my web page." It does not need to be complex.

5. Remember the `octocat.png` file from the `git-and-github` repository? Move this file from the `git-and-github` directory into the `username.github.io` directory on your computer.

  Add the `octocat.png` to `index.html` using an `img` tag. (Don't forget the `alt` attribute!)

6. As you did in the first part of this exercise, commit the changes through GitHub Desktop. You should be committing two files: `index.html` and `octocat.png`. The application should recognize there are "uncommitted changes". Provide a summary for the changes. Click "Commit to master". Then push the changes to GitHub by clicking "Sync".

7. Return to your web browser and view your username.github.io repository. The files should appear.

8. Open your web browser and visit `http://username.github.io` (again, where username is *your* username). Your simple web page should appear.


**That's it!**
