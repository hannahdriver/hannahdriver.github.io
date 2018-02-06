# Biol-812 Assignment

# Using Git

## Questions:

**1. When should you use Git for a project?**

+ Git is a great tool for collaboration, as multiple people can work on the same project at once. Git is also useful for keeping track of changes made to a project and allowing users to revert back to previous versions of their work, which is beneficial for projects that involve a lot of revisions, or trial and error.

**2. What kind of files/info should be saved in a Git repository? What types of files/info should not be included in a Git repo?**

+ Code and text files should be saved in a Git repository, however, large data files and sensitive information/data should not be included in a Git repository.

**3. What are the commands to undo a commit?**

+ To undo a commit, you can use the following command:

```{}
git revert <commit_ID>
```

+ Or you can revert to the previous version of your file using the following command:

```{}
git checkout HEAD~1 <file_name>
```

**4. One of your repositories is in a "detached HEAD" state. How do you fix this?**

+ If one of your repositories is in a "detached HEAD" state, you can return to the master branch using the following command:

```{}
git checkout master
```

**5.1 Your boss has no idea what Git is or why you are using it. Explain the pros / cons of using Git for your research project.**

**Pros:**

+ Team collaboration is easy
+ Tracking changes to your files is simple with frequent commits
+ Mistakes can be corrected by reverting back to previous versions of your projects

**Cons**

+ Large data files cannot be easily manipulated with Git
+ Learning to program in Git requires time and effort

**5.2 Explain the pros / cons of hosting your project in a public (or private) repository on Github/Bitbucket/Gitlab/etc.**

**Pros:**

+ External users can collaborate with you and improve your projects
+ It serves as a back up for your work
+ It's free to host public repositories

**Cons**

+ Publishing private data on a public server means that anyone can access your information
+ It can be expensive to host multiple private repositories
