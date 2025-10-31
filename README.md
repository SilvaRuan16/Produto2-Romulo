# 📝 Sistema de Registro de Ocorrências

![Java](https://img.shields.io/badge/Java-17+-red?logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.x-brightgreen?logo=springboot)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql)
![Maven](https://img.shields.io/badge/Maven-Build-orange?logo=apachemaven)
![License](https://img.shields.io/badge/license-Academic-lightgrey)

> Aplicação simples desenvolvida em **Java** com **Spring Boot**, onde usuários podem se **registrar** e **cadastrar ocorrências** através do **console**.

---

## 📚 Sumário

1. [🎯 Objetivo do Projeto](#-objetivo-do-projeto)  
2. [⚙️ Funcionalidades](#%EF%B8%8F-funcionalidades)  
3. [🧩 Tecnologias Utilizadas](#-tecnologias-utilizadas)  
4. [🏗️ Estrutura do Projeto](#%EF%B8%8F-estrutura-do-projeto)  
5. [🧠 Conceitos Aplicados](#-conceitos-aplicados)  
6. [🖥️ Como Executar o Projeto](#%EF%B8%8F-como-executar-o-projeto)  
7. [👨‍💻 Equipe de Desenvolvimento](#-equipe-de-desenvolvimento)  
8. [📄 Licença](#-licença)  
9. [💡 Observações Finais](#-observações-finais)

---

## 🎯 Objetivo do Projeto

O sistema tem como propósito **permitir o registro e gerenciamento de ocorrências** por meio de uma interface **via console**, aplicando conceitos fundamentais de desenvolvimento em camadas com o **Spring Boot**.

Este projeto foi criado com fins **didáticos**, com foco em:
- Estrutura de projetos Java usando camadas (Model, Controller, Service, Repository);
- Conexão com banco de dados relacional (PostgreSQL);
- Programação orientada a objetos (POO);
- Práticas de boas arquiteturas e injeção de dependência;
- Execução via console para melhor compreensão da lógica de fluxo.

---

## ⚙️ Funcionalidades

✅ Cadastro de usuários  
✅ Login de usuários  
✅ Registro de ocorrências  
✅ Listagem de ocorrências registradas  
✅ Interface e navegação via console  
✅ Armazenamento em banco de dados  

---

## 🧩 Tecnologias Utilizadas

| Categoria | Ferramenta |
|------------|-------------|
| **Linguagem** | Java 17+ |
| **Framework** | Spring Boot 3.x |
| **Banco de Dados** | PostgreSQL |
| **ORM / JPA** | Spring Data JPA |
| **Validação** | Bean Validation (Jakarta Validation) |
| **Gerenciador de Dependências** | Maven |
| **IDE sugerida** | Vscode ou Firebase Studio |

---

## 🏗️ Estrutura do Projeto

src/
└── main/
├── java/
│ └── br/com/ocorrencias/
│ ├── model/ # Classes de domínio (Usuário, Ocorrência)
│ ├── controller/ # Controladores para entrada/saída de dados
│ ├── service/ # Regras de negócio e validações
│ └── repository/ # Acesso ao banco de dados (Spring Data JPA)
└── resources/
├── application.properties # Configurações do banco e do Spring Boot
└── banner.txt # (opcional) Mensagem personalizada do console



---

## 🧠 Conceitos Aplicados

🧩 **Programação Orientada a Objetos (POO)** — encapsulamento, herança e polimorfismo.  
⚙️ **Arquitetura em camadas** — separação clara entre regras de negócio, controle e persistência.  
💾 **Persistência com Spring Data JPA** — integração direta com o PostgreSQL.  
🧠 **Injeção de dependência (IoC / DI)** — gerenciamento automático de componentes pelo Spring.  
✅ **Validação de dados** — uso de anotações do Bean Validation para garantir integridade.  

---

## 🖥️ Como Executar o Projeto

### 🔹 1. Clone o repositório:
```bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
