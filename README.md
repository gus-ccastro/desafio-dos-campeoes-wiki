# Desafio dos Campeões — Wiki de regras

Referência detalhada das regras, mecânicas, cálculos e probabilidades do RPG de corridas no Telegram. O tutorial e o comando `/ajuda` continuam sendo o caminho rápido para jogar; esta wiki é para quem quer estudar o funcionamento em profundidade.

A wiki é construída com Zensical e está preparada para o GitHub Pages. Antes da primeira publicação, habilite **Settings → Pages → Build and deployment → Source: GitHub Actions** neste repositório. O código do bot e os documentos internos ficam em outro repositório e não são copiados para cá.

- [Repositório público da wiki](https://github.com/gus-ccastro/desafio-dos-campeoes-wiki)
- [Contribuir com correções ou propostas](CONTRIBUTING.md)

## Desenvolvimento local

Requer Python 3.10 ou superior.

```bash
python -m pip install -r requirements-docs.txt
zensical serve
```

Para validar o site como no CI:

```bash
zensical build --clean --strict
```

As alterações entram por pull request. O merge na `main` dispara a publicação do site depois que o GitHub Pages estiver configurado; a publicação da wiki não executa nem altera o deploy do bot.
