# 🏁 Dice Racing Game

Simulador de corrida baseado em turnos desenvolvido em Node.js, onde dois personagens disputam uma corrida utilizando atributos e sorte.

---

## 🎮 Sobre o projeto

Neste jogo, dois personagens competem em uma corrida de 5 rodadas.  
A cada rodada, um tipo de pista é sorteado e os jogadores disputam com base em seus atributos e na rolagem de dados 🎲.

---

## 🧠 Mecânicas do jogo

### 👥 Jogadores
- O jogo recebe dois personagens
- Cada personagem possui atributos:
  - Velocidade
  - Manobrabilidade
  - Poder
  - Pontuação

---

### 🛣️ Pistas

A corrida possui **5 rodadas**, e em cada rodada é sorteado um tipo de pista:

#### 🟦 Reta
- Rola um dado de 6 lados 🎲
- Soma com **VELOCIDADE**
- Quem tiver o maior valor ganha **+1 ponto**

#### 🟨 Curva
- Rola um dado de 6 lados 🎲
- Soma com **MANOBRABILIDADE**
- Quem tiver o maior valor ganha **+1 ponto**

#### 🟥 Confronto
- Rola um dado de 6 lados 🎲
- Soma com **PODER**
- O resultado define quem vence o confronto

---

## 💥 Regras de Confronto

Quando ocorre um confronto:

### 🥊 Resultado
- O jogador com maior poder vence
- Em caso de empate, ninguém perde pontos

### 🎯 Penalidades (aleatórias)
Após o confronto, é sorteado:

- 🐢 **Casco** → jogador perde **-1 ponto**
- 💣 **Bomba** → jogador perde **-2 pontos**

### ⚡ Bônus
- O vencedor pode ganhar um **turbo (+1 ponto)** aleatoriamente

---

## 🚫 Regras adicionais

- Nenhum jogador pode ter pontuação negativa (mínimo = 0)

---

## 🏆 Condição de vitória

- Ao final das 5 rodadas
- Vence quem tiver **mais pontos**
