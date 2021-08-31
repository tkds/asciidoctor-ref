# asciidoctor-ref

## Install

```
gem install asciidoctor
gem install --pre asciidoctor-pdf
gem install coderay
gem install asciidoctor-pdf-cjk

```

## HTML

```
asciidoctor sample.adoc
```

## PDF

```
asciidoctor-pdf -a scripts=cjk -a pdf-theme=default-with-fallback-font sample.adoc
```
