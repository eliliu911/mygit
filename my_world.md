Mac VSCODE GIT GITHUB 配置文章

https://blog.csdn.net/qq_37747262/article/details/81750417

源引用表达式main没有匹配error：

https://blog.csdn.net/songyuc/article/details/115251254

```
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
```

小白命令，执行 `git config pull.ff false`
