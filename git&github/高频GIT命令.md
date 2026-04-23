## 合并远程仓库和本地仓库
- 命令： git pull origin main --no-rebase --allow-unrelated-histories --no-edit
- 解释
* --no-rebase → 明确说：用 merge（不是 rebase）
* --allow-unrelated-histories → 允许两个不同起点的仓库合并
* --no-edit → 不弹编辑器
- 成功输出
--no-rebase → 明确说：用 merge（不是 rebase）
--allow-unrelated-histories → 允许两个不同起点的仓库合并
--no-edit → 不弹编辑器
