> \[!info\]
>
> 🌱 來自: \[\[vim TODO\]\]

# pandoc in vim #🚧 施工中

`bibliography: bibliography.bib` `csl: biomed-central.csl`

`pandoc --citeproc --bibliography="$HOME/Zotero/zotero_main.bib" -t markdown-citations --csl="$HOME/Zotero/styles/american-medical-association.csl" "%" -o "%"`

`pandoc --citeproc --bibliography="$HOME/Zotero/zotero_main.bib" -t markdown_strict --csl="$HOME/Zotero/styles/american-medical-association.csl" "%" -o "%"`

[Shell script for converting a batch of *.md files into *.rst using pandoc.](https://gist.github.com/hugorodgerbrown/5317616)

<sup>1</sup>

<span class="csl-left-margin">1. </span><span
class="csl-right-inline">Tseng MH, Konrad M, Ding JJ, Lin SH. Clinical
and genetic approach to renal hypomagnesemia. *Biomedical Journal*.
2022;45(1):74-87.
doi:[10.1016/j.bj.2021.11.002](https://doi.org/10.1016/j.bj.2021.11.002)</span>
