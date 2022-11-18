![html](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![html](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![html](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![html](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![html](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

# Manage Landing Page

Landing page produzida com HTML, CSS e JavaScript usando acessibilidade e tags semânticas. Para o slide, foi utilizado a biblioteca A11Y Slider.

## Guia

```
git clone https://github.com/felipe-miranda-marreiros/Manage-landing-page.git
```

```
npm run install
npm run dev
```

Ou simplesmente use Live Server.

## Estrutura

Tratando-se de uma landing page simples, a estrutura básica é composta por:

- Header
- Main[sections]
- Footer

Dessa forma, temos como apresentação:

- Menu Mobile
- Hero
- Description
- Testimonials
- Call To Action
- Footer

## Exemplos de atributos para acessibilidade

- aria-label (string) - forma de dar melhor signicado para determinada tag.
- aria-controls (string) - usamos para o botão do Menu Mobile como forma de avisar qual elemento estamos controlando (barra de navegação).
- aria-expanded (boolean) - usado para dizer se o Meu Mobile está ou não aberto.

## Composição

Para manter o layout e o design consistente, foi utilizado alguns princípios como:

- Design System - cores, fontes, espaçamento.
- Utility Classes - flex, grid e espaçamento entre elementos.
- BEM - forma de melhorar a legibilidade de classes CSS e melhor aproveitamento em manipulação de DOM.
- Mobile First.

## Referências

- [Youtube] Build a responsive website with HTML & CSS: https://www.youtube.com/watch?v=h3bTwCqX4ns
- [Frontend Mentor] Manage lading page: https://www.frontendmentor.io/challenges/manage-landing-page-SLXqC6P5

![screencapture-127-0-0-1-5500-2022-11-18-20_30_32](https://user-images.githubusercontent.com/91689754/202820149-1f989ad2-d4aa-474e-b162-03bf69049f15.png)
