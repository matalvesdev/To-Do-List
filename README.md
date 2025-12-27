# To-Do-List ✅

Sistema de gerenciamento de tarefas desenvolvido em **Java**, com foco em simplicidade, organização e aplicação prática de conceitos de Programação Orientada a Objetos.  
Permite **adicionar, listar, concluir e remover tarefas**, servindo como base sólida para evolução em projetos maiores.

---

## 📋 Sobre o Projeto

O **To-Do-List** é uma aplicação Java que implementa um gerenciador básico de tarefas, ideal para estudo e portfólio.  
O projeto foi estruturado com mentalidade profissional, utilizando **Maven**, separação de responsabilidades e código preparado para futuras expansões.

Aqui, o objetivo não é só “funcionar”, mas demonstrar **clareza arquitetural**, **organização** e **boas práticas**.

---

## ✨ Funcionalidades

- ➕ **Adicionar tarefa** – Criar novas tarefas com descrição
- 📋 **Listar tarefas** – Visualizar todas as tarefas cadastradas
- ✔️ **Marcar tarefa como concluída**
- ❌ **Remover tarefa**
- 🏷️ **Controle de status** – Tarefas pendentes e concluídas
- 🧠 **Estrutura extensível** – Pronta para API, banco de dados ou interface gráfica

---

## 🛠️ Tecnologias Utilizadas

- **Java** – Linguagem principal
- **Maven** – Gerenciamento de dependências e build
- **JDK 11+** – Ambiente de execução
- **POO** – Encapsulamento, separação de responsabilidades e reutilização

---

## 🏗️ Estrutura do Projeto

To-Do-List/
├── src/
│ ├── main/
│ │ └── java/
│ │ └── (pacotes do projeto)
│ └── test/
│ └── java/
├── target/
├── pom.xml
└── README.md

yaml
Copiar código

---

## 📦 Principais Componentes

### Classe de Tarefa

Responsável por representar uma tarefa no sistema.

**Responsabilidades:**
- Armazenar a descrição da tarefa
- Controlar o status (concluída ou não)
- Fornecer representação textual clara

---

### Classe de Gerenciamento

Responsável por centralizar as regras de negócio.

**Responsabilidades:**
- Criar tarefas
- Listar tarefas existentes
- Finalizar tarefas
- Remover tarefas

Essa separação garante **baixo acoplamento** e **alta coesão**.

---

### Classe Principal (Main)

Responsável por iniciar a aplicação e orquestrar o fluxo de execução.

**Fluxo geral:**
1. Inicializa o gerenciador de tarefas
2. Executa as operações disponíveis
3. Exibe resultados no console

---

## 🚀 Como Executar o Projeto

### Pré-requisitos

- Java JDK 11 ou superior
- Maven 3.x

### Passo 1: Clone o repositório

```bash
git clone https://github.com/matalvesdev/To-Do-List.git
cd To-Do-List
Passo 2: Compile o projeto
bash
Copiar código
mvn clean install
Passo 3: Execute a aplicação
bash
Copiar código
mvn exec:java
Caso necessário, especifique a classe principal:

bash
Copiar código
mvn exec:java -Dexec.mainClass="com.seupacote.Main"
🎯 Conceitos Aplicados
Programação Orientada a Objetos
Encapsulamento

Separação de responsabilidades

Modelagem de domínio simples e clara

Organização de Projeto
Estrutura padrão Maven

Código limpo e legível

Facilidade de manutenção e evolução

🔮 Possíveis Evoluções Futuras
 Persistência em banco de dados (MySQL / PostgreSQL)

 Criação de API REST com Spring Boot

 Interface gráfica ou frontend web

 Testes unitários com JUnit

 Autenticação de usuários

 Deploy em ambiente cloud

 CI/CD com GitHub Actions

🎯 Objetivo do Projeto
Este projeto faz parte de um portfólio técnico, com foco em demonstrar:

Domínio dos fundamentos de Java

Organização e clareza de código

Capacidade de estruturar projetos prontos para escalar

Projetos simples, quando bem feitos, mostram maturidade técnica.

👨‍💻 Autor
Desenvolvido por matalvesdev

⭐ Se este projeto te ajudou ou serviu de referência, considere deixar uma estrela no repositório!

Copiar código
