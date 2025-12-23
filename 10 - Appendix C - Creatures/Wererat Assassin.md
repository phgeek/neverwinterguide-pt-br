---
name: Wererat Assassin
slug: wererat-assassin-page
---

```Monster {.two-column}
name: Homem-rato Assassino
slug: wererat-assassin
size: Médio
type: Humanoide
alignment: Qualquer Alinhamento
ac: 16 (Cota de Malhas)
hp: 75 (9d10 + 26)
speed: 9 m
str: 11
dex: 18
con: 14
int: 11
wis: 11
cha: 12
saves: Des +7, Int +3
skills: Percepção +3, Furtividade +7
damageImmunities: concussão, cortante e perfurante de armas não-mágicas que não sejam de prata
senses: visão no escuro 18 m, Percepção passiva 13
languages: Comum, Gíria de Ladrão (não consegue falar em forma de rato)
challenge: 4
environments: Urbano
traits:
  - name: Faro Aguçado
    description: O homem-rato tem vantagem em testes de Sabedoria (Percepção) relacionados ao olfato.
actions:
  - name: Ataques Múltiplos (Formas Humanoide ou Híbrida Apenas)
    description: "O homem-rato realiza 3 ataques com sua adaga."
  - name: Adaga (Formas Humanoide ou Híbrida Apenas)
    description: "Ataque Corpo-a-Corpo com Arma: +6 para atingir, alcance 1,5 m, um alvo. Acerto: 6 (1d4 + 4) de dano perfurante."
  - name: Besta de Mão (Formas Humanoide ou Híbrida Apenas)
    description: "Ataque à Distância com Arma: +6 para atingir, distância 9/36 m, um alvo. Acerto: 7 (1d6 + 4) de dano perfurante."
  - name: Mordida (Formas de Rato ou Híbrida Apenas)
    description: "Ataque Corpo-a-Corpo com Arma: +6 para atingir, alcance 1,5 m, um alvo. Acerto: 6 (1d4 + 4) de dano perfurante. Se o alvo for um humanoide, ele deve ser bem sucedido num teste de resistência de Constituição CD 11 ou será amaldiçoado com a licantropia do homem-rato."
bonus-actions:
  - name: Metamorfo
    description: "O homem-rato pode usar sua ação para se metamorfosear em um híbrido humanoide-rato ou em um rato gigante, ou de volta a sua forma verdadeira, que é humanoide. Suas estatísticas, diferentes do seu tamanho, são as mesmas em cada forma. Qualquer equipamento que esteja vestindo ou carregando não é transformado. Ele reverte a sua forma verdadeira se morrer."
reactions:
  - name: Esquiva Sobrenatural
    description: "O homem-rato reduz pela metade o dano causado a ele proveniente de um ataque. Ele deve estar apto a ver o atacante."
image: WereratAssassin.jpg
token: WereratAssassinToken.png
column-after: actions
```
