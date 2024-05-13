https://www.mkdocs.org/user-guide/configuration/#nav
[mkdocs官方文档](https://www.mkdocs.org/user-guide/configuration/#nav)

## 项目下载
1.  下载 m17y.github.io.git

```shell
git@github.com:m17y/m17y.github.io.git
```
2. 同步子模块
[Git 工具 - 子模块](https://git-scm.com/book/zh/v2/Git-%E5%B7%A5%E5%85%B7-%E5%AD%90%E6%A8%A1%E5%9D%97)
```shell
# 下载子模块
git submodule init
git submodule update
```

3. 如何添加子模块
```shell 
git submodule add https://github.com/chaconinc/DbConnector
```

## 项目运行

```
# 两种方法（选其一即可）：
# 1. 运行一个本地服务器，访问 http://127.0.0.1:8000 可以查看效果
mkdocs serve -v

# 2. 在 site 文件夹下得到静态页面, 访问静态也没查看效果
mkdocs build -v

# 获取 mkdocs 的命令行工具的说明（解释了命令和参数的含义）
mkdocs --help
```