# git commit

The command `git commit` will take all tracked changes (items added with[git add](./Add.md)) and package them up in what is called a commit.

commits come with commit messages that are `required` for each commit. you add a message to a commmit command by using the `-m` flag followed by a message in quotes.

A commit message _`can`_ be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

for example, if we have an application we're working on where we just built out the ability to register new accounts, then you might have some variation of the following:

```
git add .
git commit -m "Added register funcionality"
```

then when viewing the history of a git repository, you can pinpoint where the registration functionality was added.

## Resources

- [Git Commit Documentation](https://git-scm.com/docs/git-commit)

---

>[back to home](../README.md)