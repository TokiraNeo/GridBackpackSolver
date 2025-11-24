# Contribute to Grid Backpack Solver

感谢您有兴趣为 Grid Backpack Solver 项目做出贡献！

## 前提条件

在开始之前，请确保您已安装以下工具：

- Visual Studio 2022 或 Rider
- Unreal Engine 5.0 或更高版本
- Git

## 开始开发

### 1. 克隆仓库

```bash
git clone https://github.com/TokiraNeo/GridBackpackSolver.git
cd GridBackpackSolver
```

### 2. 设置开发环境

1. 在本地仓库目录中创建一个 C++ Unreal 项目
2. 生成或重新生成以下文件和目录：
   - `*.sln`（Visual Studio 解决方案文件）
   - `Saved\` 目录
   - `Intermediate\` 目录
   - `Binaries\` 目录

如果这些文件已存在，您可以：

1. 删除它们
2. 右键点击您的 `*.uproject` 文件
3. 选择 "Generate Visual Studio project files" 来重新生成它们

### 3. 打开解决方案

打开生成的 `*.sln` 文件，您将在解决方案资源管理器中看到 `Plugins\` 目录中的源代码。

## 贡献流程

### 分支策略

- `main` 分支包含稳定版本的代码
- `develop` 分支包含最新的开发代码，用于合并功能分支
- 创建功能分支来开发新功能或修复 bug
  - 功能分支命名格式：`feature/功能名称`
  - Bug 修复分支命名格式：`bugfix/修复描述`

### 提交代码

1. 确保您的代码遵循项目的代码风格
2. 编写清晰的提交消息，简要描述您的更改
3. 在提交前测试您的更改

### 提交拉取请求

1. 推送您的分支到远程仓库
2. 在 GitHub 上创建新的拉取请求
3. 提供详细的描述，解释您的更改内容和目的
4. 等待代码审查

## 代码风格指南

- 遵循 UE4/UE5 的 C++编码标准
- 为关键函数和类添加注释
- 保持代码简洁和可读
