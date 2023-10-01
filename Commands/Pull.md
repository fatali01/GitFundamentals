# git pull

similar to a [git push](./push.md), a `git pull` will interact with a remote repository. only this time it will **pull** the changes it does not have from the remote down to local repository.

this means any commits made that are on the remote repository will be pulled down and added to the local repository

this can be done by adding the remote name and the branch name:
```
git pull origin main
```

if there is any upstram connectiion established, you can use `git pull` without specifying a remote or branch

## Resources

- [Git Pull Documentation](https://git-scm.com/docs/git-pull)

---

[Back to home](../README.md)