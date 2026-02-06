# 🎧 Clone Landing Page Discord — Responsivo

Projeto desenvolvido como desafio da Trilha CSS da DIO com o objetivo de reproduzir a landing page do Discord a partir de um layout no [**Figma**](https://www.figma.com/design/NRBYrG5d4DSzObv7dpTqoM/Desafio-Responsividade---DIO?node-id=1-2&t=av7YmpOxTuk5ikZd-0).

O foco principal foi construção de layout responsivo, organização estrutural do CSS e aplicação de boas práticas sem dependência de frameworks.

---

## 🎯 Objetivo

- Reproduzir layout proposto no Figma
- Implementar responsividade para:
  - Desktop
  - Tablet
  - Mobile
- Trabalhar organização de CSS
- Aplicar estrutura semântica no HTML
- Utilizar Flexbox e Grid de forma combinada

---

## 🛠 Tecnologias Utilizadas

- HTML5 Semântico
- CSS3
- Flexbox
- CSS Grid
- Variáveis CSS (`:root`)
- Media Queries customizadas
- Font Awesome (ícones)

---

## 📐 Estratégia de Responsividade

O layout foi adaptado manualmente para três faixas principais:

- Desktop
- Tablet (768px – 1023px)
- Mobile (≤ 768px)

Foram aplicadas:

- Reorganização de layout com `flex-direction`
- Ajuste de grid
- Redimensionamento de textos
- Ocultação e exibição controlada de navegação
- Implementação de botão hamburguer visual para mobile

---

## 🎨 Decisões Técnicas

- Separação de responsabilidades:
  - `reset.css` → padronização base
  - `vars.css` → centralização de variáveis
  - `styles.css` → layout principal
  - `mediaqueries.css` → ajustes responsivos

- Uso consistente de unidades relativas (`rem`, `%`)
- Controle de espaçamento baseado no layout original
- Minimização de repetição de propriedades
- Uso combinado de Grid (macro layout) e Flexbox (componentes)

---

## 🖼 Preview

### Desktop

![Desktop](./prints-projeto/pc.png)

### Tablet

![Tablet](./prints-projeto/tablet.png)

### Mobile

![Mobile](./prints-projeto/celular.png)

---

## 📌 Observações

Projeto desenvolvido com finalidade educacional, com foco na consolidação de conceitos de layout responsivo e organização estrutural de CSS sem frameworks.
