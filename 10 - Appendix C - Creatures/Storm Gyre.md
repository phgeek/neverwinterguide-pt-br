---
name: Storm Gyre
slug: storm-gyre-page
---

```Monster {.two-column}
name: Giro Tempestuoso
slug: storm-gyre
size: Médio
type: Elemental
alignment: Tipicamente Neutro
ac: 18 (natural)
hp: 135 (9d10 + 35)
speed: 0 m, voo 18 m (planar)
str: 10
dex: 20
con: 12
int: 5
wis: 14
cha: 5
senses: visão no escuro 18 m, Percepção passiva 12
damageResistances: elétrico, trovejante; concussão, cortante e perfurante de armas não-mágicas
damageImmunities: veneno
conditionImmunities: agarrado, caído, envenenado, exausto, impedido, inconsciente, paralisado, petrificado
languages: Auran
challenge: 8
token: StormGyreToken.png
image: StormGyre.jpg
traits:
  - name: Forma de Ar
    description: "O elemental pode entrar no espaço de uma criatura hostil e ficar parado nele. Ele pode se mover através de um espaço de até 2,5 centímetros de espessura sem se espremer."
actions:
  - name: Pancada
    description: "Ataque Corpo-a-Corpo com Arma: +8 para atingir, alcance 1,5 m, um alvo. Acerto: 19 (2d10 + 8) de dano trovejante, e o alvo deve ser bem-sucedido em um teste de resistência de Constituição CD 13 ou ficará atordoado até o final do próximo turno do Giro."
  - name: Condução
    description: "O Giro Tempestuoso escolhe um alvo a até 18 metros. Esse alvo, e todos os outros alvos a até 3 metros dele, devem fazer uma salvaguarda de Destreza CD 14. Todos os alvos sofrem 22 (5d8) de dano elétrico em caso de falha no teste, ou metade disso em caso de sucesso."
column-after: actions
column-after-property: Pancada
```