# git Remote

when working with git, a **remote** is any git repository that is not on the machine you're working on. the counterpart to this is **local**, or the machine that is being developed on. 

take github for example, while git is the technology that allows you to create local repositories, github is the site that will host your remote repositories. once stored remotely, you can bring that repository back down or share it with others.

**Note**: while the repositories (local and remote) are related and track the same project, they can have different states if changes are not shared between the two

### Adding a remote

a remote can be added with the `git remote add` command, followed by the name and location of the remote.

The name is a local name, meaning it's your label and does not impact the actual remote whatsoever.

```
git remote add origin https://github.com/ElevenfiftyAcademy/GitFundamentals.git
```

---

### removing a remote

a remote can be removed with the `git remote remove` command, followed by the name of the remote.

```
git remote remove origin
```

## resources

- [Git Remote Documentation](https://git-scm.com/docs/git-remote)

---

[Back to home](../README.md)