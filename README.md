# 🎨 Repositório de Soluções CSS Battle 🏆

Este repositório contém minhas soluções para os desafios da plataforma [CSS Battle](https://cssbattle.dev/).

O objetivo principal é recriar imagens-alvo usando o mínimo de código CSS possível (obtendo o menor *score* de caracteres) e alcançar a maior precisão (*match*).

---

## 🚀 Como está Organizado

Cada desafio resolvido fica em uma pasta separada, nomeada pelo número ou nome do Battle (ex: `001-simply-square`, `003-push-button`, etc.).

Dentro de cada pasta, você encontrará:

* **`solution.css`** (ou `index.html` com o `<style>`): O código CSS otimizado e a estrutura HTML minimalista.
* **`README.md` (local):** Explicações sobre as técnicas avançadas usadas para otimização (se necessário).

---

## ✨ Técnicas de Otimização e Truques de CSS

Ao resolver esses desafios, foco em usar truques avançados para reduzir a contagem de caracteres:

* **Redução do HTML:** Uso de múltiplos elementos (como `<p>` ou `<a>`) em vez de múltiplos `<div>`.
* **Propriedade `border`:** Criação de triângulos e outras formas complexas usando apenas as bordas transparentes de elementos `width: 0; height: 0;`.
* **Aproveitamento de `box-shadow`:** Para criar formas adicionais sem adicionar mais elementos HTML.
* **Otimização do `margin`:** Uso de `margin: -8px;` no `body` ou seletor universal (`*`) para remover o margin padrão do navegador.
* **Shorthands:** Uso máximo de atalhos (como `margin: 10px 20px;`) e códigos hexadecimais curtos (ex: `#fff`).

---

## 🛠️ Ferramentas

* **[CSS Battle Official Site](https://cssbattle.dev/):** A plataforma onde os desafios são jogados.
* **[CSS Minifier / Compressor](https://cssminifier.com/):** Usado para verificar a contagem de caracteres e otimizar o código (embora a otimização manual seja o foco principal).

---

Feito com 💙 por Pedro Augusto.
