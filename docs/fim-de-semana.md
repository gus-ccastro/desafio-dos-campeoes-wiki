# Fim de semana de corrida

## Ordem das fases

1. **Classificação**: cada jogador escolhe estratégia de classificação, ação de treino e pneu; também rola o dado do treino. O dado de classificação determina o grid.
2. **Escolha da corrida**: após a classificação, cada jogador escolhe estratégia de corrida e pneu para o primeiro trecho.
3. **Largada**: cada piloto rola o d10 de largada. As ultrapassagens desta fase são automáticas.
4. **Desenvolvimento do primeiro trecho**: cada piloto rola seu d10; o trecho altera score, não a ordem.
5. **Duelo do primeiro trecho**: quem ficou à frente pelo score passa. Quando atacante e defensor são jogadores, ambos rolam no grupo.
6. **Pit stop**: a fase inclui as rolagens das paradas e a escolha do pneu para o segundo trecho.
7. **Desenvolvimento do segundo trecho** e **duelo do segundo trecho**: seguem as mesmas regras do primeiro.
8. **Teste final**: cada piloto rola para verificar se o carro e o piloto completam a corrida. As ultrapassagens finais são automáticas.

Após cada etapa, o grupo recebe o grid atualizado, exceto após o teste final. O grupo vê os dados, os resultados e a ordem. A conta individual fica no privado.

## Classificação

A base da conta é:

`score de classificação = Técnica + Velocidade + Balanço + d10 + modificadores`

Se a classificação estiver molhada, soma-se também o bônus de Habilidade na chuva: `(Chu − 3) × 2`. O pneu pode alterar Velocidade, Balanço e score. O efeito da ação de treino pode entrar como bônus temporário.

O resultado da estratégia de classificação é sorteado pelo motor para opções oscilantes. Essa oscilação é exibida apenas ao jogador no privado. Seus efeitos de corrida entram na largada e são temporários.

## Largada

A conta-base é:

`score acrescentado na largada = Reflexos + Velocidade + d10 + modificadores temporários`

O modificador de treino de largada também se aplica quando houver. Falha crítica ou fulminante natural pode acrescentar um resultado da tabela correspondente. As ultrapassagens na largada são automáticas e não geram duelo entre jogadores.

## Desenvolvimento dos trechos

A conta-base de cada trecho é:

`score acrescentado = Técnica + Concentração + Balanço + d10 + estratégia + bônus de chuva + outros efeitos`

Em trecho molhado, o bônus de Habilidade na chuva é `(Chu − 3) × 2`. A estratégia Agressiva acrescenta uma oscilação independente em cada trecho. O valor é `piso((d10 − 5,5) × 2)`; as dez saídas possíveis são −9, −7, −5, −3, −1, +1, +3, +5, +7 e +9. O resultado aparece no privado.

O desenvolvimento não altera diretamente a ordem. Depois dele, o score é usado para decidir quem pode tentar ultrapassar no duelo que fecha o trecho.

## Duelos entre jogadores

Um duelo só ocorre quando o piloto de trás tem score maior que o piloto à frente e os dois são jogadores. Contra NPCs a ultrapassagem é automática.

`Ataque = Reflexos + Velocidade + Coragem + d10 + bônus de diferença + modificador crítico`

`Defesa = Técnica + Balanço + Concentração + d10 + modificador crítico`

O atacante passa se o ataque for **maior** que a defesa. Empate significa que o defensor segura a posição. Um crítico pode impor passar ou segurar; se os efeitos de crítico dos dois lados se opuserem, eles se anulam e a conta decide.

O bônus de diferença usa o score do atacante menos o score do defensor, dividido pelo fator da pista e arredondado para baixo. O bônus máximo é +3.

| Perfil vigente da pista | Divisor de score |
|---|---:|
| Favorece ataque | 2,0 |
| Neutra | 2,5 |
| Favorece defesa | 3,0 |

O valor de ataque ou defesa da pista determina o perfil usado. Os duelos não alteram score por si só. Pontos de score concedidos por um crítico entram depois da rodada de duelos para não criarem ultrapassagens em cascata.

## Pit stop

Cada parada usa um d10. Para o jogador, um resultado natural **1** zera a perda daquela parada e não aciona uma tabela de crítico. Nos resultados de **2 a 10**, a perda básica é:

`perda por parada = piso(máximo(0, 6 + d10 − 0,5 × nível da equipe))`

A perda final pode receber ajustes de estratégia, treino e críticos ocorridos em outras etapas. Quem faz duas paradas usa uma rolagem para cada parada. Os figurantes não recebem a parada perfeita de 1 e seguem a fórmula. A conta detalhada não é narrada no grupo.

Estratégias de uma parada podem pagar uma perda de pneus no segundo trecho conforme o desgaste da pista. Estratégias de duas paradas recebem bônus de pneu novo. Consulte [estratégias e desgaste](#estrategias-de-corrida) e [chuva e pneus](chuva-pneus.md) para as condições especiais.

## Teste final

A conta é:

`total = Resistência + Durabilidade + modificadores + d10`

A CD da F2 é **12**. Se o total for menor, o piloto perde 5 pontos de score. Um 1 natural aciona a tabela de falhas do teste final; a entrada sorteada pode resultar em abandono. Um 10 natural aciona a tabela de fulminantes para pilotos que podem recebê-los. O 10 não impede a penalidade de −5 se o total ainda ficar abaixo da CD.

Depois do teste, as ultrapassagens são automáticas. O resultado final determina os pontos do campeonato.

## Estratégias de corrida

O desgaste da pista altera o bônus de pneu novo ou o custo de uma parada única.

| Estratégia | Paradas | Efeito no primeiro trecho | Efeito no segundo trecho | Ajuste efetivo de Durabilidade final | Ajuste por parada |
|---|---:|---:|---:|---:|---:|
| Conservadora | 1 | — | — | −1 | — |
| Ataque inicial | 1 | +5 score | custo conforme desgaste: −3, −5 ou −7 | −1 | — |
| Escalonada | 2 | — | bônus de pneu novo conforme desgaste: +8, +11 ou +15 | +1 | — |
| Agressiva | 2 | +2 score e oscilação | oscilação independente | 0 líquido | +2 score perdido |

Na Agressiva, o ajuste de Durabilidade da estratégia de duas paradas (+1) é compensado pelo ajuste da própria estratégia (−1). A oscilação de cada trecho é explicada acima. As estratégias Tudo ou nada e Agressiva são processadas pelo motor e seu resultado é privado.

### Desgaste por GP

| Desgaste | Bônus do pneu novo na Escalonada | Custo adicional no 2º trecho da Ataque inicial |
|---|---:|---:|
| Baixo | +8 | −3 |
| Médio | +11 | −5 |
| Alto | +15 | −7 |

## Estratégias de classificação

| Opção | Efeito na classificação | Efeito na corrida |
|---|---:|---|
| Volta limpa | +1 | Durabilidade −1 no teste final |
| Ataque total | +3 | Durabilidade −4 e Velocidade −1 |
| Acerto de balanço | −1 | Balanço +1 |
| Poupar pneus | −2 | Perde 2 pontos a menos por parada no pit |
| Simulação de corrida | −2 | Concentração +1 e Resistência +2 |
| Tudo ou nada | oscilação entre −9 e +9, em passos ímpares | Velocidade −1 |

O efeito de corrida da estratégia de classificação vale só para aquela corrida. Para Tudo ou nada, o motor calcula `piso((d10 − 5,5) × 2)` e mostra a conta no privado.
