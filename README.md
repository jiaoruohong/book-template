# Book Template

## Fonts Demand

- [Source Han Sans (SC)](https://github.com/adobe-fonts/source-han-sans)
- [Source Han Serif (CN)](https://github.com/adobe-fonts/source-han-serif)

## Compile
- Compile in English: </br>
  ```bash
  latexmk -pdflatex=pdflatex -pdf ./book-en.tex 
  ```
- Compile in Chinese: </br>
  ```bash
  latexmk -pdflatex=xelatex -pdf ./book-cn.tex 
  ```

## Attention
Run LaTeX on this file several times to get Table of Contents, 
cross-references, and citations.

