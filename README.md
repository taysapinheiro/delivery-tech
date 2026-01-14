# 🚀 Qualifica SP – API de Delivery

Projeto desenvolvido como parte da **Formação em Arquitetura de Sistemas – Qualifica SP**.

Este repositório contém a construção de uma **API REST em Java 21**, voltada para um **sistema de delivery**, aplicando boas práticas de arquitetura, organização de código e princípios modernos de desenvolvimento backend.

---

## 📌 Objetivo do Projeto

O objetivo deste projeto é consolidar os conhecimentos adquiridos na formação, abordando:

* Arquitetura de sistemas
* Boas práticas de desenvolvimento backend
* Criação de APIs escaláveis e bem estruturadas
* Separação de responsabilidades
* Preparação para cenários reais de mercado

---

## 🛠️ Tecnologias Utilizadas

* **Java 21**
* **Spring Boot**
* **Spring Web**
* **Spring Data JPA**
* **Banco de Dados** (H2 / PostgreSQL / MySQL – a definir)
* **Maven**

---

## 🧱 Arquitetura

O projeto segue princípios de **arquitetura em camadas**, podendo evoluir para modelos como:

* Clean Architecture
* Hexagonal (Ports and Adapters)

### Camadas principais:

* **Controller** – Exposição dos endpoints REST
* **Service** – Regras de negócio
* **Repository** – Persistência de dados
* **Domain / Entity** – Modelos de domínio
* **DTOs** – Transferência de dados

---

## 📦 Funcionalidades (em evolução)

* Cadastro de usuários
* Cadastro de estabelecimentos
* Cadastro de produtos
* Realização de pedidos
* Atualização de status do pedido
* Integração com meios de pagamento (futuro)

---

## ▶️ Como Executar o Projeto

### Pré-requisitos

* Java 21 instalado
* Maven
* Git

### Passos

```bash
# Clonar o repositório
git clone https://github.com/seu-usuario/qualifica-sp.git

# Entrar no diretório
cd qualifica-sp

# Executar a aplicação
mvn spring-boot:run
```

A API estará disponível em:

```
http://localhost:8080
```

---

## 🧪 Testes

Para executar os testes:

```bash
mvn test
```

---

## 📚 Aprendizados Aplicados

* Modelagem de domínio
* Boas práticas REST
* Princípios SOLID
* Organização de projetos Java
* Versionamento com Git

---

## 🎓 Formação

Projeto desenvolvido durante a **Formação em Arquitetura de Sistemas – Qualifica SP**.

---

## 👩‍💻 Autora

**Taysa Mendes**
Desenvolvedora Backend / Full Stack

---

## 📄 Licença

Este projeto é apenas para fins educacionais.
