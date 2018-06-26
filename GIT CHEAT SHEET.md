# GIT学习以及使用

下面是GIT的部分命令以及规范的格式

## configure tooling

```
git config --global user.name "[name]"
git config --global user.email "[email address]"
git config --global color.ui auto

```

```
#创建我的配置
git config --global user.name "[Kingfa]"
git config --global user.email "[kingfaluis@gmail]"
```

## create repositoies

```
git init [project-name]
git clone [url]

#例如：
git init [scrapyTaobao]

```

## make changes

```
git status

```

## group changes

```
git branch
git branch [branch-name]
git checkout [branch-name]
git merge [branch]
git branch -d [branch-name]
git merge [branch]
git branch -d [branch-name]

```

## refactor filenames

```
git rm [file]
git rm --cached[file]
git mv [file-original] [file-renamed]

```



```

```

## refactor filenames

```
git rm [file]
git rm --cached [file]
git mv [file-original] [file-renamed]

```

## synchronize changes

```
git fetch [bookmark]
git merge [bookmark]/[branch]
git push [alias][branch]
git pull
```



参考文献

[1]: https://blog.csdn.net/ouyang_peng/article/details/48437365
[2]: https://zh.wikipedia.org/wiki/GitHub
[3]: file:///D:/Program%20Files/Git/ReleaseNotes.html
[4]: https://en.wikipedia.org/wiki/Markdown
[5]: https://blog.csdn.net/huangjw_806/article/details/78297851
[6]: 

