# Contribuir com a wiki

A wiki descreve as regras aprovadas e o comportamento atual do jogo. Propostas de mudança devem ser identificadas como propostas; não apresente como regra vigente algo que ainda não foi decidido.

## Fluxo

1. Abra uma issue ou pull request com o tema e as páginas afetadas.
2. Para mudança de regra, aguarde a decisão do responsável pelo jogo antes de redigir a versão normativa.
3. Mantenha o tutorial e `/ajuda` curtos. Esta wiki é a referência de estudo detalhada.
4. Abra um pull request para `main`. Não publique por push direto.
5. O CI precisa concluir `build-docs` com sucesso. O merge é feito pelo responsável.

A wiki não deve inferir regras aprovadas apenas a partir de uma alteração técnica no bot. Quando houver divergência entre texto antigo e implementação, registre a questão para revisão; não transforme uma suposição em regra.

## Estilo e precisão

- Escreva em português brasileiro e explique os termos antes de usar abreviações.
- Mostre fórmulas com variáveis definidas e arredondamentos explicitados.
- Diferencie probabilidade teórica de resultado observado em simulação.
- Não inclua tokens, logs privados, dados de jogadores, caminhos internos ou conteúdo do repositório privado.
- Confira cálculos, nomes e efeitos nas regras aprovadas antes de alterar páginas públicas.

## Validar localmente

```bash
python -m pip install -r requirements-docs.txt
zensical build --clean --strict
```
