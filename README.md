# FarmacuraPet 🐾
> **Conectando doadores de medicamentos veterinários a quem mais precisa.**

O **FarmacuraPet** é uma plataforma de economia circular e solidariedade animal. O projeto facilita a doação de sobras de medicamentos veterinários (dentro do prazo de validade), ajudando protetores independentes e tutores de baixa renda a darem continuidade aos tratamentos de seus pets.

---

## 📍 Contexto do Projeto
Desenvolvido em Pernambuco para o programa **Projetão**, com foco inicial nas regiões de **Recife e Cabo de Santo Agostinho**. O projeto atua diretamente no bem-estar animal e na sustentabilidade, evitando o descarte incorreto de fármacos no meio ambiente.

## 🛠️ Tecnologias e Ferramentas
Para garantir que o projeto seja acessível e funcional, utilizamos:
* **Linguagem:** Python 3.11
* **Framework Mobile:** Kivy (Desenvolvimento Mobile-First)
* **Banco de Dados:** SQLite (Persistência de dados local)
* **Front-end Web:** HTML5 & Tailwind CSS
* **IDE de Desenvolvimento:** Pydroid 3 (Android)

## 🚀 Funcionalidades (Status: Quest 3)
- [x] **Cadastro de Doações:** Interface simples para inserir nome do remédio e validade.
- [x] **Persistência de Dados:** Uso de banco de dados SQLite para salvar informações offline.
- [x] **Interface Responsiva:** Design adaptado para telas de smartphones.
- [ ] **Filtro de Validade:** Lógica para destacar medicamentos próximos do vencimento (Em desenvolvimento).
- [ ] **Geolocalização:** Identificação de pontos de coleta em Gaibu e Recife (Planejado).

## 📂 Estrutura do Repositório
```text
├── src/                # Código fonte em Python (Kivy)
├── web/                # Landing Page do projeto (HTML/CSS)
├── database/           # Esquema do banco de dados SQLite
├── README.md           # Documentação principal
└── .gitignore          # Arquivos ignorados pelo Git
