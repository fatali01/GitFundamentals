# git push

when you have a [remote](./Remote.md) setup you'll need to begin to move [](./Commit.md) to the remote. this can be done with the command `git push`.

you can attach a name to your command to specify where your pushing to.

```
git push origin main
```

This command will push the **main** branch to the remote called **origin**. this means any commits that are in your local will be **pushed** to the remote.

### Upstream tracking

>Instead of including the name of the remote and the branch you're on every time, you can set local branches to track an upstream branch. This means you can tell the branch to push to its assigned upstream remote branch by using the `git push` command.

>before doing so, you'll need to use the `-u` or `--set-upstream` flag. this can be done on any `git push`.

```
git push -u origin main
```
after this command is used you can just use `git push` and it will function the same way 

## Resources

- [Git Push Documentation](https://git-scm.com/docs/git-push)

---

[Back to Home](../README.md)