## 模板参考
- [tsaoyu/WHUT-LaTeX-bachelor](https://github.com/tsaoyu/WHUT-LaTeX-bachelor)		*last commit on 8 Jun 2019*
- [mengyuqianxun/WHUT--LaTeX-bachelor-thesis](https://github.com/mengyuqianxun/WHUT--LaTeX-bachelor-thesis)	*last commit on 16 Jul 2020*

## 导入到 Overleaf
1. 创建新项目
2. 上传项目
3. 上传项目的压缩包（.zip文件)

## Overleaf Setting
- 编译器：XeLaTeX
- TeX Live version：2020
- 主目录：main.tex

## 实用工具
- 数学公式：[Online LaTeX Equation Editor](https://latex.codecogs.com/eqneditor/editor.php)
- 表格生成：[Table Generator](https://www.tablesgenerator.com/)

## 参考文献
目录下的`bibfile.bib`和`gbt7714-2005.bst`为`main.tex`中使用：
```tex
\addcontentsline{toc}{section}{参考文献}
\bibliography{bibfile}
\clearpage
```
而后来并没有使用这样的参考文献生成方式，因而注释。项目中使用的参考文献生成，为引入的`reference.tex`中的`thebibliography`。所以，`main.tex`中使用的是：
```tex
% \addcontentsline{toc}{section}{参考文献}
% \bibliography{bibfile}
\include{body/reference}
% \clearpage
```