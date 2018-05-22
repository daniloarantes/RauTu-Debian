# Converter Markdown para PDF

Instalar pacotes:

```bash
apt install texlive texlive-base pandoc
```

Para converter um arquivo criado com **markdown** para **pdf**, configurando as margens, utilize:

```bash
pandoc -s -V geometry:margin=1in -o documentation.pdf part01.md part02.md
```

# Git e GitHub

Criar repositório no GitHub e depois realizar o processo abaixo:

```bash
mkdir teste
cd teste
git init
echo "# Teste" > README.md
git add README.md
git commit -m "Descrição do Commit"
git remote add origin git@github.com:usuario/repositorio.git
git push -u origin master
```
