# 📡 Qt Supervisory Client/Server

## 📌 Sobre o projeto

O **Qt Supervisory Client/Server** é um sistema desenvolvido em C++ com o framework Qt, com foco em **comunicação cliente-servidor e visualização de dados em tempo real**.

O projeto simula um ambiente de supervisão, onde diferentes clientes interagem com um servidor central para envio e visualização de dados associados a timestamps.

---

## 🛠️ Tecnologias utilizadas

* 💻 **C++**
* ⚙️ **Qt Framework**
* 🌐 Comunicação via TCP/IP
* 📊 Interface gráfica em tempo real

---

## 💡 Funcionalidades

* 📡 Comunicação cliente-servidor
* ⏱️ Envio de dados com timestamp
* 👥 Suporte a múltiplos clientes simultâneos
* 📈 Visualização gráfica dinâmica
* 🔄 Separação entre produção e consumo de dados

---

## 🧩 Componentes do sistema

* **Servidor** → Armazena e gerencia os dados
* **Producer** → Envia dados ao servidor
* **Consumer** → Consome e exibe os dados em gráfico

---

## ▶️ Como executar

### Pré-requisitos

* Qt instalado
* Qt Creator ou `qmake` / `make`
* Compilador C++ compatível

### Passos

```bash
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

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram aplicados conceitos como:

* Programação de redes (TCP/IP)
* Arquitetura cliente-servidor
* Comunicação entre múltiplos processos
* Desenvolvimento de interfaces com Qt
* Visualização de dados em tempo real

---

## 🔮 Melhorias futuras

* 🔹 Adicionar autenticação
* 🔹 Melhorar tratamento de erros
* 🔹 Persistência em banco de dados
* 🔹 Melhorias na interface gráfica

---

## 👨‍💻 Autores

Desenvolvido por **Gabriel Gonzaga** e **Aysllan Paulo** 🚀
