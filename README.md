# DataStructure-Report-2018

这是数软学院2018级软件工程创新班数据结构课程提交作业使用的 Github 仓库，请各位同学 Fork 本仓库到自己的账户下操作，并使用 Pull Request 提交到主仓库。



具体操作方法如下：

- 点击 `fork` 主仓库到自己的账户，此时在自己的账户下应该可以看到名为`DataStructure Report 2018`的仓库。
- 安装 Git ，可以参考[这篇文章]( https://www.liaoxuefeng.com/wiki/896043488029600/896067074338496 )进行操作。
- 配置 SSH ，可以参考[这篇文章]( https://www.liaoxuefeng.com/wiki/896043488029600/896954117292416 )进行操作。
- 将自己账户下的该仓库克隆到本地，可以参考[这篇文章]( https://www.liaoxuefeng.com/wiki/896043488029600/898732792973664 )进行操作。

- 在本地仓库中建立一个以自己学号与姓名命名的文件夹。

- 将要提交的文件放到上面创建的文件夹中。

- 在当前路径下打开 git bash，使用以下命令向本地仓库提交修改

  ```shell
  # cd "DataStructure-Report-2018/201820xxxx张三/"
  git add 第一次实验.doc
  git commit -m "add file"
  ```

  其中`add file` 可以替换为其他字符串。

- 接着使用以下命令推送到远程

  ```shell
  git push
  ```

  当出现类似下面的输出时表明提交成功

  ```shell
  Enumerating objects: 3, done.
  Counting objects: 100% (3/3), done.
  Writing objects: 100% (3/3), 235 bytes | 117.00 KiB/s, done.
  Total 3 (delta 0), reused 0 (delta 0)
  To github.com:iLern/DataStructure-Report-2018.git
   * [new branch]      master -> master
  Branch 'master' set up to track remote branch 'master' from 'origin'.
  ```

  

-  最后，到 Github 上创建  Pull Request ：

   在接下来的页面中点击「compare across forks」，并在左边选择主仓库（iLern/DataStructure-Report-2018），右边选择你的仓库： 

   输入标题和正文（可为空）后点击最下方的「Create pull request」即可。你的提交将在被审阅之后合并到主仓库 。