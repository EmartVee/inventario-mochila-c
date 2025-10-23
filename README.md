# 🔫🎒 Desafio Código da Ilha – Edição Free Fire  
## 💼 Nível Aventureiro — Mochila com Busca (Linguagem C)

Bem-vindo ao **Desafio Código da Ilha – Edição Free Fire!**  
Este projeto implementa o **gerenciamento de inventário de sobrevivência** em C, utilizando `struct` e **listas sequenciais (vetores)**.

---

## 🎯 Objetivo

Desenvolver um sistema de **mochila virtual** onde o jogador possa **adicionar, remover, listar e buscar itens**.  
O foco é simular a organização dos recursos coletados nos primeiros momentos de sobrevivência.

---

## ⚙️ Funcionalidades Implementadas

| Funcionalidade | Descrição |
|----------------|------------|
| 🧱 **Struct `Item`** | Armazena `nome`, `tipo` e `quantidade` de cada item. |
| 🎒 **Vetor de até 10 itens** | Representa a mochila do jogador. |
| ➕ **Adicionar item** | Permite cadastrar novos itens com nome, tipo e quantidade. |
| ➖ **Remover item** | Remove um item existente pelo nome. |
| 🔍 **Buscar item** | Implementa **busca sequencial** (case-insensitive) pelo nome. |
| 📋 **Listar itens** | Exibe os itens cadastrados em formato de tabela. |
| 🌀 **Menu interativo** | Controlado por `do...while` + `switch`, com mensagens orientativas. |
| 🧠 **Comparação inteligente** | A busca ignora letras maiúsculas/minúsculas (`tolower`). |

---

## 🧩 Estrutura de Dados

```c
typedef struct {
    char nome[30];
    char tipo[20];
    int  quantidade;
} Item;
