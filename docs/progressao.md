# Progressão e ações entre GPs

## XP e PP

Os ganhos de XP vêm da participação na classificação, da posição na corrida e de eventuais bônus. A tabela está em [temporada](temporada.md#experiencia-por-gp). A cada **10 XP**, o jogador recebe **1 PP**. O saldo e os detalhes do ganho são enviados apenas no privado.

O jogador escolhe quando evoluir pelo comando `/evoluir`, também no privado. Cada aumento permanente custa PP conforme o atributo e o nível atual. O custo é arredondado para baixo e tem mínimo de 1 PP.

| Atributos | Fator por nível atual |
|---|---:|
| Reflexos e Técnica | 2 |
| Resistência, Coragem e Concentração | 1,5 |
| Mecânica, Recursos e Habilidade na chuva | 1 |

Exemplo: aumentar Técnica de 3 para 4 custa `piso(2 × 3) = 6 PP`. A evolução só é oferecida se o jogador puder pagar e se respeitar o teto da F2.

## PDC e evolução do carro

PDC é usado para evoluir Velocidade, Balanço ou Durabilidade do carro. O custo é:

`custo em PDC = máximo(1, fator × nível atual)`

| Característica do carro | Fator |
|---|---:|
| Velocidade | 2 |
| Balanço | 2 |
| Durabilidade | 1 |

O teto de carro da F2 é 5. A compra deduz o saldo e aplica o aumento permanentemente.

## Testes de PDC

A cada GP há dois testes de Mecânica e um de Recursos. Cada teste usa um d10 rolado pelo jogador, CD 15 e bônus de equipe limitado a +4:

`total = atributo + mínimo(nível da equipe, 4) + d10`

O teste bem-sucedido concede 1 PDC. Um resultado natural 1 sempre falha. Um resultado natural 10 não concede PDC extra por si só. A cada oito falhas acumuladas na temporada, o jogador recebe 1 PDC de consolo e o contador de falhas volta a zero. O contador é reiniciado na renovação da temporada.

## Ações de treino

Entre GPs, o jogador escolhe uma ação e rola seu próprio d10. O efeito temporário vale só para a próxima corrida. O atributo-alvo de cada ação é:

| Ação | Alvo |
|---|---|
| Simulador | Técnica |
| Treino de largada | Reflexos |
| Preparação física | Resistência |
| Mentalização | Concentração |
| Pilotagem agressiva | Coragem |
| Reunião de engenharia | Balanço do carro |
| Imprensa | Recursos, que reduz perdas no pit |
| Treino na chuva | Habilidade na chuva |

Um resultado baixo pode gerar penalidade temporária; resultado neutro pode conceder XP em vez de bônus de corrida; resultado alto pode conceder bônus e pontos de treino (PT). As ações Simulador, Reunião de engenharia e Mentalização têm efeitos de corrida reduzidos porque alcançam várias etapas ou têm mais alcance. As tabelas de críticos de treino são consultadas com 1 e 10 naturais.

## PT e aumentos permanentes

PT positivos acumulam por atributo. A cada **30 PT**, Coragem, Concentração, Resistência, Mecânica, Recursos ou Habilidade na chuva recebem +1 permanente. O excedente permanece acumulado.

Técnica e Reflexos não viram aumento permanente por PT. Nesses atributos, **3 PT convertem em 1 XP**. Efeitos negativos não removem PT já acumulado.

## O que é temporário

Bônus e penalidades de treino, clima, críticos, coletiva ou bastidores que são definidos para uma corrida não se tornam evolução permanente, salvo quando a própria regra concede PP, PDC, PT ou aumento permanente. Os ajustes de atributos e carro restritos a uma prova são restaurados ao fim dela.
