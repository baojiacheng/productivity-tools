# 如何在vscode中关联github,并创建公开或私有库

要在VSCode中关联GitHub并创建公开或私有库，您可以按照以下步骤操作：

- 确保您已经在GitHub上创建了一个账户。如果您还没有，请前往GitHub的官方网站（https://github.com/）注册一个账户。

- 在VSCode中安装GitHub扩展。在VSCode中，按下Ctrl+Shift+X（Windows和Linux）或Cmd+Shift+X（macOS）打开扩展视图，然后搜索“GitHub”。找到 GitHub Pull Requests and Issues 后安装。

- 安装完GitHub扩展后，您需要登录到您的GitHub账户。在VSCode的侧边栏中，单击“源代码管理器”图标（通常是一个三角形和条形图标），然后单击“登录到GitHub.com”。

- 在VSCode中创建一个新的文件夹，并打开它。

- 初始化Git存储库。在VSCode的终端中，运行以下命令：
```csharp
git init
```
- 创建一个新的GitHub仓库。在GitHub的官方网站上，单击“New repository”按钮，填写仓库名称和描述，然后选择是公开还是私有仓库。

- 将本地存储库与远程GitHub存储库关联。在VSCode的终端中，运行以下命令：
```csharp
git remote add origin https://github.com/your-username/your-repo-name.git
```
