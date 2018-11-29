Von Markdown nach PDF mit [pandoc](https://pandoc.org/demos.html):
```zsh
pandoc --pdf-engine=xelatex --template=../inc/mytemplate.tex \\
  --variable mainfont="Palatino" --variable sansfont="Helvetica" \\ 
  --variable monofont="Menlo" --variable fontsize=12pt \\
  -V geometry:margin=1in -o exam_2018-11-25.pdf exam_2018-11-25.md 
```
