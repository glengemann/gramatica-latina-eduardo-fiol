# gramatica-latina-eduardo-fiol

## HTML

asciidoctor -d book 2da_declinacion.adoc

asciidoctor -a stylesheet=gramatica.css -a stylesdir=../asciidoctor-stylesheet-factory/stylesheets gramatica-latina-eduardo-fiol.adoc 

## PDF

asciidoctor-pdf -a pdf-style=default-theme.yml gramatica-latina-eduardo-fiol.adoc

## EPUB

$ asciidoctor-epub3 gramatica-latina-eduardo-fiol.adoc -D epub
