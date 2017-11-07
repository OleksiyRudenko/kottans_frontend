# Kottans Frontend Course Reflections

`[171023]` - initialized

This is a reflections register to be completed while
passing [Kottans frontend course](https://github.com/Kottans/frontend).

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Legend](#legend)
- [Courses Pathway](#courses-pathway)
- [Kottans Course Tasks](#kottans-course-tasks)
  - [Task 0 - Getting familiar with Git and Github](#task-0---getting-familiar-with-git-and-github)
  - [Test 1 - Linux command line, server and http tools](#test-1---linux-command-line-server-and-http-tools)
  - [Test 2 - More of git and github](#test-2---more-of-git-and-github)
- [Going to learn](#going-to-learn)
  - [Git related](#git-related)
  - [Misc skills](#misc-skills)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


## Legend

Each article studied is commented with three reflection items:
 * `new----- :` what was new to me
 * `surprise :` what has surprised me
 * `will use :` what I shall use

`[171024]` - occasionally date in format `[YYMMDD]` can be specified
for future reference.

[TOC :arrow_double_up: ](#table-of-contents)

## Courses Pathway

 - [x] [How to Use Git and GitHub](https://www.udacity.com/course/how-to-use-git-and-github--ud775)
 - [x] [try.github.io](https://try.github.io/levels/1/challenges/1)
 - [x] fork/PR [Kottans/mock-repo@github](https://github.com/Kottans/mock-repo)
 - [x] [Linux Command Line Basics](https://www.udacity.com/course/linux-command-line-basics--ud595)
 - [x] [Configuring Linux Web Servers](https://www.udacity.com/course/configuring-linux-web-servers--ud299)
 - [x] [Networking for Web Developers](https://www.udacity.com/course/networking-for-web-developers--ud256)
 - [x] [Version Control with Git](https://classroom.udacity.com/courses/ud123/)
 - [ ] [GitHub & Collaboration](https://classroom.udacity.com/courses/ud456)
 - [ ] [HTML and CSS Syntax](https://www.udacity.com/course/intro-to-html-and-css--ud304)
 - [ ] [Responsive Web Design Fundamentals by Google](https://www.udacity.com/course/responsive-web-design-fundamentals--ud893)
 - [ ] [Intro to JavaScript](https://www.udacity.com/course/intro-to-javascript--ud803)
 - [ ] [Object-Oriented JavaScript by Hack Reactor](https://www.udacity.com/course/object-oriented-javascript--ud015)

[TOC :arrow_double_up: ](#table-of-contents)

## Kottans Course Tasks

### Task 0 - Getting familiar with Git and Github

 * Git and GitHub basics (##1,2)
     - `new----- :` tuning up Git Environment, PRs
     - `surprise :` git flexibility
     - `will use :` many techniques, e.g. conflict resolution, github PR
 * Create this repo and README.md with impressions (##3,4,5)
     - `new----- :` peace of cake
     - `surprise :` not much, really
     - `will use :` again and again
 * Pull requests to [Kottans/mock-repo](https://github.com/Kottans/mock-repo) (#6)
     - `new----- :` pull request process
     - `surprise :` couldn't pick particular change for the merger, and
       [skip unnecessary file](#git-related)
     - `will use :` pull request technique

[TOC :arrow_double_up: ](#table-of-contents)

### Test 1 - Linux command line, server and http tools
[The test itself](https://github.com/Kottans/frontend/blob/master/test01.md)

Completed lessons evidences:

 ![LinuxCommandLineBasics completed](task_1/01-LinuxCommandLineBasics.png)
 
 ![ConfiguringLinuxWebServer completed](task_1/02-ConfiguringLinuxWebServer.png)

 ![NetworkingForWebDevelopers completed](task_1/03-NetworkingForWebDevelopers.png)

Reflections:
 * Linux Command Line Basics (#1)
     - `new----- :` Vagrant
     - `surprise :` control of every aspect of OS
     - `will use :` Vagrant
 * Configuring Linux Web Servers (#2)
     - `new----- :` serving HTTP from VM
     - `surprise :` complicated dependecies
     - `will use :` web-server from VM
 * Networking for Web Developers (#3)
     - `new----- :` `nc` (netcat) untility; `NAT` mechanics
     - `surprise :` easyness of traffic interception for debug tasks;
                    `traceroute` mechanics
     - `will use :` TCP mechanics knowledge
 * HTTP: The Protocol Every Web Developer Must Know (##4,5)
     - `new----- :` TRACE, OPTIONS verbs;
                    how web query & response get transformed into
                    request/response messages;
                    TLS is SSL+; Cache-Control;
     - `surprise :` multiple HTTP auth methods;
                    `407 Unauthorized` is not a dead-end
     - `will use :` RFC-2616

[TOC :arrow_double_up: ](#table-of-contents)

### Test 2 - More of git and github

[The test itself](https://github.com/Kottans/frontend/blob/master/test02.md)

Completed lessons evidences:

 ![VersionControlWithGit completed](task_2/00-VersionControlWithGit.png)

Reflections:
 * Version Control with Git (#0)
     - `new----- :` `git reset --mixed|soft`
     - `surprise :` quite transparent difference between resetting modes
     - `will use :` `git reset`
 * GitHub & Collaboration (#2)
     - `new----- :` 
     - `surprise :` 
     - `will use :` 

[TOC :arrow_double_up: ](#table-of-contents)

## Going to learn

### Git related

 - [x] Skipping files on pull request. For e.g. the target repo
       doesn't contain `.gitignore`, and I need it to make my life
       a bit easier: have it and avoid extra steps on ignoring its
       existence at every git action.
       How to remove this file from the pull request scope?
       -- Populate your `~/.gitignore`
       and do `git config --global core.excludesfile ~/.gitignore`
 - [x] Post Pull Request activity:
   - [x] merge to forked master? - if PR's successful, merge master from upstream
   - [x] just kill the branch? - kill it upon PR complete

### Misc skills

 * [ ] [Improve typing skills](https://www.typingclub.com/)

[TOC :arrow_double_up: ](#table-of-contents)