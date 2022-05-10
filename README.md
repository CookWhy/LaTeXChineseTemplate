# LaTeX 中文模板

本仓库存放一些本人修改过的中文 LaTex 模板，主要是对一些英文出版机构的 LaTeX 适合中文环境，以作学习之用。

验证环境：Windows 10，TeX Live 2021

目前有的模板主要有 Wiley。

## 验证环境

Windows 和 Mac 下测试通过：

Windows 使用 Tex Live 2021 版本；

Mac 使用 MacTex 2021 版本。

## Wiley 7x10 中文模板

Wiley 是全球历史最悠久﹑最知名的学术出版商之一，它的英文书籍想必大家都用过，排版非常漂亮，可惜官方并未提供对应的中文版本；本人尝试动手让 Wiley 原版支持中文，并适当按中文习惯作了一些调整。

本模板放置于目录 Wiley_latex_macros_7x10 中，原始的 Wiley 模板为 7″ x 10″ 英寸书籍模板，已按中文习惯修正为 A4 尺寸。

使用时，可根据 w-bktmpl.tex 文件修改，生成自己的文档。w-bktmpl.tex 文档本身也是该模板的说明和使用样例。

如果需要预览本模板样式，可查看 Wiley_latex_macros_7x10/w-bktmpl.pdf 文件，这是根据 w-bktmpl.tex 生成的中文书籍样例文件。

本模板适合用于科技中文写作，不建议用作文学类题材。

## 书籍封面模板

目录 bookcover 下为书籍封面模板，有一些模板简单修改过才可以编译，现收集在这里。

### cover0

来源 URL ：https://tug.org/PSTricks/main.cgi?file=Examples/Logos/logos

略微根据 A4 尺寸作过调整，使用 "latex -> dvips -> ps2pdf" 的编译方式来获得一页 pdf 输出，并插入书籍的首页作为封面。

替代文件内容及 tiger.eps 文件后，使用 build.cmd 直接编译，也可以用 xelatex 直接编译：

```cmd
xelatex cover0.tex
```

### cover1

来源 URL：https://latexdraw.com/tikz-cover-pages-gallery/

根据中文简单调整，可直接编译。

### 其它资源

1. 书籍菲页集合：http://dante.ctan.org/tex-archive/info/latex-samples/TitlePages/titlepages.pdf

# TODO

记录一些待解决的问题：

* contents in brief

    Wiley 模板里有一个这个英文选项，但是在中文来说，我不确定对应哪个内容。

# 问题反馈

如果在使用这些模板过程中碰到排版问题，或是有修改需求，可于本仓库 issue 反馈，反馈时请描述清楚问题及需求。

我会尽量抽时间解决并更新版本。
