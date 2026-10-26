# Chuva e pneus

## Chance de chuva por pista

A tabela mostra a chance de chuva usada pelo jogo para cada GP. Os percentuais são parâmetros do jogo, não previsões meteorológicas reais.

| Pista | Chance de chuva |
|---|---:|
| Melbourne | 20% |
| Suzuka | 35% |
| Miami | 20% |
| Montreal | 30% |
| Mônaco | 25% |
| Barcelona | 10% |
| Spielberg | 25% |
| Silverstone | 30% |
| Spa | 40% |
| Hungaroring | 20% |
| Monza | 15% |
| Madri | 10% |
| Baku | 10% |
| Interlagos | 40% |
| Lusail | 3% |
| Yas Marina | 3% |

Uma ou duas tempestades são planejadas por temporada: 55% de chance de haver uma e 45% de haver duas. A pista é sorteada entre as que têm chance de tempestade. Em 35% dos casos a tempestade ocorre antes da largada e atrasa a prova; nos outros 65% encerra a corrida com bandeira vermelha no segundo trecho.

## Previsão e escolha

Antes da classificação, o jogador vê a chance de chuva da pista e três palpites de estrategistas. Cada palpite acerta o nível com probabilidade de 60%. O resultado real não é revelado antes da escolha do pneu.

A classificação e a corrida têm sorteios de clima relacionados entre si. Se a classificação estiver molhada, a chance de a corrida começar molhada é 65%. Se estiver seca, a probabilidade mostrada para o trecho de corrida é recalculada para manter a chance total associada à pista.

Na corrida, o clima é revelado aos poucos. Antes do segundo trecho, o jogador vê a chance atualizada e escolhe novamente o pneu.

## Níveis de clima

O jogo distingue pista seca, garoa, chuva moderada e chuva forte. A tempestade é uma condição especial de corrida: pode atrasar a largada ou provocar bandeira vermelha. As intensidades de chuva variam por pista.

## Efeitos dos pneus

O pneu de chuva em pista seca aplica −1 Velocidade, −1 Balanço e −3 de score.

| Chuva | Pneu seco: Velocidade / Balanço | Pneu seco: perda de score | Pneu de chuva: Velocidade / Balanço | Pneu de chuva: perda de score |
|---|---:|---:|---:|---:|
| Garoa | 0 / −1 | 2 | −1 / 0 | 0 |
| Moderada | −1 / −2 | 4 | 0 / 0 | 0 |
| Forte | −2 / −3 | 7 | −1 / −1 | 1 |

Em chuva forte, o pneu seco também tem 30% de chance de perder a etapa de desenvolvimento. Em pista seca, essa perda não acontece.

A Habilidade na chuva modifica cada conta de classificação ou desenvolvimento feita em etapa molhada:

`bônus de chuva = (Habilidade na chuva − 3) × 2`

O bônus pode ser negativo se o atributo estiver abaixo de 3.

## Correção no pit

Com duas paradas, o pneu errado para o segundo trecho é corrigido automaticamente no pit por um custo fixo de 2 pontos de score.

Com uma parada, o bot avalia o efeito do pneu errado. Se a soma das reduções de Velocidade e Balanço for de pelo menos 2 pontos, a parada é corrigida por uma parada extra automática com perda calculada pela fórmula do pit. Caso contrário, o piloto segue com o pneu escolhido e sofre seus efeitos.

As escolhas de pneu são feitas antes de conhecer o resultado real do clima. Isso é parte do risco estratégico da corrida.
