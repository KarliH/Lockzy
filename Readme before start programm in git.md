# Tips for using git  

I don't know how far are you guys go at software projects, so I would write while assuming the person who read this is a beginner.  

But I will only write the things which my teacher didn't say while I was learning git. For how to use git, I believe there are a lot of tutorials are far more better than me.

---

#### *Important!!*   
Don't push to `mater` branch before you ensure the entire program can run well, and contain the newest update from other teammates.

---

## One thing you have to install: *Git*

It will also be used in the future.
[Installing tutorial here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

---

## Two way to push your code online  

### The easiet way for beginner: Use *GitHub Desktop*  

[download here](https://desktop.github.com/) (both Windows/macOS can use)

for other application, please google

### If you don't want to install anything: Use *cmd* in your computer

Find any commands you want to do from [A list of my commonly used Git commands](https://github.com/joshnh/Git-Commands)

---

## Some summarise from what I experienced

1. Everyone please create your own branch when you want to update the code. Otherwise it might (99% possibilities) cause at lease one of you cannot push your work before you spend a lot of time to merge your code to the new code in severs.
2. Please avoid to use `git push -f`. You might delet others work...
3. **Specially for people who using cmd to push** always check which branch your git is working at, so that you would not push your code to others' branch and causing the error same as the first situation.
4. **Specially for people who using cmd to push** When some team member create a new branch but you cannot see it, use `git fetch`
