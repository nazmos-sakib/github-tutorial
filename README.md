Welcome to the github-tutorial !


***
## Merge Local Repo with GitHub

To merge two Git repositories, you can follow these steps:

1. Clone your GitHub repository :

```
git clone https://github.com/yourusername/your-github-repo.git
cd your-github-repo
```

2. Add the local repository as a remote:

```
git remote add local-repo /path/to/your/local/repo
```
3. Fetch the changes from the local repository:
```
git fetch local-repo
```
4. Merge the changes:
> If your local repository uses a different branch name, replace main with the appropriate branch name.
```
git merge local-repo/main --allow-unrelated-histories
```
5. Add new files and changes
```
git add <filename>
```
6. Commit the merge:
```
git commit -m "Merged local repo into GitHub repo"
```
7. Push the changes to GitHub:
```
git push origin main
```
