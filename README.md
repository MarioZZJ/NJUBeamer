# NJU Beamer

南京大学 Beamer 演示文稿模板，配色基于南京大学视觉形象规范化标准。

## 使用

```latex
\documentclass[10pt]{beamer}
\usetheme{njubeamer}
```

使用 XeLaTeX 编译：

```bash
latexmk slide.tex
```

编译产物输出到 `out/` 目录。

## 主题选项

| 选项 | 说明 |
|------|------|
| `en` | 纯英文模式（不加载 ctex） |
| `sectiontoc` | 每节前显示目录 |
| `nosectionpage` | 关闭节过渡页 |

## 致谢

- 布局参考 [NKU Presentation Beamer](https://www.overleaf.com/latex/templates/nku-presentation-beamer/gctydndnvstd)
- 颜色与标识来自 [NJUVisual](https://github.com/nju-lug/NJUVisual)
