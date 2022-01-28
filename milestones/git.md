## Milestone: GITHUB

_This Milestone will allow you to start working with Git and Github_

- Go to the Github webpage
- Create your account if you don't have one, you can use your SciLifeLab email.
- Login into your account
- Add a picture to your profile
- Find a way to create a new repository ("repo" for short)
- In the repository name, you can use the same as your username plus ".github.io"
    For example: my username is `USERNAME`, then my repo will be called "`USERNAME`.github.io"
- Add a description "this is my personal repository"
- Leave it to "public"
- Add a readme
- Add gitignore (look for the programing language you would like to use, R or Python)
- Add a MIT license
- Look at the files present in your repository, what are they?
- Which file is displayed in the main page of your repository?

***

## Milestone: WEBPAGE

_This Milestone will allow you visualise your work and progress in PBL_

_Depends: GITHUB_

- Go ot your "USERNAME.github.io" repository
- Look for the button "Settings"
- In "Pages", select the theme "Slate" (for consistency in the exercises)
- In the next page, scroll down and click on "Commit changes".
- Open a new tab on your browser and type "USERNAME.github.io", this is your new website.
- Which file is being displayed in the main page?
- Which language is used to style the text displayed in the webpage?
- Go to your repository main page and open it in 2 windows side-by-side. In one of them, click in "edit". There you'll see some basics styling tips.
- How do you make headers?
- How do you make text bold?
- How do you add inline code?
- How do you add links?
- How do you add images?

***

## Milestone: GIT

_This Milestone will allow you start working locally with git_

_Depends: WEBPAGE, UNIX_


- Open a terminal/MobaXterm on your computer.
- Go to your home directory using `cd`
- Create a directory named "repos" with `mkdir`
- Go inside the "repos" directory with `cd`
- type `git config --global user.name "USERNAME"``
- type `git config --global user.email "USERNAME@EMAIL.COM"``

- On the browser, go to your own repository main page on Github.
- On the top right corner click on your profile and then in "Settings"
- Then click on "Developer settings" on the left menu.
- Then click on "Personal access tokens" and "Generate new token".
- Add a note like "Personal Computer", and change the expiration date to "no expiration".
- Click in all check-boxes and then "Generate token"
- Copy the token
- Back to terminal, type `git config --global user.password "TOKEN"``

- On the browser, go to your own repository main page on Github.
- Click on the button "Code" and then copy the HTTPS link
- Back to your terminal, type `git clone ` and paste the link copied. Should look like this:
    `git clone https://github.com/USERNAME/USERNAME.github.io.git`

***
