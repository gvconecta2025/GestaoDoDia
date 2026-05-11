# 📔 Gestão do Dia

Um Web App Progressivo (PWA) focado em produtividade real, eliminando a sobrecarga mental através de uma matriz simplificada de tempo e impacto.

## 🎯 O Conceito
A interface simula "cadernetas" de projetos (Escola, Finanças, Pessoal). O fluxo de tempo abandona o calendário tradicional e foca em 3 colunas de "Instante":
1. **Atrasado (O Passado):** Tarefas pendentes.
2. **Agora (O Presente):** O foco principal (visão diária, semanal ou mensal).
3. **Antecipado (O Futuro):** O que está no radar.

Dentro de cada caderneta, as tarefas são divididas em 3 linhas horizontais por cor, indicando o **Impacto** (Alto, Normal, Baixo). As tarefas concluídas são riscadas e movidas para o rodapé da caderneta.

## 🛠️ Stack Tecnológica
* **Frontend:** React / Next.js (hospedado na Vercel)
* **Backend & Auth:** Firebase (Authentication & Firestore)
* **Interação:** Drag and Drop (arrastável entre colunas e níveis de impacto)

## 📂 Arquitetura do Repositório
O projeto utiliza uma estrutura consolidada, com todas as partes do aplicativo separadas por pastas dentro deste único repositório:

```text
gestao-do-dia/
├── frontend/             # Aplicação web/PWA (Next.js, componentes visuais, DnD)
├── services/             # Lógica de conexão com Firebase, Autenticação e Firestore
├── docs/                 # Documentação de design, wireframes e regras de negócio
├── .gitignore
└── README.md
