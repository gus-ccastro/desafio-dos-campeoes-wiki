# Guia completo de regras

Esta wiki é a referência detalhada do **Desafio dos Campeões**, um RPG de corridas disputado por meio de um bot de Telegram. Ela explica como funcionam as etapas, os cálculos, os atributos, a progressão e as probabilidades.

Para começar a jogar sem estudar as fórmulas, use `/tutorial` e `/ajuda` no bot. A wiki é opcional e serve para quem quer entender o jogo por dentro.

## Escopo desta edição

Esta edição descreve a temporada de **F2 atualmente implementada**. A revisão técnica desta primeira versão foi feita em 26/10/2026 e corresponde ao identificador de equilíbrio `2026-10-24.c`. As regras de F1 e de progressão para outras categorias ainda não estão definidas.

O texto descreve as regras vigentes e não cria regras novas. Uma ideia ou alteração ainda não aprovada pelo responsável pelo jogo não deve ser tratada como regra oficial.

## Comece por aqui

- [Fundamentos](fundamentos.md): dado, atributos, carro, score e privacidade das rolagens.
- [Temporada](temporada.md): calendário, grid, equipes, pontuação e NPCs.
- [Fim de semana](fim-de-semana.md): classificação, escolhas, corrida, ultrapassagens, pit stop e teste final.
- [Chuva e pneus](chuva-pneus.md): probabilidades, previsão, escolha de pneus e efeitos.
- [Progressão](progressao.md): XP, PP, PDC, PT, treino e evolução.
- [Críticos e fulminantes](criticos.md): quando são sorteados, como funcionam e os efeitos em cada fase.

## Princípios de leitura

**Score** é a soma usada para ordenar os pilotos durante as etapas e resolver ultrapassagens. **Pontos do campeonato** são atribuídos pela posição final. São valores diferentes.

Os dados da corrida são rolados publicamente no grupo. As contas detalhadas e o XP são enviados ao jogador em particular. Os testes de atributo também são rolados pelo jogador; no jogo, o bot pausa a resolução até receber o dado necessário.

Esta wiki pode ser atualizada para refletir decisões aprovadas. Mudanças de regra não são inferidas automaticamente de uma alteração técnica no bot.
