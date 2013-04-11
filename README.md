# gitforbzr

Configs that make sense to bazaar users. These are made to go in the `alias` section of your $HOME/.gitconfig file. See the example file for details.

## Configurations

* whoami
* ignored
* update
* nick
* ls
* branches
* shelve
* unshelve
* revno
* revert
* annotate
* pack
* tags
* deleted

## Workflows

Here are some basic workflows that can help bazaar users get used to git. One of the most noticeable changes between bazaar and git is that while each branch is a separate directory in bazaar, git has one folder for the repository and you can switch branches by issuing a command to git (typically 'checkout').

### Branching


```
$ bzr branch trunk ../branches/my_branch_name && cd ../branches/my_new_branch_name
```

```sh
# go to the branch you want to branch off of  
$ git checkout master
# the following branches off the current branch 'master'  
$ git branch my_new_branch_name  
# checkout your new branch  
$ git checkout my_new_branch_name  
```
```sh
$ git checkout -b my_new_branch_name master
```
