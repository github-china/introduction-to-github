<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 2: 提交文件（Commit a file）

_你已经成功创建了一个分支! :tada:_

创建分支的好处是，你可以在不影响 main 主分支的情况下修改项目。
现在有了属于你的分支，接下来我们要创建一个新文件，并完成你的第一个提交（commit）！

**什么是提交(commit)？**: _[提交](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ 是指对项目中的文件或文件夹的一组修改。提交存在于某个分支中。更多信息，请参阅文档 "[关于提交](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)"。

### :keyboard: 实操环节：完成你的第一个提交

下面会带你在 GitHub 上完成一次文件修改提交。

“提交” 可以是对项目所做的任何修改，比如修改文件内容、新增文件、删除文件或重命名。
本练习中，我们要先在你的分支上添加一个新文件，并将它提交到仓库中。


> [!NOTE]
> `.md` 是 Markdown 文件的扩展名。Markdown 是一种轻量级标记语言，用来格式化文字。其语法格式可以阅读我们的文档 "[基本撰写和格式语法](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)" 或学习课程 "[使用 Markdown 进行沟通](https://github.com/skills/communicate-using-markdown)"。

1. 在仓库导航栏中， 进入 **< > Code** 页面，确认你当前所在的分支是 `my-first-branch`。

2. 点击 **Add file** 下拉菜单，选择 **Create new file** 。

   ![create new file option](/images/create-new-file.png)

3. 在 **Name your file...** 输入框中填写文件名： `PROFILE.md`.

4. 在 **Enter file contents here** 编辑框中输入以下内容

   ```
   Welcome to my GitHub profile!
   ```

   ![profile.md file screenshot](/images/my-profile-file.png)

5. 在页面右上方，点击 **Commit changes...**。
在弹出的提交界面中，你可以填写一条简短的信息来说明这次提交的内容。
虽然 GitHub 会自动生成一条默认信息，但这次我们自己写一条，输入： `Add PROFILE.md`。

   ![screenshot of adding a new file with a commit message](/images/commit-full-screen.png)

6. 本节我们暂时不用关心其他选项，直接点击 **Commit changes**。
7. 等待大约20秒，然后刷新当前课程页面。[GitHub Actions](https://docs.github.com/en/actions) 会自动检测并进入下一步。
