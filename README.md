Minimal API da Fórmula 1 com Node.js e Fastify

Esta é uma API leve e eficiente desenvolvida com Node.js e Fastify, criada para fornecer informações sobre a Fórmula 1. É ideal para aplicações web e móveis que necessitam de respostas rápidas e um ambiente minimalista.

Descrição

A API permite realizar operações CRUD básicas relacionadas à Fórmula 1, como gerenciar equipes, pilotos e resultados. Com uma estrutura simplificada, ela mantém o foco na velocidade e eficiência, tornando fácil a integração com diferentes tipos de aplicações.

Funcionalidades

CRUD Completo: Criação, leitura, atualização e exclusão de dados sobre a Fórmula 1.

Minimalista: Estrutura simples, fácil de entender e expandir.

Rápida e Eficiente: Respostas ágeis para aplicações web e móveis.

Flexível: Pode ser integrada facilmente a diferentes front-ends ou serviços externos.

Exemplos de Dados
Equipes
[
  { "id": 1, "nome": "Mercedes", "base": "Brackley, Reino Unido" },
  { "id": 2, "nome": "Red Bull Racing", "base": "Milton Keynes, Reino Unido" },
  { "id": 3, "nome": "Ferrari", "base": "Maranello, Itália" }
]

Pilotos
[
  { "id": 1, "nome": "Lewis Hamilton", "equipe": "Mercedes", "pais": "Reino Unido" },
  { "id": 2, "nome": "Max Verstappen", "equipe": "Red Bull Racing", "pais": "Países Baixos" },
  { "id": 3, "nome": "Charles Leclerc", "equipe": "Ferrari", "pais": "Mônaco" }
]

Resultados
[
  { "id": 1, "corrida": "GP do Bahrain", "vencedor": "Lewis Hamilton", "ano": 2025 },
  { "id": 2, "corrida": "GP de Mônaco", "vencedor": "Max Verstappen", "ano": 2025 }
]

Tecnologias Utilizadas

Node.js: Ambiente de execução JavaScript do lado do servidor.

Fastify: Framework Node.js voltado para alto desempenho e baixo consumo de recursos.
