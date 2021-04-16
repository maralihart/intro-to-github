# Introduction to GitHub
Curriculum written for [Mara Hart's Twitch (MaraDrinksMilk)](https://twitch.tv/maradrinksmilk), inspired by [GitHubGuides](guides.github.com)

This curriculum was written specifically for use cases with hackathons!

[Canva slides found here]

## Tools We'll Be Using
* [Visual Studio Code](https://code.visualstudio.com/Download) - an Integrated Development Environment to write all kinds of code in
* [GitHub Desktop](https://desktop.github.com/) - an great UI for connecting your local code to GitHub!

## What Is Git?
Imagine Google Docs, but way better and for coding. When you work in Google Docs, you can see what was edited, by who, and when!

When using Git, it's the same thing. You're able to take snapshots throughout the coding process to "save" your code. This is great when you mess up and need to go back to your last saved checkpoint or you need to know who wrote a certain piece of code.

A system where you can see what changes were made, when they were made, who made them, and why they were made is called **Version Control System**.

We use Git because it's so widely utilized and allows developers to work *independently on the same time*.

[Read More](https://guides.github.com/introduction/git-handbook/)

## The GitHub Flow During a Hackathon
Let's pretend we're coding for a hackathon. The first thing we want to do to get started is to **create a repository**.

A repository is essentially a project folder. 

**Steps to Set Up a Repository**:
1. Create a GitHub account!
2. Click the `+` in the top right
3. Select "New repository" to open a new page to set up your repository
4. Name your repository whatever you'd like - it just has to be unique to your account! Typically a descriptive name is best.
5. Next initialize this repository by clicking `Add a README file`. This will allow you to have a file that you can update with documentation. That's what we'll be editing through

**Getting It Onto Your Computer**
At this point, you should have *GitHub Desktop*. All you have to do is click the green button that says `Code` and then select the option `Open with GitHub Desktop`.

**Editing On Your Computer**
Now that we've got it on our computer, let's open in up in *Visual Studio Code* and create `index.html`.

You can use the following code:
```
<html>
  <body>
    <h1>Hello, World</h1>
  </body>
</html>
```

**Git Add, Commit, Push**
1. Now open GitHub Desktop back up!
2. On the left hand sidebar, you'll see the files that you've changed with the changes highlighted on the right (green for add, red for delete)
3. Make sure that the check is checked and that's *adding* the change to get ready for a commit.
4. Next, add a commit message in the bottom left title that's descriptive of your work, i.e. `created index.html`
5. Go ahead and *commit* your work. This is creating a snapshot of your code right then and there. You now have a saved copy of your code at this exact moment on your local machine.
6. Now, all we have to do is *push* it so it gets uploaded from your local computer to your GitHub repository.

**Git Pull**
1. On GitHub, click the file and then click the pencil icon in the top right of the code to edit.
2. Add a simple edit, such as changing `Hello, World` to `Hello, MaraDrinksMilk`.
3. Scroll down, give a commit message, and commit the changes.
4. Open up *GitHub Desktop* and notice in the top right the `Fetch origin` button and click that to get the latest updates from the website.
5. If you look at your code now, you'll see that the code you had on GitHub is now on your local computer. 

**Git Branch**
What if you're working with multiple people and you want to keep the code separate?
Branches are great for this! Branches can *branch* off and do their own thing, until you make a *pull request* (a way to suggest a change by supplying code) and *merge* with the main code.

1. Open GitHub Desktop and click the middle branch on the top that says `Current Branch main`
2. Click `New Branch` and add your name (typically the name of what you're about to do) and click `Create Branch`
3. Here, you'll do the same thing. As before on your local computer, except introduce a new edit, maybe say a paragraph tag that you like to code
```
<p>I love to code!</p>
```
4. Go ahead and add, commit, and push this.
5. Log back onto GitHub, you'll see a notification that a branch has had recent commits, click the `Pull Request` button on the right of this notification.
6. Open this pull request and notice how you can see the commit names and the file changed. This is really great when you have a bunch of team members creating different things and you want to see what's all going on!
7. Once you've decided that this branch is good and you like the code here, you can go ahead and merge it and delete the branch! Now everything's on main

**What's a Merge Conflict?**
The danger with having everyone edit is that sometimes those commits -- the snapshots -- won't always sync up.

1. Create a branch called `change-a` and add a change and submit a pull request according to the instructions above, but don't yet merge the pull request.
2. Repeat step 1 with a new branch called `change-b`.
3. Merge `change-a` to main.
4. View the `change-b` pull request, scroll down and you'll see that there is a merge conflict and you can solve it on GitHub. Simply remove the parts you don't want and click `Resolve Conflicts`
5. Go ahead and merge just like normal!

## Hosting a Website for Free!
Now, we have a working .html file that can be a webpage. A really easy hackathon project is a simple website that has information. But usually you want somewhere to host it so you can check it out from your phone or even a friend's computer!

1. Simply go to your Settings
2. Scroll down to GitHub Pages
3. Select the main branch to deploy from!
4. Refresh the page and you'll see a link appear
5. Click the link, you may have to wait a couple minutes (the bigger the project, the longer the wait)
6. Pull it up from your phone and see it from wherever!