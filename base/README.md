# A base do $\LaTeX$

A base do $\LaTeX$ consiste em utilizar arquivos organizados da seguinte forma:

- **main.tex** – Arquivo principal do documento. Contém a estrutura do texto, chamadas para pacotes, inclusão de seções e configuração geral do layout.

- **packs.sty** – Arquivo dedicado à importação e configuração dos pacotes $\LaTeX$ usados no projeto, facilitando a organização e manutenção do código.

- **bibliography.bib** – Arquivo no formato BibTeX que reúne todas as referências bibliográficas citadas no documento, permitindo gerenciamento automático das citações e formatação consistente.

Essa separação mantém o projeto modular e facilita futuras edições ou reutilização de conteúdo.

OBS.: se o documento for dividido em seções, pode-se adicionar um arquivo.tex dedicado a cada uma e as importar diretamente no main.