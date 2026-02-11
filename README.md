# Github
So this is the ALAM 2025-2026 cohort hosted by Edgar, an aspiring Embedded Systems/ Systems Engineer at the time of writing this. I decided to tailor this Github rundown of knowledge that could help both my current team as well as future cohorts who join as ISAM sub-contractors. 

What this Workshop will cover:
* Git Tag
* Git Branch

## Git Branch 
As you've seen in the main ISAM repo, there are different branches which separate the different aspects ALAM works on. Branches also help you avoid the hassle that is merge conflicts. So if you want to work on a specific part before putting it all together or just keeping it separate, make a new branch by using:

``` bash
git branch name
```
The name is a placeholder so replace it it what you want then you use:

``` bash
git switch name
```
I've mentioned the shell commands if you are familiar with terminal, but you can also make a new branch using the github UI. You see the branch button that says Github on this repo? The one next to 2 Branches, click that and there should appear an option for a new branch. You can do that and then you git pull and then use git switch. You'd do this on your own repo of course.


## Git Tag
Simply put, its pretty much a bookmark of all of your final code for whatever you plan to use it for. Say you made a program to make an automated coffee machine and you've made sure it works 100%. You can git tag it to bring the code contents you had that made it work that 100%. So I'll walk through how to make a git tag by using simple calculator program in Java. You're supposed to work in increments but for the sake of this workshop, I've generated it and it works for what it does. So now that it's done, before I push to Github, I use:

``` bash
git add example.java # usual add 
git commit -m "works" # Usual commit 
git tag ver1.0 # Tagging the final code for the calculator program
git push # Pushing the code first
git push --tags # Pushing the tagged code
```
This is the final version of the code

