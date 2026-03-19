# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

# 欢迎来到高中数学互动课堂

这是一个基于 Markdown 构建的教学网页，支持完美的排版与互动。

## 1. 核心公式展示

在这里，我们可以轻松插入行内公式，例如一元二次方程的求根公式为 $\frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$。

或者展示独立的块级公式，例如正态分布的概率密度函数：

$$
f(x) = \frac{1}{\sigma\sqrt{2\pi}} e^{-\frac{1}{2}\left(\frac{x-\mu}{\sigma}\right)^2}
$$

## 2. 互动几何：动态函数图像

下面我们通过 GeoGebra 嵌入了一个动态的三维坐标系，您可以直接在网页上拖动和旋转它：

<iframe scrolling="no" title="Tredimensionellt koordinatsystem" src="https://www.geogebra.org/material/iframe/id/azp3xktm/width/1000/height/600/border/888888/sfsb/true/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/true/ctl/false" width="1000px" height="600px" style="border:0px;"> </iframe>

> **提示：** 您只需在 GeoGebra 网页版上点击“分享 -> 嵌入”，就能获取并替换上面的 `<iframe>` 代码。