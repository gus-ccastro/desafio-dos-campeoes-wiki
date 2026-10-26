# Probabilidades e contas

## Um d10

Cada face do d10 tem probabilidade de **10%**. Em uma rolagem que usa críticos, o 1 natural tem 10% de chance de ativar a tabela de falhas e o 10 natural tem 10% de chance de ativar a tabela de fulminantes. Os outros oito resultados somam 80%.

No pit, a interpretação é diferente: o 1 zera a perda daquela parada. Não há tabela de falha crítica do pit.

## Chance de passar em um teste

Para um teste comum com bônus total `B` e CD `C`, a chance-base de passar é a quantidade de faces do d10 que satisfazem `B + d10 ≥ C`, dividida por 10:

`P(passar) = limitar((11 − (C − B)) / 10, 0, 1)`

O cálculo considera somente a comparação com a CD. Efeitos de críticos e regras especiais do teste são aplicados depois. Por isso, a chance real de obter o efeito desejado pode ser diferente.

| Bônus total | CD 10 | CD 12 | CD 15 |
|---:|---:|---:|---:|
| 0 | 10% | 0% | 0% |
| 3 | 40% | 20% | 0% |
| 6 | 70% | 50% | 20% |
| 9 | 100% | 80% | 50% |
| 12 | 100% | 100% | 80% |

### Exemplo de teste de PDC

Com Mecânica 4 e nível de equipe 5, o bônus de equipe é limitado a 4. O bônus total é 8. Contra CD 15, o dado precisa mostrar 7 ou mais: 7, 8, 9 ou 10. A chance-base de sucesso é `4/10 = 40%`. Um resultado natural 1 falha sempre em PDC, mas neste exemplo já não atingiria a CD.

### Exemplo de teste final

Com Resistência 3 e Durabilidade 4, sem modificadores, o bônus é 7. Contra CD 12, o piloto precisa de 5 ou mais, ou seja, a chance-base de atingir a CD é `6/10 = 60%`. O resultado final ainda pode ser alterado por falhas ou fulminantes.

## Oscilações de estratégia

A Agressiva e Tudo ou nada usam `piso((d10 − 5,5) × 2)`. As dez saídas são −9, −7, −5, −3, −1, +1, +3, +5, +7 e +9. Cada saída tem 10% de chance em uma oscilação. O valor esperado é zero por rolagem, mas a dispersão é alta. Na Agressiva são duas rolagens, uma por trecho.

## Previsões do clima

Cada um dos três estrategistas tem 60% de chance de acertar seu palpite. Como as três tentativas são independentes, a chance teórica de pelo menos um acerto é `1 − 0,4³ = 93,6%`. Isso não significa que a previsão indique o momento ou o efeito exato da chuva.

As chances de chuva por pista estão na página [Chuva e pneus](chuva-pneus.md#chance-de-chuva-por-pista). São parâmetros do jogo; não são probabilidades calculadas a partir do clima real.

## Duelos

Em um duelo, cada jogador rola seu próprio d10. Para cada lado, há 10% de chance de falha crítica, 10% de fulminante e 80% de não ativar esses dois gatilhos. Antes de considerar os críticos, a chance de passar depende de comparar os valores de ataque e defesa. Um empate favorece o defensor.

As chances de ganhar uma corrida ou uma disputa não podem ser obtidas apenas pela CD ou pelo d10: também dependem dos atributos, do carro, dos pneus, do score e das tabelas de críticos.
