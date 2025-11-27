# Desafio WAR Estruturado – Tema 1

Este repositório contém a implementação estruturada de uma versão simplificada do jogo **WAR**, com foco em manipulação de dados, modularização de código, ponteiros, alocação dinâmica e definição de tipos abstratos em C.

## 🎯 Objetivos do Projeto
- Representar territórios usando `struct`.
- Utilizar memória dinâmica com `malloc`, `calloc`, `realloc` e `free`.
- Implementar lógica de ataque entre territórios usando ponteiros.
- Usar ponteiros para funções (estratégias de ataque).
- Modularizar o projeto de forma profissional.
- Criar e verificar missões e condições de vitória.
- Garantir performance, legibilidade e manutenibilidade.

📌 Descrição rápida dos módulos
territory.c / territory.h

Criação e destruição de territórios

Ligação bidirecional entre territórios (vizinhança)

Representação de nome, dono, tropas e conexões

attack.c / attack.h

Função de ataque entre dois territórios

Estratégias configuráveis através de ponteiro para função

Exemplos de estratégias: aleatória e gananciosa

missions.c / missions.h

Verificação de condições de vitória

Missões básicas implementadas:

“Controlar todos os territórios”

“Eliminar jogador específico”

🧪 Testes

O projeto inclui exemplos simples no main.c para validar:

Criação do mapa

Conexões entre territórios

Ataques usando estratégia aleatória

Verificação de missão

📚 Relatório

O documento docs/relatorio.md descreve:

Estruturas de dados

Decisões de arquitetura

Uso de ponteiros e memória dinâmica

Modularização

Testes

Melhorias futuras

👨‍💻 Autor

Lucas venicius da silva farias.
