# 🚀 Spring MVC

Projeto desenvolvido com **Java e Spring MVC**, utilizando **Gradle** para gerenciamento de dependências e automação do processo de build.

Este projeto faz parte dos estudos e práticas de desenvolvimento **Back-end com Java**, explorando conceitos relacionados ao ecossistema Spring e à construção de aplicações web estruturadas.

---

## 📚 Sobre o projeto

O objetivo deste projeto é aplicar na prática conceitos fundamentais do desenvolvimento web utilizando **Spring MVC**, trabalhando com a arquitetura baseada no padrão **Model-View-Controller (MVC)**.

A aplicação utiliza o **Gradle Wrapper**, permitindo executar o projeto sem a necessidade de instalar uma versão específica do Gradle globalmente.

---

## 🛠️ Tecnologias utilizadas

<div align="center">

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge\&logo=openjdk\&logoColor=white)

![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge\&logo=spring\&logoColor=white)

![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge\&logo=gradle\&logoColor=white)

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge\&logo=git\&logoColor=white)

![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge\&logo=github\&logoColor=white)

</div>

---

## 🏗️ Arquitetura

O projeto segue o conceito do padrão arquitetural **MVC (Model-View-Controller)**:

```text
                ┌──────────────────┐
                │      Cliente     │
                │   Browser / API  │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │    Controller    │
                │   Spring MVC     │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │      Model       │
                │ Dados / Regras   │
                └────────┬─────────┘
                         │
                         ▼
                ┌──────────────────┐
                │       View       │
                │ Interface Web    │
                └──────────────────┘
```

### 🔹 Model

Responsável pela representação dos dados e das regras relacionadas ao domínio da aplicação.

### 🔹 View

Responsável pela apresentação das informações ao usuário.

### 🔹 Controller

Responsável por receber as requisições HTTP, processar as informações necessárias e direcionar o fluxo da aplicação.

---

## 📂 Estrutura do projeto

```text
Spring-mvc/
│
├── gradle/
│   └── wrapper/
│
├── src/
│   └── ...
│
├── .gitattributes
├── .gitignore
├── build.gradle
├── gradlew
├── gradlew.bat
├── settings.gradle
│
└── Variavel de ambiente
```

---

## ⚙️ Pré-requisitos

Antes de executar o projeto, tenha instalado:

* ☕ **Java JDK**
* 🐘 **Git**
* 💻 Uma IDE de sua preferência

  * IntelliJ IDEA
  * Eclipse
  * Visual Studio Code

O projeto possui **Gradle Wrapper**, portanto não é necessário instalar o Gradle manualmente.

---

## 🚀 Como executar

### 1. Clone o repositório

```bash
git clone https://github.com/G-Souto/Spring-mvc.git
```

### 2. Acesse o projeto

```bash
cd Spring-mvc
```

### 3. Execute utilizando o Gradle Wrapper

#### Windows

```bash
.\gradlew.bat bootRun
```

#### Linux / macOS

```bash
./gradlew bootRun
```

Caso o projeto não possua a task `bootRun`, utilize:

```bash
./gradlew build
```

---

## 🔐 Variáveis de ambiente

Caso o projeto utilize informações sensíveis ou configurações externas, recomenda-se configurar essas informações através de **variáveis de ambiente**.

Exemplo:

```text
DATABASE_URL=...
DATABASE_USERNAME=...
DATABASE_PASSWORD=...
```

> ⚠️ Nunca publique senhas, tokens, chaves de API ou outras credenciais diretamente no código ou no repositório.

---

## 🧪 Build

Para gerar o build do projeto:

```bash
./gradlew build
```

No Windows:

```powershell
.\gradlew.bat build
```

Para limpar os arquivos gerados:

```bash
./gradlew clean
```

---

## 📌 Conceitos estudados

Durante o desenvolvimento deste projeto são trabalhados conceitos importantes de desenvolvimento Back-end, como:

* Java
* Spring Framework
* Spring MVC
* Arquitetura MVC
* Controllers
* Requisições HTTP
* Rotas
* Models
* Views
* Gerenciamento de dependências
* Gradle
* Variáveis de ambiente
* Organização de projetos Java
* Git e GitHub

---

## 🎯 Objetivo acadêmico

Este projeto foi desenvolvido como parte da jornada de aprendizado em **Análise e Desenvolvimento de Sistemas**, com foco no desenvolvimento **Back-end utilizando Java e Spring**.

A aplicação serve como prática para compreender como uma aplicação web pode ser estruturada utilizando o padrão MVC e o ecossistema Spring.

---

## 🔮 Possíveis evoluções

Algumas melhorias que podem ser implementadas futuramente:

* [ ] Implementar autenticação e autorização
* [ ] Adicionar Spring Security
* [ ] Integrar banco de dados
* [ ] Implementar Spring Data JPA
* [ ] Criar APIs REST
* [ ] Adicionar validação de dados
* [ ] Implementar tratamento global de exceções
* [ ] Criar testes unitários
* [ ] Criar testes de integração
* [ ] Implementar documentação com Swagger/OpenAPI
* [ ] Criar pipeline CI/CD
* [ ] Containerizar com Docker

---

## 👨‍💻 Autor

**Gustavo Souto**

Estudante de **Análise e Desenvolvimento de Sistemas — FIAP**

Foco em desenvolvimento **Full Stack**, com experiência e estudos em:

`Java` • `Spring` • `C#` • `.NET` • `TypeScript` • `React` • `Next.js` • `SQL` • `Docker` • `Azure`

---

## 🔗 Links

* 💻 **Repositório:** https://github.com/G-Souto/Spring-mvc
* 🐙 **GitHub:** https://github.com/G-Souto

---

<div align="center">

### ⭐ Se este projeto foi útil para você, considere deixar uma estrela!

**Desenvolvido por Gustavo Souto 🚀**

</div>
