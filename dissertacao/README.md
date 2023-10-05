[![GitHub license](https://img.shields.io/badge/license-CC0-blue.svg)](https://raw.githubusercontent.com/emersonmello/modelos-latex/master/LICENSE)

# Modelo de dissertacao em LaTeX para a Universidade Federal de Santa Catarina

Adaptação do documento abnTeX2: Modelo de Trabalho Acadêmico para ficar de acordo com o "Livro digital para elaboração de trabalhos academicos" fornecido pela biblioteca da UNIVALI

## Compilando o projeto localmente e não no Overleaf

Este projeto faz uso do pacote glossaries. Se for usar uma instalação local do LaTeX para compilar, e não no [Overleaf](https://www.overleaf.com), então é necessário que tenha o arquivo [`.latexmkrc`](.latexmkrc) dentro diretório deste projeto e use o comando abaixo:
```bash
latexmk -outdir=out -pdf monografia.tex
```
A extensão [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop) do Visual Studio Code usa por padrão o latexmk para compilar.

## Disclaimer

:warning: Este modelo ainda não está totalmente adequado ao livro `Livro digital para elaboração de trabalhos academicos`, fornecido pela biblioteca da UNIVALI. Use por sua conta em risco e fique a vontade para sugerir melhorias ou contribuir para o repositório. 
