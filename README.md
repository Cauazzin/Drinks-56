# 🥤 Sucos 56

Landing page interativa para apresentação de bebidas com troca dinâmica de sabores e identidade visual.

Projeto focado em animações, manipulação de DOM e transições suaves com JavaScript puro.

---

## 🚀 Sobre o Projeto

O **Sucos 56** é uma página interativa que permite alternar entre diferentes sabores de bebida.

Cada sabor possui:

- Cor de fundo personalizada via CSS Variable
- Camadas visuais (efeito de profundidade)
- Transição animada
- Controle manual por botões (prev / next)

O objetivo do projeto é demonstrar domínio de:

- Estruturação HTML
- Animações CSS
- Manipulação de classes via JavaScript
- Lógica de controle de estado

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- CSS Variables
- Keyframes Animation

---

## 🎯 Funcionalidades

### 🔁 Alternância de Slides
Controle circular:

```js
active = active >= count - 1 ? 0 : active + 1

Permite navegação infinita entre os sabores.

🎨 Background Dinâmico

Cada .item define sua própria cor:

--background: #EA3D41;

Isso permite trocar o tema automaticamente ao mudar o slide.

✨ Animação de Entrada

Uso de:

@keyframes toActive

Para criar efeito suave na fruta e no título.

📂 Estrutura do Projeto
sucos-56/
│
├── index.html
├── style.css
├── script.js
└── img/
💻 Como Executar

Clone o repositório:

git clone https://github.com/seu-usuario/sucos-56.git

Abra:

index.html
🧠 Lógica do JavaScript

O controle do slider funciona através de:

Lista de elementos .item

Controle de índice active

Remoção da classe .active

Adição da classe ao novo item

Estrutura de navegação circular

Trecho principal:

active = active >= count -1 ? 0 : active + 1
📱 Pontos Técnicos Interessantes

Uso de clamp() para tipografia responsiva

Animação com @keyframes

Controle de estado simples e eficiente

Estrutura visual minimalista e moderna

📈 Melhorias Futuras

Autoplay automático

Indicadores de posição

Swipe para mobile

Animação mais elaborada entre transições

Deploy online

👨‍💻 Autor

Desenvolvido por Cauã Santos
