<!--
  <<< Author notes: Step 4 >>>
  Just a historic note: The previous version of this step required responding
  to a pull request review before merging. The previous version also handled
  if users accidentally closed without merging.
-->

## Step 4: 合并 Pull Request

_你已经创建了 Pull Request，做得很好! :sunglasses:_

Pull Request 的意义在于让他人有机会在代码合并到主分支之前，先审查并提出意见。
当所有讨论完成并确认无误后，就可以将这个分支的修改正式合并进主分支。

**什么是合并(merge)?**: [合并（merge）](https://docs.github.com/en/get-started/quickstart/github-glossary#merge)_ 的过程，就是把你分支上的改动整合进 main 分支。
一旦合并完成，你的修改就会成为主分支的一部分。更多详细说明可参阅 "[Merging a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/merging-a-pull-request)"。

在上一步中，你可能注意到 GitHub Actions 在后台运行，它会自动帮你推进课程进度。
当合并按钮变成绿色时（如下图），就表示可以进行合并操作了。

![screenshot of green merge pull request button](/images/Green-merge-pull-request.png)

### :keyboard: 实操环节: Merge the pull request

1. 点击 **Merge pull request**
2. 点击 **Confirm merge**，确认合并
3. 当分支成功合并到 `main` 后，这个分支就没用了，你可以点击 Delete branch 将其删除。

   ![screenshot showing delete branch button](/images/delete-branch.png)

4. 等待大约20秒，然后刷新当前课程页面。[GitHub Actions](https://docs.github.com/en/actions) 会自动检测并进入下一步。

> [!NOTE]
> 在下一步的 **Finish** 步骤你可以看到本教程的总结和后续建议，了解更多可学习的内容。