# Git and GitHub - week 2 - exercise 5 Q&A
### **1. How do you see the files changed within each commit from git log?** 
<br>To see the files changed within each commit from git log, use ***git log --raw*** command. It is best way to find what file changed in a commit.
### <br>**2. How do you see the contents of what changed within each file from the git log?**
<br>To see the whole history of the file, use ***git log --follow -p -- path-to-file*** (diffs for each change are included).
### <br>**3. What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)**
<br>HEAD is basically seeking wherever you are in your commit history. When you make a commit, HEAD will also follow. 
