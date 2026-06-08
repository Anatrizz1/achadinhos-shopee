# Landing Page - Guia Definitivo dos Achadinhos

Uma landing page de alta conversão desenvolvida para um cliente, com o objetivo de vender um infoproduto (e-book) focado no programa de afiliados da Shopee. O projeto foi estruturado com foco em velocidade, gatilhos de conversão e design focado no mobile.

## O Projeto

O layout foi pensado para fugir da estética de "site corporativo", adotando um visual minimalista e moderno, com texturas sutis e forte contraste no Call to Action (CTA). Toda a estrutura foi desenhada no conceito **Mobile First**, já que o tráfego principal do cliente vem de redes sociais como TikTok e Instagram.

### Principais Funcionalidades

* **Prova Social Dinâmica (Scroll-Triggered):** Sistema construído em Vanilla JS que ativa notificações simuladas de vendas assim que o usuário chega em determinada seção, utilizando a API `IntersectionObserver` para criar um efeito cascata.
* **Jornada Visual (Timeline):** Substituição de cards estáticos por uma linha do tempo vertical interativa para apresentar os módulos do curso.
* **FAQ Interativo (Accordion):** Seção de perguntas frequentes que expande e retrai respostas suavemente, mantendo a página limpa.
* **Layout Adaptativo:** Otimização para telas grandes (Desktop) com centralização de conteúdo e controle rigoroso de largura (Max-Width) para evitar a distorção dos elementos visuais.

## Tecnologias Utilizadas

Este projeto foi construído sem o uso de frameworks, garantindo máxima performance e carregamento instantâneo.

* **HTML5:** Estrutura semântica.
* **CSS3:** Animações CSS, Flexbox, Grid Layout e Media Queries.
* **JavaScript (Vanilla):** Manipulação do DOM para o acordeão do FAQ e controle de eventos de rolagem para animações de visibilidade.

## Deploy

[Clique](https://ebookachadinhos.netlify.app/)

Desenvolvido por @anacerqueira.dev
