# ✨ Efeito GLOW na Unity (Shader Graph + Bloom)

Este repositório mostra passo a passo como criar **efeitos de brilho (Glow)** em objetos usando **Shader Graph** com o **Bloom do Post Processing** na Unity.

---

## 🛠 Requisitos

- Unity com URP (Universal Render Pipeline)
- Shader Graph instalado
- Post Processing ativado
- Câmera com HDR ativado
- Volume Global na cena

---

## 🌟 Passos para Criar o Efeito GLOW

### 1. Criar o Shader com Emission
- Abra o Shader Graph.
- Use um **Color** multiplicado por um **Float** para controlar a intensidade.
- Conecte no **Emission** do shader.
- Salve e crie um material com esse shader.
- Aplique o material no objeto desejado.

### 2. Ativar o Post Processing Bloom
- Crie um **GameObject vazio** na cena chamado `PostProcessingVolume`.
- Adicione o componente **Volume**.
- Marque como **Is Global**.
- Adicione o efeito **Bloom** no Volume (pelo painel do Inspector).
- Ajuste os valores para que o brilho apareça corretamente.

### 3. Ativar HDR na Câmera
- Selecione a Câmera principal.
- No componente **Camera**, ative a opção **HDR**.

---

## ⚙️ Ajustes Extras

- Altere a **cor** e **intensidade** do emission no material para variar o efeito.
- No Bloom, ajuste os valores de:
  - *Threshold* (limiar)
  - *Intensity* (intensidade)
  - *Scatter* (dispersão)

---

## 🧪 Exemplo Visual

![](./demo.gif)

> Demonstração do efeito Glow com cor verde aplicado a um objeto.

---

## 🎥 Vídeo Tutorial Recomendado de Code Monkey:
https://www.youtube.com/watch?v=bkPe1hxOmbI

---

