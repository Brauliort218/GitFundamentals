# git pull

Similar to a [git push](./Push.md), a `git pull` will interact with a remote repository. Only this time it will **pull** the changed it does not have from the remote down to the local repository.

This means any commits make that are on the remote repository will be pulled down and added to the local repository.

This can be done by adding the remote name and branch name:
```
git pull orgin main
```

If there is anyupstream connection established, you can use `git pull` without specifying a remote or a branch.
## Resources 

- [Git Pull Documentation](https://git-scm.com/docs/git-pull)

---

[Back to home](../README.md) 