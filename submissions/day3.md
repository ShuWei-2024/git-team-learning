# day3：掌握基本的git分支操作

## fujiajun
### 学习记录
1. **merge**：将一个分支的更改合并到当前分支
   - `git merge <branch>` 将指定分支合并到当前分支
   - 示例：`git merge main` 将main分支合并到当前分支

2. **rebase**：将提交历史重新应用到另一个分支上，产生线性的提交历史
   - `git rebase <branch>` 将当前分支的提交重新应用到目标分支
   - 示例：`git rebase main` 将当前分支基于main进行变基

3. **branch**：分支管理
   - `git branch` 列出本地分支
   - `git branch <name>` 创建新分支
   - `git branch -d <name>` 删除本地分支
   - `git checkout -b <name>` 创建并切换到新分支

4. **推送/删除远端分支**
   - `git push origin <branch>` 推送本地分支到远程
   - `git push origin -d <branch>` 删除远程分支
   - `git push origin :<branch>` 另一种删除远程分支的方式

### 今日操作记录
今天完成了以下操作：
1. 将main分支合并到fujiajun分支（git checkout fujiajun && git merge main）
2. 创建了submissions/day3.md文件，记录了关于git分支操作的方法
3. 将修改后的分支合并回main
