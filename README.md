# github.io
Aula EBAC

Briefing
1. Disponibilizar um projeto no Github Pages
2. Criar um repositório com o nome do seu usuário + o sufixo .github.io
3. Habilitar o Github Pages em seu repositório, ou
4. Instalar em se gh-pages em seu projeto: yarn add -D gh-pages
5. No package.json, configurar homepage igual ao seu Github Pages,
ex.: https://cavalcantemmarcelo.github.io/style-guide/
6. Ainda no package.json, adicionar em scripts: "deploy": "gh-pages -d
build"

Conteúdo base
1. Code Together: https://github.com/cavalcantemmarcelo/style-guide
2. GitHub Pages: https://pages.github.com/

echo "# github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:dvcm/github.io.git
git push -u origin main
