# ❤️ I Love You Forever

Um projeto web simples e elegante que utiliza **CSS Animations** e **JavaScript** para criar uma animação fluida de múltiplos textos flutuantes.

## 🚀 Como visualizar

Como este projeto é composto por um arquivo único (HTML, CSS e JS integrados), você não precisa de nenhum servidor ou compilador para rodá-lo:

1. Clone este repositório ou baixe o arquivo `index.html`.
2. Abra o arquivo `index.html` em qualquer navegador (Chrome, Firefox, Edge, etc.).

## 🛠️ Tecnologias Utilizadas

* **HTML5**: Estrutura da página.
* **CSS3**: Animações de *keyframes* e estilização visual.
* **JavaScript (ES6)**: Geração dinâmica de elementos para criar o efeito de movimento fluido.

## 💡 Como funciona

* **Dinâmica**: O script cria 100 instâncias do elemento de texto.
* **Animação**: Utilizamos `animation-delay` variável para cada elemento (calculado via CSS custom property `--i`), o que cria o efeito de movimento contínuo e orgânico.
* **Performance**: A animação utiliza propriedades otimizadas para garantir fluidez no navegador.

## ⚙️ Personalização

Você pode alterar o comportamento da animação diretamente no código:

* **Texto**: Procure a linha `word.textContent = 'I love you';` no `<script>` e altere para a mensagem desejada.
* **Quantidade**: Mude a constante `const N = 100;` para aumentar ou diminuir a quantidade de elementos flutuantes.
* **Estilo**: As cores e velocidades podem ser ajustadas dentro da tag `<style>` no cabeçalho do documento.

## Imagem do Projeto:
Acesse: https://i-love-you-beige-sigma.vercel.app/
<img src="img/imagem do projeto.png" alt="imagem do projeto">

---
*Criado com carinho.*
