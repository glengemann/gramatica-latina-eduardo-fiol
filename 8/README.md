# gramatica-latina-eduardo-fiol

## Asciidoc

a2x -f pdf gramatica-latina-eduardo-fiol.adoc

## Asciidoctor

## HTML

asciidoctor -d book 2da_declinacion.adoc

asciidoctor -a stylesheet=gramatica.css -a stylesdir=../asciidoctor-stylesheet-factory/stylesheets gramatica-latina-eduardo-fiol.adoc

## PDF

asciidoctor-pdf -a pdf-style=default-theme.yml gramatica-latina-eduardo-fiol.adoc -a toc

## EPUB

$ asciidoctor-epub3 gramatica-latina-eduardo-fiol.adoc -D epub
