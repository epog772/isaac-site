# Relatório de aprendizagem

## Como cheguei ao resultado

Escolhi como tema uma wiki sobre o jogo *The Binding of Isaac: Rebirth*, porque é um jogo que jogo bastante. O site tem uma página inicial com a lista de personagens, uma página para cada personagem e uma para cada versão Tainted, com um botão para ir de uma para a outra.

Escrevi as páginas só com HTML e CSS, usando um único `style.css` para todo o site. Os links entre as páginas são relativos (por exemplo, `../style.css` nas páginas dentro de personagens/). As informações vêm da minha experiência com o jogo e de wikis que já existem.

Depois usei o Git:

1. Criei o repositório com `git init` e renomeei a branch para `main`.
2. Fiz commits separados por mudança, com mensagens claras.
3. Criei um repositório público no GitHub e liguei o meu repositório a ele com `git remote add origin`.
4. Enviei o código com `git push -u origin main`.

Por último, ativei o GitHub Pages em *Settings → Pages*, usando a branch `main` e a pasta raiz. O site ficou em `https://epog772.github.io/isaac-site/index.html` Testei o link em uma aba anônima para confirmar que é público.

**Problema que encontrei:** no primeiro commit, o Git deu o erro *Author identity unknown*. Resolvi configurando meu nome e e-mail com `git config --global user.name` e `git config --global user.email`.

## Ferramentas utilizadas e por quê

- **HTML e CSS:** HTML para o conteudo, CSS para estilização.
- **Git:** registra o histórico das mudanças do código em commits.
- **GitHub:** guarda o repositório na internet, onde o GitHub Pages lê os arquivos.
- **GitHub Pages:** publica o site direto do repositório, de graça.
- **Terminal:** usei para rodar os comandos do Git.
- **Editor de código:** neovim e vscodium.
- **Navegador:** usei para testar as páginas e abrir o site em aba anônima.

## Conceitos novos que aprendi

- **GitHub Pages:** serviço que transforma os arquivos de um repositório em um site público.
- **Site estático:** site feito de arquivos prontos (HTML e CSS), sem processamento no servidor.
- **Git** aprendi de uma maneira bem basica como usar o Git.
- **Markdown:** sintaxe simples para formatar texto, usada no `README.md` e neste relatório.