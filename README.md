# how-to-sync-fork-repo
Colaborating to open source projects? Here you will find instructions how to sync your fork repository!

# How to sync you fork repository - shortest explanation possible

```
$ git clone https://github.com/your_account/yor_fork.git

$ git remote add upstream https://github.com/repo_owner/source_repo.git

$ git fetch upstream

$ git checkout main # or git checkout master

$ git merge upstream/main # or git merge upstream/master

$ git push origin main # or git push origin master
```
# ```master``` or ```main``` branch name should I use?

In old times, the github default branch name were ```master```. Nowadays, the default name is ```main``` instead. So, for old repos use ```master``` and for newest ones use ```main``` (or any different name the repository owner have choosen for it).

It is pretty easy to realize which branch name you should use. Check this saetting on the repository main page. For example, in [Primefaces](https://github.com/primefaces/primefaces) repository page you should see ```master``` as repository name:


In a new repository such as [V3DLib](https://github.com/wimrijnders/V3DLib) you should find ```main``` as default branch name:


