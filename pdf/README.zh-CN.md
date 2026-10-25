# 全书中文 PDF · 审校修订版

[直接下载 PDF（526 页，约 32 MB）](https://raw.githubusercontent.com/Penghui-Zhang/Kalman-and-Bayesian-Filters-in-Python/master/pdf/Kalman-and-Bayesian-Filters-in-Python.zh-CN.pdf)

本版在前一轮英中对照审校和原 526 页全页版式检查基础上，另完成了一轮覆盖前言、14 章及全部附录的错别字、漏字与语句检查。公式采用常规字重，修复了多行公式换行、图片前字距、动画静态帧及部分代码分页和图表标注问题。

收录前言、第 1—14 章及原仓库全部 7 个附录（A、B、D、E、G、H、I）。附录 D、G、H 含未完成内容，附录 I 只有标题，保留原稿状态。

数学公式以英文 LaTeX 为基础校订排版，保留程序算法和图表，并修复旧版绘图库参数及失效接口；代码注释、运行输出及图中英文标签保留原文。数学定义、适用条件及必要技术解释已融入正文，已知公式与示例错误直接更正。“新息”用于 innovation，即更新前的测量残差；information 译为“信息”，并与更新后残差及状态估计误差区分。PDF 支持中文搜索、目录和书签跳转；交互演示须在 Jupyter 中运行。

原著：Roger R. Labbe Jr.；英文来源：[本仓库](https://github.com/Penghui-Zhang/Kalman-and-Bayesian-Filters-in-Python)，基于英文提交 `04b2bea802321086effbd99402fc13c893d11110`。

中文参考：[pleb631/Kalman-and-Bayesian-Filters-in-Python-chinese](https://github.com/pleb631/Kalman-and-Bayesian-Filters-in-Python-chinese)，参考提交 `6867aff40a76662af98aa89e20739a9b6a25b3f4`。中文翻译与审校使用 AI 辅助完成，未获原作者或出版社审定。

## 运行笔记本

已在 Python 3.12 环境中逐章使用 Jupyter 内核执行全部 22 个笔记本、608 个代码单元，未出现未处理错误。第 14 章用于说明 IMM 状态维数不匹配的示例会捕获并打印预期错误。PDF 采用原笔记本保存的图表，少量图表为改善标注重新绘制；交互控件和动画请在 Jupyter 中查看。

在仓库根目录运行：

```bash
python -m pip install -r requirements-notebooks.txt
jupyter notebook
```

依赖文件固定了本次实际验证的版本。

## 许可证

仓库 README 声明书籍使用 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)，但前言仍保留较早的 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 声明。本版保留两者及其来源，对本次翻译整理采用署名—非商业性使用—相同方式共享 4.0 条件；软件代码继续遵循原 MIT 许可证。PDF 中也保留相应说明。
