# Ropes Project - Where we show you the ropes of working with Rails

The Ropes Project is a repository that has everything you'll need to get started developing your onboarding Rails app. By the end, you'll have a full app deployed to Heroku that allows people to add images and share links to them with friends. Along the way you'll learn the basics of working with ERB templates, CSS, and Javascript as well as testing best practices.

## Project Goal

The goal of the project is for you to develop confidence in building a modern ruby-on-rails application while learning and demonstrating our best development practices. You may find the tasks to be relatively straightforward, however, we want to stress the best practices which means that you may spend a significant amount of time addressing comments made by code reviewers after you've "finished" a task.

## Project Workflow

Your overall workflow will make use of a few Github features. Don't worry if you aren't familiar with some of them, we'll go into detail below.

Each feature will be linked to a Github Issue. As you work your way towards merging that feature you'll be updating the issue with the appropriate Github Label. When you are ready to merge you will open a Github Pull Request and request a code review from whomever is assigned to that Issue. Once they've given it a green light you can merge it into your master branch. If you have other outstanding branches don't forget to rebase!

### Github Issues

We've broken up this project into a series of Github Issues. If you aren't familiar with them, think of them as stories. Each one encapsulates some bit of value being delivered. These issues can be found in the "Issues" section of your repository. The issue list view will look something like the following:

![Example list of issues](https://github.com/AppFolioOnboarding/base/blob/master/readme/issues.png)

Issues are to be worked on in their issue number order from low to high. This order was established to minimize dependency conflict as you progress through the issues. An exception is when an Academy session necessitates starting an issue early.

Only a single issue should be “in progress” at a time (see labels below). If issue #3 is “in progress”, and then there is a session which requires you to start issue #6, change issue number #3’s label to “waiting on developer”.

The in progress issue should always be the issue with the lowest number that's not "waiting on reviewer".

[![Dependencies](https://raw.githubusercontent.com/AppFolioOnboarding/tasks/master/dependencies.png)](https://github.com/AppFolioOnboarding/tasks)

### Github Labels

In order to keep track of where you are on an issue we use the Github Labels feature. We have six **core labels**. These labels are designed to help keep track of which step in the development/merging process that your issue is in. It should only have one of these at a time, since each of them represents a specific state that the issue is in, and a single issue can't be in two states at once.

The **core labels** are as follows:

![List of core labels](https://github.com/AppFolioOnboarding/base/blob/master/readme/core_labels.png)

We've also created an additional label that can be added if your PR needs to get merged before it's been code-reviewed. This is hopefully a rare case, but it is nice to know when it happens so that someone can sync up with you later about any feedback there might be for that branch. The extra issue is as follows:

![List of additional labels](https://github.com/AppFolioOnboarding/base/blob/master/readme/extra_label.png)

### Github Pull Requests

A pull request should be made whenever you are at a point where one of the following is true:
* You would like to test your work on heroku via a review app.
* You would like feedback on part of your code.
* You are satisfied that your work addresses the acceptance criteria of the corresponding issue.

When you make a pull request be sure to:
* Make reference to the corresponding issue
* Assign the pull request to the same assignee on the issue
* Set the issue label to "pull request"
* Set the appropriate label on the pull request

# Additional Resources

There's more to onboarding at AppFolio than just learning Rails, Javascript, and CSS. We've put together a list of great resources to help you learn more about the technologies we use, the Slack channels we live in, and the places we hang out in Santa Barbara and San Diego.

For all of that and more please check out our [Wiki](https://sites.google.com/a/appfolio.com/eng)!
