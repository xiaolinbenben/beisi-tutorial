# 使用 GitHub Desktop 进行 Fork 和 Pull Request 协作 💻

1. **Fork 仓库**  
   - 登录到 [GitHub](https://github.com/)。  
   - 找到目标仓库页面，点击右上角的 `Fork` 按钮。这将在你的个人账户下创建一个该仓库的副本。

2. **安装与登录 GitHub Desktop**  
   - 如果尚未安装，请下载并安装 [GitHub Desktop](https://desktop.github.com/)。  
   - 打开 GitHub Desktop，并使用你的 GitHub 账号登录。

3. **克隆 Fork 后的仓库**  
   - 在 GitHub Desktop 中，点击 `File -> Clone Repository`。  
   - 在弹出的窗口中选择 `Your Repositories` 标签页，找到你刚刚 Fork 的仓库，然后点击 `Clone` 将其克隆到本地。

4. **创建分支**  
   - 克隆完成后，在 GitHub Desktop 中点击顶部的 `Current Branch`，然后选择 `New Branch` 创建新分支。  
   - 为分支命名（例如 `feature/your-feature-name` 或 `fix/your-fix-name`），并切换到该分支。

5. **修改代码并提交更改**  
   - 在本地编辑器中对代码进行修改。  
   - 返回 GitHub Desktop，查看更改详情。  
   - 按照 [Git 提交规范](/资料/手册图片/提交规范.png) 填写提交信息，确保描述清晰准确。  
   - 点击 `Commit to <branch-name>` 提交更改到本地分支。

6. **推送分支到远程仓库**  
   - 提交完成后，点击 `Push Origin` 将本地分支推送到你在 GitHub 上的 Fork 仓库。

7. **发起 Pull Request (PR)**  
   - 登录到 GitHub 网页端，进入你 Fork 的仓库页面。  
   - 切换到你刚刚推送的分支，点击 `Compare & pull request` 按钮。  
   - 在 PR 页面中，描述你的更改内容（可以包括改动原因、功能说明等）。  
   - 确认无误后，点击 `Create pull request` 提交 PR。  

8. **等待审查与合并**  
   - 提交 PR 后，等待原仓库的维护者审查你的更改。  
   - 如果审查过程中有反馈或需要修改，可以在同一分支上继续提交新的更改，这些更改会自动更新到现有的 PR 中。  
   - 审查通过后，维护者会将你的更改合并到主仓库。
  
9. **同步原仓库更新（Sync Fork）**  
   - 如果原仓库有新的更新，你需要同步你的 Fork 仓库以保持最新。  
   - 登录到 GitHub 网页端，进入你 Fork 的仓库页面。  
   - 在页面上方，点击 **`Sync fork`** 按钮，然后选择 **`Update branch`**。  
     如果没有看到 `Sync fork` 按钮，请确保你当前在主分支（如 `main` 或 `master`）。  
   - 同步完成后，你的 Fork 仓库将包含原仓库的最新更改。
