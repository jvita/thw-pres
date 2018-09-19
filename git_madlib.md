Git basics + version control organization
=========================================
A short activity filling out a Mad Lib using Git

## Installation
__Option 1:__ Download [here](https://git-scm.com/downloads) directly from Git

__Option 2:__ Use ```sudo apt-get install git``` (Ubuntu)

Once you've finished installing, you should also [make an account](https://github.com) on Github.

## What is Git good for?

__Version control__

![organization](https://user-images.githubusercontent.com/15058514/45724076-15be5700-bb7a-11e8-958b-7b6f87aebcdf.png)

__Collaborative development__

![collab](https://user-images.githubusercontent.com/15058514/45724078-17881a80-bb7a-11e8-8d17-586ce919980d.png)

__Dumping your code to the cloud so that you can work from home__

![comic](https://user-images.githubusercontent.com/15058514/45724005-d0018e80-bb79-11e8-902d-9ab3d8dcc8ec.png)

## The basics
For the independent researcher, __sometimes just learning a few basic commands is sufficient for what you need to do__. In general, especially if you're doing large-scale software development, __you should also be aware of some good practices__ when it comes to __organization__ of your repository and how to best take advantage of Git for __collaboration__. Today we will simply cover some of the key functions, but there is also a great blog post [here](https://nvie.com/posts/a-successful-git-branching-model/) by Vincent Driessen discussing some organizational and branch management tips.

Note that since we already have [a nice tutorial](https://github.com/thehackerwithin/illinois/blob/master/git.md) by Aaron that has an example working with a forked repository, today's tutorial will instead attempt to simulate the experience of a new, independent researcher who is just learning about Git.

__Setup__

1. Log into ```https://github.com```
2. Press the "+" button at the top-right of the page, and select "New repository"
3. Give your repository a name, I will call mine "mad_lib"
4. Select "Public" (unlimited private repositories are available to students for free)
5. Leave the "Initialize this repository with a README" unchecked
6. Leave "Add .gitignore: None" as is.
..* a .gitignore file helps you to automatically decide what files to include when you are staging a commit. I would highly suggest using [gitignore.io](https://www.gitignore.io/) to automatically generate this file depending on your needs.
