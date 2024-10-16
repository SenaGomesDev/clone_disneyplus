# Clone DisneyPlus

## Visão Geral do Projeto

Este projeto é uma recriação fiel da página inicial da **Disney+**, replicando o design, a responsividade e a interatividade utilizando técnicas modernas de desenvolvimento web. O objetivo é demonstrar habilidades com HTML, CSS, JavaScript e ferramentas de automação para otimizar o fluxo de trabalho, garantindo alta performance e uma experiência do usuário de qualidade.

## Funcionalidades

- **Design Responsivo**: Adaptado para diferentes tamanhos de tela, garantindo uma excelente experiência em dispositivos móveis e desktops.
- **Conteúdo Dinâmico**: Utiliza JavaScript para manipular elementos interativos, como abas e seção de FAQ (perguntas frequentes) com accordion.
- **Otimização de Imagens**: As imagens são comprimidas para garantir tempos de carregamento mais rápidos, sem perder qualidade.
- **CSS e JavaScript Minificados**: O código é otimizado e minificado, resultando em arquivos menores e, consequentemente, um carregamento mais ágil.
- **Processo de Build Automatizado**: Com o Gulp, tarefas repetitivas, como compilação de SASS, minificação de JavaScript e otimização de imagens, são automatizadas.

## Ferramentas & Tecnologias Utilizadas

### Frontend:
- **HTML5**: Estruturação do conteúdo na página.
- **CSS3**: Estilização do layout, utilizando técnicas modernas como Flexbox e media queries para responsividade.
- **SASS**: Pré-processador CSS que permite modularização e manutenção mais fácil das folhas de estilo.
- **JavaScript**: Para adicionar interatividade e manipular eventos, como rolagem e alternância entre abas.

### Ferramentas de Build:
- **Gulp**: Automatizador de tarefas para otimizar o fluxo de desenvolvimento.
  - **gulp-sass**: Compila os arquivos `.scss` em CSS minificado.
  - **gulp-imagemin**: Otimiza as imagens para melhorar o desempenho.
  - **gulp-uglify**: Minifica os arquivos JavaScript.
