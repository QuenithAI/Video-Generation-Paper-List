<div style="display: flex; justify-content: space-between;">
  <a href="README.md"><img src="https://img.shields.io/badge/返回主页-red?style=for-the-badge" /></a>
  <a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/english-blue?style=for-the-badge" /></a>
</div>

# 🤝 成为这个项目的合作者之一

非常感谢您有兴趣为本项目做出贡献！我们诚邀有志之士成为这个项目的一份子，为社区共同维护这个项目。我们非常感谢每一位贡献者的关注和努力。

## 📖 目录

- [🤝 成为这个项目的合作者之一](#-成为这个项目的合作者之一)
  - [📖 目录](#-目录)
  - [📝 如何贡献](#-如何贡献)
  - [🚀 第一次贡献](#-第一次贡献)
  - [✍️ 添加新论文的指南](#️-添加新论文的指南)
  - [🗂️ 添加新数据集的指南](#️-添加新数据集的指南)
  - [📥 Pull Request 流程](#-pull-request-流程)

---

## 📝 如何贡献

您可以通过以下几种方式为项目做出贡献：

* ✍️ **添加新论文**: 分享您发现的、列表中尚未包含的研究。我们随时欢迎您通过 [PR](https://github.com/QuenithAI/Video-Generation-Paper-List/pulls) 或 [Issues](https://github.com/QuenithAI/Video-Generation-Paper-List/issues) 的方式，贡献您自己已发表或已公开的预印本论文。
* 🗂️ **添加新数据集**: 分享视频生成领域常用的基准数据集。
* 🛠️ **修复错误**: 修正拼写错误、格式问题或失效链接。
* 💡 **提出改进建议**: 通过 [Issues](https://github.com/QuenithAI/Video-Generation-Paper-List/issues) 提出改进方案，例如增加新的论文分类等。

## 🚀 第一次贡献

如果您是第一次参与开源贡献，请遵循标准的 GitHub 工作流程：

1.  **Fork** 本仓库到您的个人账户。
2.  从 `main` 分支创建一个新的特性分支。请使用一个有描述性的分支名称，例如：
    ```bash
    # 示例：添加一篇名为 MotionDirector 的论文
    git checkout -b feature/add-motiondirector-paper
    ```
3.  在您的新分支上进行修改（例如，添加论文或数据集条目）。
4.  提交您的更改。请使用清晰的提交信息来描述您的工作：
    ```bash
    # 示例：添加一个新的数据集
    git commit -m "feat: Add OpenVid-1M Dataset"
    ```
5.  将您的分支推送到您 Fork 的仓库：
    ```bash
    git push origin feature/add-motiondirector-paper
    ```
6.  从您 Fork 的仓库向本仓库的 `main` 分支创建一个 Pull Request。

## ✍️ 添加新论文的指南

这是最常见的贡献类型。为确保格式统一，请仔细遵循以下步骤：

1.  **找到正确的分类**
    * 首先，确定论文所属的主要类别（例如 `Text-to-Video`、`Image-to-Video`）。
    * 然后，找到其发表年份对应的区域。
    * 最后，将其放入 `✅ 已发表论文 (Published Papers)` 或 `💡 预印本论文 (Pre-Print Papers)` 列表中。

2.  **使用标准格式模板**
    * 请复制下方的模板并替换占位符信息。这能确保所有条目风格一致。

    **通用模板:**
    ```markdown
    * **[会议 年份]** ***论文标题:***<br>
        [![ArXiv](https://img.shields.io/badge/arXiv-PDF-b31b1b?style=for-the-badge&logo=arxiv)](https://arxiv.org/abs/your-arxiv-id)
        [![GitHub](https://img.shields.io/badge/GitHub-Repo-blue?style=for-the-badge&logo=github)](https://github.com/user/repo)
        [![Project Page](https://img.shields.io/badge/Project-Page-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://project-page-url.com)
    ```
    * 如果论文没有 GitHub 仓库或项目主页，请直接 **删除** 对应的行。
    * 如果论文已在会议上发表但没有 ArXiv 链接，您可以使用 `Paper` 图表。具体可参考 `README.md` 中的现有示例。

3.  **核实信息**
    * 在提交前，请仔细检查所有链接是否有效且指向正确的目标。
    * 确认论文标题、作者、会议和年份等细节准确无误。

## 🗂️ 添加新数据集的指南

我们也欢迎贡献新的公开数据集。请在 `README.md` 的 `Datasets` 表格中添加新的一行。

1.  **找到正确的位置**
    * 导航到 `README.md` 文件末尾的 `🗂️ Datasets` 表格。
    * 在表格的底部添加新数据集作为新的一行。

2.  **使用标准格式模板**
    * 请复制下方的 Markdown 表格行模板，并替换占位符信息。

    **通用模板:**
    ```markdown
    | **你的数据集名称** | 2025 | 文本, 视频 | 任务 (例如, Text-to-Video) | [![Paper](https://img.shields.io/badge/Paper-Link-red?style=for-the-badge)](https://paper-url.com) | [![Website](https://img.shields.io/badge/Website-Link-orange?style=for-the-badge)](https://dataset-website-url.com) |
    ```
    * 请确保 `|` 符号周围有空格，以保持表格格式正确。
    * 如果数据集没有关联的论文，您可以将 `Paper` 单元格的内容替换为 `N/A`。

3.  **核实信息**
    * 在提交前，请确保论文和数据集网站的链接均有效。
    * 确认数据集名称、年份、模态和任务描述准确无误。

## 📥 Pull Request 流程

当您提交 Pull Request 时，请注意以下几点：

* 为您的 PR 提供一个清晰的标题，例如 `feat: Add 3 new papers from CVPR 2025`。
* 在描述中简要说明您所做的更改。
* 提交后，项目维护者会尽快审查您的贡献。感谢您的耐心等待！