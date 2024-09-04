#  My Linktree - (1_Project_Web)

**Autor:** Brendon Santos

Este projeto foi desenvolvido como parte de um estudo inicial no desenvolvimento web, utilizando de forma básica as tecnologias HTML, CSS e JavaScript. O projeto consiste em uma página estilo **Linktree**, amplamente utilizada em redes sociais como Instagram para compartilhar múltiplos links em um único local.

## Visão Geral

O **1_Project_Web** é uma aplicação simples, porém eficaz, que demonstra os fundamentos do desenvolvimento web. A página permite que os usuários compartilhem vários links de forma organizada e acessível, em um formato que é facilmente reconhecido e utilizado nas redes sociais.

### Funcionalidades

- **Links Personalizados**: A página permite que você adicione vários links, cada um com seu próprio texto e URL.
- **Design Responsivo**: A página foi construída com um layout simples, mas responsivo, garantindo que os links sejam exibidos corretamente em dispositivos móveis e desktops.
- **Estilo Personalizado**: Estilo básico, mas funcional, utilizando CSS para estilizar os elementos da página.

## Estrutura do Projeto

A estrutura do projeto é bastante simples, refletindo o objetivo de aprendizado inicial:
    ```plaintext
    
               1_Project_Web/
               ├── index.html
               ├── styles.css
               └── script.js

- **index.html**: Este arquivo contém a estrutura básica da página, utilizando elementos HTML para criar os blocos de links.

- **styles.css**: Contém as definições de estilo para a página. O CSS foi utilizado para definir a aparência dos links, espaçamento, e cores.

- **script.js**: Contém o código JavaScript utilizado para adicionar interatividade à página, como animações simples ao passar o mouse sobre os links.

## Código Importante
### HTML
No arquivo `index.html`, a estrutura básica da página é definida:
    ```html
    
          <div class="container">
          <h1>Brendon Santos</h1>
          <a href="https://github.com/BrendonSant" target="_blank">GitHub</a>
          <a href="https://www.linkedin.com/in/brendon-santos-2341234" target="_blank">LinkedIn</a>
          <a href="https://www.instagram.com/brendonsant" target="_blank">Instagram</a>
          </div>
Este bloco de código cria um contêiner centralizado que contém um título e uma lista de links para redes sociais.

### CSS
No arquivo styles.css, o estilo básico da página é definido, incluindo a centralização dos elementos e o estilo dos links:
    ```css
    
        .container {
          text-align: center;
          margin-top: 50px;
        }
        
        a {
          display: block;
          margin: 10px 0;
          text-decoration: none;
          color: #fff;
          background-color: #333;
          padding: 10px;
          border-radius: 5px;
        }
        
        a:hover {
          background-color: #555;
        }

Este código CSS estiliza os links, criando botões que mudam de cor ao passar o mouse.

### JavaScript
O arquivo `script.js` contém o JavaScript básico para adicionar alguma interatividade ou animações simples, se necessário:
    ```javascript

          document.querySelectorAll('a').forEach(link => {
          link.addEventListener('mouseover', () => {
            link.style.transform = 'scale(1.05)';
          });
        
          link.addEventListener('mouseout', () => {
            link.style.transform = 'scale(1)';
          });
        });

Este trecho de código adiciona um efeito de escala quando o usuário passa o mouse sobre os links.

## Como Executar o Projeto

1.Clone o repositório:
    ```bash
    
          git clone https://github.com/BrendonSant/1_Project_Web.git
          
2.Abra o arquivo `index.html` em um navegador para visualizar a página.

## Conclusão

Este projeto foi uma excelente introdução ao desenvolvimento web, proporcionando uma oportunidade prática de aplicar conceitos básicos de HTML, CSS e JavaScript. A criação de uma página estilo Linktree não só reforçou os fundamentos de web design, mas também destacou a importância de design responsivo e interatividade.
