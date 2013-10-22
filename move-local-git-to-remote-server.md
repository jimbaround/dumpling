How to move local git repository to remote server and preserve history
======================================================================

On remote server, set up bare git repository  

```shell
$ git init --bare /path/to/repo.git
```

On local repository:  

```shell
$ git push --mirror ssh://url/path/to/repo.git
```



