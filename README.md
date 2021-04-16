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


## Hosting a Website for Free?