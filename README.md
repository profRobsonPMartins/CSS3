# Guia Didático CSS3 📚

[![CSS](https://img.shields.io/badge/CSS-3-blue?style=flat&logo=css3)](https://link-para-mais-informacoes)

## Introdução 🚀

👨‍🏫 Bem-vindo ao Guia Didático CSS3! Este documento oferece uma visão geral dos conceitos fundamentais e recursos avançados do CSS3, a versão mais recente da linguagem de estilo utilizada para estilizar páginas web.💻

## Seletores Básicos 🧐

Os seletores são usados para aplicar estilos a elementos HTML específicos.

```css
/* Seletor de tag */
body {
    font-family: 'Arial', sans-serif;
}

/* Seletor de classe */
.button {
    background-color: #3498db;
    color: #ffffff;
}
```

## Propriedades Principais

### Cores

O CSS3 oferece diversas formas de especificar cores.

```css
/* Usando nome da cor */
h1 {
    color: red;
}

/* Usando código hexadecimal */
p {
    background-color: #f2f2f2;
}

/* Usando RGB */
a {
    border: 1px solid rgb(255, 0, 0);
}
```

### Box Model

O modelo de caixa é fundamental para entender o layout.

```css
/* Definindo margens, bordas e preenchimento */
.box {
    margin: 10px;
    border: 1px solid #333;
    padding: 20px;
}
```

### Flexbox

Flexbox é um modelo de layout mais eficiente.

```css
/* Usando Flexbox para alinhar itens horizontalmente */
.container {
    display: flex;
    justify-content: space-between;
}
```

## Media Queries

Media queries permitem estilos responsivos para diferentes dispositivos.

```css
/* Estilos para dispositivos pequenos (ex: smartphones) */
@media only screen and (max-width: 600px) {
    body {
        font-size: 14px;
    }
}
```

## Transições e Animações

Adicione transições e animações para melhorar a experiência do usuário.

```css
/* Adicionando uma transição suave */
.button {
    transition: background-color 0.3s ease;
}

/* Criando uma animação de balanço */
@keyframes swing {
    0% { transform: rotate(0deg); }
    50% { transform: rotate(20deg); }
    100% { transform: rotate(0deg); }
}

.element {
    animation: swing 2s infinite;
}
```

## Conclusão

O CSS3 oferece uma variedade de recursos para criar layouts atraentes e responsivos. Ao entender os seletores, propriedades principais e recursos avançados, você estará pronto para estilizar suas páginas web de maneira eficaz.

## Recursos Adicionais

- [W3Schools CSS Tutorial](https://www.w3schools.com/css/)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
```

Este é um guia básico para começar com CSS3. Sinta-se à vontade para personalizar e expandir conforme necessário para atender às suas necessidades específicas.
