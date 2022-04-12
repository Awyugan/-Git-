# gitignore的用法
忽略不需要的文档，你需要在`.gitignore`中把不需要同步的文件夹或文件忽略。
一方面可以缩小上传的文档大小，也可以把某些不想公开的内容仅在本地展示。

你只需要在`.gitignore`中写入需要忽略的文档，比如，本地的历史版本文件`.history`。同时，如果你正在使用不同的软件处理这个文件目录，也可以忽略软件的隐藏目录。我在使用的时候，就忽略了`obsidian`的配置文件。这些配置文件中可能会存在你的个人信息，因此需要你谨慎处理。

```
.history
.DS_Store
.vault-stats
.obsidian
```

![image](https://static.aiwriter.net/2utuxsJh4CXi46hzmc3uZ3/kTLxu72dooum8junC8JK5G/3sGxTQEqWo34gcNWgppepw)