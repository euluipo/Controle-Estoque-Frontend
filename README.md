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

### ✅ Requisitos Funcionais
1.  O sistema permite o **cadastro, consulta, atualização e exclusão de produtos e categorias** por meio de **API REST** (`/api/produtos`, `/api/categorias`).
2.  O sistema possibilita o **registro de movimentações de estoque**, diferenciando **entradas e saídas**.
3.  O sistema permite o **reajuste de preços**, tanto de forma **unitária** quanto **em massa**, com base em um percentual definido pelo usuário.
4.  O sistema gera **relatórios consolidados** de produtos, movimentações e balanço geral.
5.  O sistema permite a **consulta e exibição da lista de preços atualizada**.
6.  O sistema oferece **autenticação e controle de usuários**, restringindo o acesso a endpoints protegidos.
7.  O sistema permite **integração com banco de dados relacional**, garantindo persistência confiável dos dados.

---

### ⚙️ Requisitos Não Funcionais
1.  Desenvolvido em **Java 21** com a biblioteca **Swing** para a interface gráfica (GUI).
2.  Arquitetura **Cliente-Servidor**. Este projeto é o cliente desktop.
3.  Comunicação com o servidor back-end realizada via **requisições HTTP** para uma **API REST**.
4.  Gerenciamento de dependências do projeto feito com **Apache Maven** (conforme `pom.xml`).
5.  Uso de **DTOs (Data Transfer Objects)** para a troca de dados (serialização/desserialização) com o back-end, no formato **JSON**.
6.  Implementação de **lógica de autenticação no lado do cliente** (`AuthManager`, `LoginFrame`) para gerenciar o estado do usuário e o token de acesso (JWT).