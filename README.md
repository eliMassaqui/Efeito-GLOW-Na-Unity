# ✨ Efeito GLOW na Unity (Shader Graph + Bloom)

Este repositório mostra passo a passo como criar **efeitos de brilho (Glow)** em objetos usando **Shader Graph** com o **Bloom do Post Processing** na Unity.

---

## 🛠 Requisitos

- Unity com URP (Universal Render Pipeline)
- Shader Graph instalado
- Post Processing ativado
- Volume Global na cena

---

## 🌟 Passos para Criar o Efeito GLOW

### 1. Criar o Material com Emission
- Ative o **Emission** no Material.
- Aplique o material no objeto desejado.

### 2. Ativar o Post Processing Bloom
- Crie um **GameObject vazio** na cena chamado `PostProcessingVolume`.
- Adicione o componente **Volume**.
- Marque como **Is Global**.
- Adicione o efeito **Bloom** no Volume (pelo painel do Inspector).
- Ajuste os valores para que o brilho apareça corretamente.

---

## ⚙️ Ajustes Extras

- Altere a **cor** e **intensidade** do emission no material para variar o efeito.
- No Bloom, ajuste os valores de:
  - *Threshold* (limiar)
  - *Intensity* (intensidade)
  - *Scatter* (dispersão)

---

## 🧪 Exemplo Visual

![Glow Effect Preview](https://github.com/eliMassaqui/Efeito-GLOW-Na-Unity/blob/main/Captura%20de%20ecr%C3%A3%202025-06-12%20101710.png)

-
![](https://github.com/eliMassaqui/Efeito-GLOW-Na-Unity/blob/main/undefined_Unity_Glow_Effect_Steps.png)


> Demonstração do efeito Glow com cor verde aplicado a um objeto.

---

## 🎥 Vídeo Tutorial Recomendado de Code Monkey:
https://www.youtube.com/watch?v=bkPe1hxOmbI

---

Dica:
entao pra um objeto estar no modo GLOW basta ter ele com material no modo emission e ativar o pos processamento pra global

