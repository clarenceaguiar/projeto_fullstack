# Full Stack Open - Universidade de Helsinki 🚀

Este repositório foi criado para armazenar as resoluções dos exercícios e projetos propostos ao longo do curso **Full Stack Open**, oferecido pela Universidade de Helsinki. O curso aborda o desenvolvimento web moderno com JavaScript, focado em construir aplicações Single Page Applications (SPA) robustas utilizando React, Node.js, Express, MongoDB, entre outras tecnologias de ponta.

---

## 📂 Estrutura do Repositório

O projeto é organizado em pastas correspondentes a cada parte do curso, conforme as diretrizes de submissão:

- `part0/` - Fundamentos das Aplicações Web (Exercícios de Diagramas e Fluxos HTTP)

---

## 🛠️ Parte 0: Fundamentos das Aplicações Web

Nesta seção inicial do curso, o foco foi compreender o funcionamento interno da Web, o ciclo de requisição e resposta HTTP, a manipulação do DOM pelo JavaScript e a diferença crucial de arquitetura entre aplicações web tradicionais e Single Page Applications (SPA).

Os exercícios desta parte consistem em diagramas de sequência utilizando a sintaxe **Mermaid**.

### 📊 Exercícios Desenvolvidos:

- **Exercício 0.4: Novo diagrama de nota**
  - Mapeamento do fluxo tradicional de envio de dados, ilustrando a resposta com o código de status `302 Found` (Redirecionamento) e o recarregamento total da página pelo navegador.
- **Exercício 0.5: Single page app diagram**
  - Diagrama demonstrando o carregamento inicial de uma SPA, onde o HTML base chega ao cliente e o arquivo `spa.js` assume o controle para renderizar a interface de forma dinâmica.
- **Exercício 0.6: Nova nota em Single page app**
  - Fluxo assíncrono onde o JavaScript intercepta o formulário, atualiza a árvore do DOM (interface) instantaneamente e envia os dados estruturados em JSON em segundo plano para o servidor, recebendo um status `201 Created`.

---

## 👁️ Como Visualizar os Diagramas no VS Code

Os diagramas deste projeto foram construídos em Markdown puro utilizando blocos de código do **Mermaid**.

Se você estiver visualizando este projeto localmente pelo VS Code e o seu preview nativo não renderizar os gráficos automaticamente, siga os passos abaixo:

1. Vá até a aba de extensões do VS Code (`Ctrl + Shift + X`).
2. Procure por **Markdown Preview Mermaid Support** (desenvolvida por _Matt Bierner_).
3. Instale a extensão.
4. Abra qualquer arquivo `.md` da pasta `part0/` e use o comando `Ctrl + Shift + V` para abrir a visualização interativa do gráfico.

> 💡 **Nota:** Na interface web do GitHub, os diagramas são renderizados nativamente de forma automática, sem a necessidade de extensões externas.

---

## ⚙️ Tecnologias e Conceitos Praticados

- Protocolo HTTP (Métodos GET, POST, Cabeçalhos, Status Codes: 200, 302, 201)
- Document Object Model (DOM)
- JavaScript Assíncrono (AJAX / Fetch API)
- Arquitetura de Aplicações Monolíticas Tradicionais vs. SPAs
- Documentação técnica com Mermaid e Markdown
