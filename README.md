# Sistema de Controle de Estoque 📦
### **Repositório Front-End (Java Swing)**

Projeto desenvolvido para a disciplina **Sistemas Distribuídos e Mobile** da **Universidade do Sul de Santa Catarina - UNISUL**.

---

**Link Repositório Back-end:** https://github.com/euluipo/Controle-Estoque-Backend

**Link Repositório Front-end React:** https://github.com/euluipo/Controle-Estoque-Frontend-React

---

## 🎓 Informações Acadêmicas

- **Disciplina:** Sistemas Distribuídos e Mobile
- **Professores:** Osmar de Oliveira Braz Júnior
- **Avaliação:** A3 – Desempenho de compreensão
- **Meta:** Projetar e desenvolver sistemas com arquiteturas baseadas em serviços.

## 👥 Integrantes do Grupo

- Arthur Zamprogna Ventura - 10725111773 - [@arthurventuraza](https://github.com/arthurventuraza/)
- Gabriel Luipo - 1072519471 - [@euluipo](https://github.com/euluipo/)
- Nícolas Gaia Negrão - 1072517389 - [@NickPotato](https://github.com/nickpotato/)
- Pedro Henrique Francio Della Giustina - 10725110773 - [@PedroDella](https://github.com/pedrodella/)

---

## 🧭 Funcionalidades (via API)

Este cliente consome os seguintes recursos do back-end:

## ✅ Requisitos Funcionais (RF)

Estes requisitos descrevem **o que** o sistema deve fazer (as funcionalidades).

| ID | Descrição |
| :--- | :--- |
| **RF-001** | O sistema deve permitir o **cadastro, consulta, atualização e exclusão (CRUD)** de produtos e categorias por meio da API REST (`/api/produtos`, `/api/categorias`). |
| **RF-002** | O sistema deve possibilitar o **registro de movimentações de estoque**, diferenciando entradas e saídas. |
| **RF-003** | O sistema deve permitir o **reajuste de preços** de produtos, tanto de forma unitária quanto em massa (com base em um percentual). |
| **RF-004** | O sistema deve gerar **relatórios consolidados** de produtos, movimentações e balanço geral. |
| **RF-005** | O sistema deve permitir a **consulta e exibição da lista de preços** atualizada. |
| **RF-006** | O sistema deve oferecer **autenticação e controle de usuários**, restringindo o acesso a endpoints protegidos. |
| **RF-007** | O sistema deve permitir a **integração com banco de dados relacional** para garantir a persistência confiável dos dados. |

---

## ⚙️ Requisitos Não Funcionais (RNF)

Estes requisitos descrevem **como** o sistema deve operar ou as restrições técnicas (qualidade, desempenho, tecnologia).

| ID | Descrição |
| :--- | :--- |
| **RNF-001** | O cliente desktop deve ser desenvolvido em **Java 21** com a biblioteca **Swing** para a interface gráfica (GUI). |
| **RNF-002** | A arquitetura do sistema deve seguir o modelo **Cliente-Servidor** (este projeto é o cliente). |
| **RNF-003** | A comunicação com o servidor back-end deve ser realizada via **requisições HTTP** para uma API REST. |
| **RNF-004** | O gerenciamento de dependências do projeto deve ser feito com **Apache Maven**. |
| **RNF-005** | A troca de dados com o back-end deve ser feita usando **DTOs (Data Transfer Objects)** no formato **JSON**. |
| **RNF-006** | O cliente deve implementar a **lógica de autenticação** (`AuthManager`, `LoginFrame`) para gerenciar o estado do usuário e o token de acesso (JWT). |