# pubuim-git

PubuIM Git 服务通知

## 如何使用

- 请现在 PubuIM 上创建 Git 服务然后，复制 hooks 地址，替换 `post-receive` 脚本中的第二行的 `HOOKS` 值

- 复制脚本到 Git 对应仓库的 hooks 目录,并确保有执行权限

- 尝试提交一个 Commit 并且 Push，即可收到推送。Enjoy :)


参考

- [Git Tools - Revision Selection](https://git-scm.com/book/tr/v2/Git-Tools-Revision-Selectio)
- [PRETTY FORMATS](http://git-scm.com/docs/pretty-formats)
- [Git Log](https://git-scm.com/docs/git-log)
- [Git Basics - Viewing the Commit History](https://git-scm.com/book/tr/v2/Git-Basics-Viewing-the-Commit-History)
- https://github.com/chriseldredge/git-slack-hook
