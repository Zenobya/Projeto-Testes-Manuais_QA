# 🧪 O Dia a Dia de um QA: A Prática de Testes Manuais Funcionais

> 🎓 Projeto desenvolvido durante o **Bootcamp Almaviva Solutions - Back-end com Java & QA** na plataforma [DIO](https://www.dio.me)
>
> 📌 Desafio: **O Dia a Dia de um QA: A Prática de Testes Manuais Funcionais**

---

## 📖 Sobre o projeto

Projeto prático de QA com foco em **testes manuais funcionais**, aplicando conceitos do mundo ágil (Scrum) ao sistema de e-commerce **SwagLabs Shopping** ([saucedemo.com](https://www.saucedemo.com)). Inclui documentação completa de fluxo de trabalho, histórias de usuário, mind-map e casos de teste.

---

## 🎯 Objetivos

- Revisar e aplicar conceitos de testes manuais no mundo ágil
- Compreender o ciclo de vida do bug
- Escrever User Stories com critérios de aceite
- Criar mind-maps para mapeamento de testes
- Documentar casos de teste nos formatos Step-by-Step e BDD

---

## 🛠️ Tecnologias e Ferramentas

- **JIRA** — Gerenciamento de projeto e registro de bugs
- **Confluence** — Documentação colaborativa
- **Scrum** — Metodologia ágil
- **Gherkin (BDD)** — Escrita de cenários de teste
- **SwagLabs / SauceDemo** — Sistema utilizado para os testes

---

## 📁 Documentos entregues

| Arquivo | Descrição |
|---------|-----------|
| `documento1_fluxo_e_ciclo_bug.pdf` | Fluxo de trabalho do QA no Scrum + Ciclo de vida do bug |
| `documento2_user_stories.pdf` | 2 User Stories com critérios de aceite e cenários BDD |
| `documento3_mindmap.pdf` | Mind-map da US-01 (Login na Plataforma) |
| `documento4_casos_de_teste.pdf` | 4 casos de teste: 2 Step-by-Step + 2 BDD |

---

## 📋 User Stories documentadas

### US-01 — Realizar Login na Plataforma
> Como cliente da SwagLabs, desejo realizar login com meu usuário e senha, para que eu possa acessar o catálogo de produtos e realizar compras.

**Épico:** Autenticação e Acesso do Usuário

### US-02 — Adicionar Produto ao Carrinho
> Como cliente autenticado na SwagLabs, desejo adicionar produtos ao carrinho de compras, para que eu possa selecionar os itens desejados antes de finalizar minha compra.

**Épico:** Gestão de Carrinho de Compras

---

## 🧩 Casos de Teste

| ID | Tipo | Descrição |
|----|------|-----------|
| CT-01 | Step-by-Step | Login com credenciais válidas |
| CT-02 | Step-by-Step | Login com usuário bloqueado (locked_out_user) |
| CT-03 | BDD | Adicionar e remover produto do carrinho |
| CT-04 | BDD | Login com senha incorreta e campos vazios |

---

## 🔄 Fluxo de Trabalho QA no Scrum

```
BACKLOG → SPRINT PLANNING → DESENVOLVIMENTO → READY FOR QA → TESTES QA → DONE
```

O QA participa ativamente em todas as etapas: refinamento de histórias, planning poker, criação de casos de teste, execução e registro de bugs.

---

## 🐛 Ciclo de Vida do Bug

```
NEW → ASSIGNED → IN PROGRESS → READY FOR RETEST → RETEST → VERIFIED → CLOSED
                                                              ↓
                                                          REOPENED
```

---

## 📄 Licença

Este projeto está sob a licença **MIT**.

---

## 👩‍💻 Autora

Desenvolvido por **Camila Machado** ✨

[![GitHub](https://img.shields.io/badge/GitHub-CamilaMachado-181717?style=flat&logo=github&logoColor=white)](https://github.com)
[![DIO](https://img.shields.io/badge/DIO-Bootcamp-F97316?style=flat&logo=rocket&logoColor=white)](https://www.dio.me)
[![Almaviva](https://img.shields.io/badge/Almaviva_Solutions-Back--end_Java_%26_QA-0057A8?style=flat)](https://www.dio.me)
