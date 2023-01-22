---
title: pandoc in vim
date: "2023-01-22"
enableToc: false
---

> [!info]
>
> 🌱 來自: [[vim TODO]]

# pandoc in vim #🚧 施工中

`bibliography: bibliography.bib`
`csl: biomed-central.csl`

`pandoc --citeproc --bibliography="$HOME/Zotero/zotero_main.bib" -t markdown-citations --csl="$HOME/Zotero/styles/american-medical-association.csl" "%" -o "%"`

result

::: {#refs .references .csl-bib-body}
::: {#ref-ogara2015controversies .csl-entry}
[1. ]{.csl-left-margin}[O'Gara B, Fan E, Talmor DS. Controversies in the
Management of Severe ARDS: Optimal Ventilator Management and Use of
Rescue Therapies. *Semin Respir Crit Care Med*. 2015;36(6):823-834.
doi:[10.1055/s-0035-1564889](https://doi.org/10.1055/s-0035-1564889)]{.csl-right-inline}
:::
:::
