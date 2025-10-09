🏎️ Minimal API da Fórmula 1
Uma API leve e eficiente desenvolvida com Node.js e Fastify, focada em fornecer informações sobre a Fórmula 1. Ideal para aplicações web e móveis que necessitam de respostas rápidas e um ambiente minimalista.

📋 Descrição
Esta API oferece uma estrutura simplificada para operações CRUD básicas relacionadas à Fórmula 1, como equipes, pilotos e resultados. Seu objetivo é fornecer respostas rápidas e manter a estrutura enxuta, facilitando a integração com diferentes tipos de aplicações.

⚡ Funcionalidades
CRUD Completo: Permite criar, ler, atualizar e excluir dados sobre a Fórmula 1

Minimalista: Estrutura simples, fácil de entender e expandir

Rápida e Eficiente: Respostas ágeis para aplicações web e móveis

Flexível: Preparada para integração com diferentes tipos de front-end e serviços externos

🛠️ Tecnologias Utilizadas
Node.js: Ambiente de execução JavaScript do lado do servidor

Fastify: Framework Node.js voltado para alto desempenho e baixo consumo de recursos

🚀 Começando
Pré-requisitos
Node.js (versão 14 ou superior)

npm ou yarn

Instalação
bash
# Clone o repositório
git clone https://github.com/seu-usuario/f1-minimal-api.git

# Entre no diretório
cd f1-minimal-api

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
📚 Endpoints da API
Pilotos
GET /drivers - Lista todos os pilotos

GET /drivers/:id - Obtém um piloto específico

POST /drivers - Cria um novo piloto

PUT /drivers/:id - Atualiza um piloto

DELETE /drivers/:id - Remove um piloto

Equipes
GET /teams - Lista todas as equipes

GET /teams/:id - Obtém uma equipe específica

POST /teams - Cria uma nova equipe

PUT /teams/:id - Atualiza uma equipe

DELETE /teams/:id - Remove uma equipe

Resultados
GET /results - Lista todos os resultados

GET /results/:id - Obtém um resultado específico

POST /results - Cria um novo resultado

PUT /results/:id - Atualiza um resultado

DELETE /results/:id - Remove um resultado

🏃‍♂️ Scripts Disponíveis
bash
npm run dev      # Inicia o servidor de desenvolvimento
npm run build    # Compila o projeto
npm run start    # Inicia o servidor em produção
npm run test     # Executa os testes
