# Dashboard: Análise de Percepção de Produtos Diet & Light

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Chart.js](https://img.shields.io/badge/chart.js-F5788D.svg?style=for-the-badge&logo=chart.js&logoColor=white)

## 📖 Sobre o Projeto

Este projeto é um **dashboard interativo de página única (SPA)**, desenvolvido para transformar os dados brutos de uma pesquisa de mercado em uma experiência visual e analítica. A página não apenas renderiza os resultados da pesquisa em múltiplos gráficos, mas também se conecta diretamente à **API do Google Gemini** para gerar um resumo analítico detalhado com o clique de um botão.

O objetivo foi criar uma ferramenta de visualização de dados moderna, responsiva e inteligente, demonstrando habilidades avançadas em desenvolvimento front-end e integração com serviços de IA.

---

## ✨ Funcionalidades Principais

-   **Visualização de Dados com Chart.js:**
    A página apresenta 8 gráficos do tipo "doughnut", cada um representando uma pergunta da pesquisa, com animações e tooltips interativos para uma fácil interpretação dos dados.

-   **Análise em Tempo Real com IA Generativa (Gemini):**
    Um botão de destaque aciona uma chamada à API do Google Gemini, enviando os dados da pesquisa e solicitando um resumo analítico estruturado. A resposta da IA é exibida em um modal, oferecendo insights instantâneos sobre o perfil do consumidor, conclusões e recomendações de marketing.

-   **Interface Responsiva e Moderna:**
    Construído com Tailwind CSS e estilização customizada, o layout é totalmente responsivo e inclui elementos de design modernos como o efeito "glassmorphism" nos cards, animações de entrada em cascata e micro-interações.

-   **Acesso a Relatório Completo:**
    Disponibiliza um link para download direto de um relatório complementar em formato PDF.

---

## 🛠️ Tecnologias Utilizadas

-   **HTML5:** Para a estruturação semântica do dashboard.
-   **Tailwind CSS:** Para a criação de um design utility-first, ágil e responsivo.
-   **JavaScript (Vanilla JS):** Para controlar toda a lógica do front-end, incluindo a renderização dos gráficos, manipulação do DOM, animações e a comunicação com a API.
-   **Chart.js:** Biblioteca utilizada para criar e customizar os gráficos de visualização de dados.
-   **Google Gemini API:** Utilizada para a geração de texto e análise de dados em tempo real.

---

## ⚙️ Como Executar e Configurar

### Pré-requisitos

-   Um navegador web moderno (Chrome, Firefox, Edge, etc.).
-   Uma chave de API do Google Gemini (você pode obter uma no [Google AI Studio](https://aistudio.google.com/)).

### Rodando a Aplicação

1.  **Clone o repositório:**
    ```bash
    git clone <URL_DO_SEU_REPOSITORIO>
    ```

2.  **Configure sua Chave de API:**
    -   Abra o arquivo `index.html` em um editor de código.
    -   Procure pela linha `const apiKey = "AIzaSy...";` dentro da tag `<script>`.
    -   **Substitua o valor existente pela sua própria chave de API do Google Gemini.**

    > **⚠️ Aviso de Segurança Importante:**
    > Expor sua chave de API diretamente no código do front-end é uma prática insegura e deve ser usada apenas para testes locais ou projetos de demonstração. Em uma aplicação real, a chave deve ser protegida em um servidor de back-end.

3.  **Visualize a Página:**
    Após salvar a alteração com sua chave, simplesmente dê um duplo clique no arquivo `index.html` para abri-lo no seu navegador. Para uma melhor experiência, use a extensão "Live Server" no VS Code.

---

## 👨‍💻 Autores

-   Tarciso Ferreira
-   Maria Dayane
-   Alana Silvestre

