# 📡 Qt Supervisory Client/Server

<p align="center">
  🇧🇷 Português | 🇺🇸 English
</p>

## 📌 Sobre o projeto

O **Qt Supervisory Client/Server** é um sistema desenvolvido em C++ com o framework Qt, com foco em **comunicação cliente-servidor e visualização de dados em tempo real**.

O projeto simula um ambiente de supervisão, onde diferentes clientes interagem com um servidor central para envio e visualização de dados associados a timestamps.

---

## 📌 About the Project

The **Qt Supervisory Client/Server** is a system developed in C++ using the Qt framework, focused on **client-server communication and real-time data visualization**.

The project simulates a supervisory environment, where different clients interact with a central server to send and visualize timestamped data.

---

## 🛠️ Tecnologias utilizadas

* 💻 **C++**
* ⚙️ **Qt Framework**
* 🌐 Comunicação via TCP/IP
* 📊 Interface gráfica em tempo real

---

## 🛠️ Technologies Used

* 💻 **C++**
* ⚙️ **Qt Framework**
* 🌐 TCP/IP communication
* 📊 Real-time graphical interface

---

## 💡 Funcionalidades

* 📡 Comunicação cliente-servidor
* ⏱️ Envio de dados com timestamp
* 👥 Suporte a múltiplos clientes simultâneos
* 📈 Visualização gráfica dinâmica
* 🔄 Separação entre produção e consumo de dados

---

## 💡 Features

* 📡 Client-server communication
* ⏱️ Timestamped data transmission
* 👥 Support for multiple simultaneous clients
* 📈 Dynamic graphical visualization
* 🔄 Separation between data production and consumption

---

## 🧩 Componentes do sistema

* **Servidor** → Armazena e gerencia os dados
* **Producer** → Envia dados ao servidor
* **Consumer** → Consome e exibe os dados em gráfico

---

## 🧩 System Components

* **Server** → Stores and manages data
* **Producer** → Sends data to the server
* **Consumer** → Retrieves and displays data in graphs

---

## ▶️ Como executar

### Pré-requisitos

* Qt instalado
* Qt Creator ou `qmake` / `make`
* Compilador C++ compatível

### Passos

```bash id="y5f9tw"
# Clone o repositório
git clone https://github.com/GabrielFGonzaga/ProjetoPA_qtsupervisory.git

# Acesse a pasta
cd ProjetoPA_qtsupervisory
```

1. Compile separadamente:

   * QtTcpServer
   * QtTcpClientProducer
   * QtTcpClientConsumer

2. Execute o servidor

3. Execute um ou mais Producers

4. Execute um ou mais Consumers

---

## ▶️ How to Run

### Prerequisites

* Qt installed
* Qt Creator or `qmake` / `make`
* Compatible C++ compiler

### Steps

```bash id="c3t0g2"
# Clone the repository
git clone https://github.com/GabrielFGonzaga/ProjetoPA_qtsupervisory.git

# Navigate to the folder
cd ProjetoPA_qtsupervisory
```

1. Build separately:

   * QtTcpServer
   * QtTcpClientProducer
   * QtTcpClientConsumer

2. Run the server

3. Run one or more Producers

4. Run one or more Consumers

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos como:

* Programação de redes (TCP/IP)
* Arquitetura cliente-servidor
* Comunicação entre múltiplos processos
* Desenvolvimento de interfaces com Qt
* Visualização de dados em tempo real

---

## 📚 Learning Outcomes

During the development of this project, the following concepts were applied:

* Network programming (TCP/IP)
* Client-server architecture
* Communication between multiple processes
* GUI development with Qt
* Real-time data visualization

---

## 🔮 Melhorias futuras

* 🔹 Adicionar autenticação
* 🔹 Melhorar tratamento de erros
* 🔹 Persistência em banco de dados
* 🔹 Melhorias na interface gráfica

---

## 🔮 Future Improvements

* 🔹 Add authentication
* 🔹 Improve error handling
* 🔹 Database persistence
* 🔹 UI improvements

---

## 👨‍💻 Autores

Desenvolvido por **Gabriel Gonzaga** e **Aysllan Paulo** 🚀

---

## 👨‍💻 Authors

Developed by **Gabriel Gonzaga** and **Aysllan Paulo** 🚀
