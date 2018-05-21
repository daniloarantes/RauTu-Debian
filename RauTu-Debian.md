# Converter Markdown para PDF

Instalar pacotes:

```bash
apt install texlive texlive-base pandoc
```

Para converter um arquivo criado com **markdown** para **pdf**, configurando as margens, utilize:

```bash
pandoc -s -V geometry:margin=1in -o documentation.pdf part01.md part02.md
```
