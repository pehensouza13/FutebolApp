# ⚽ FutebolApp - Flutter App

Bem-vindo ao **FutebolApp**!  
Um aplicativo moderno e intuitivo desenvolvido com **Flutter**, que permite visualizar **campeonatos**, **times** e **detalhes dos clubes de futebol**, com suporte a **login de usuário via Firebase Authentication**.

---

## ✨ Funcionalidades

- 🔐 **Autenticação** de usuários com Firebase (login e cadastro)
- 🏆 **Listagem de campeonatos de futebol** com dados da API-Football
- 🧩 **Visualização de times por liga**
- 🖼️ **Exibição de detalhes do time** (nome, escudo, etc.)
- 📌 **Estrutura pronta para favoritar times** com Firestore
- 🚀 Integração com API-Football (v3)

---

## 🛠️ Tecnologias

- 🚀 **Flutter** — Framework para desenvolvimento multiplataforma
- 💻 **Dart** — Linguagem oficial do Flutter
- ☁️ **Firebase Authentication** — Gerenciamento de usuários
- 🔥 **Cloud Firestore** — Base para funcionalidades de favoritos
- 🌍 **API-Football** — Dados de futebol em tempo real
- 📦 **Provider** — Gerenciamento de estado
- 🌐 **HTTP** — Requisições de API

---

## 🖼️ Prévia do App

| Tela de Campeonatos | Tela de Times |
|:--------------------:|:-------------:|
| ![Ligas](https://github.com/user-attachments/assets/ligas-placeholder.png) | ![Times](https://github.com/user-attachments/assets/times-placeholder.png) |

| Detalhes do Time | Login |
|:----------------:|:-----:|
| ![Detalhes](https://github.com/user-attachments/assets/time-detalhes-placeholder.png) | ![Login](https://github.com/user-attachments/assets/login-placeholder.png) |

> **Observação:** Imagens meramente ilustrativas. Substitua pelos screenshots do seu app real.

---

## 🔐 Firebase Authentication

O gerenciamento de usuários é feito diretamente pelo **Firebase Authentication**, permitindo login e cadastro com e-mail/senha de forma segura e rápida.

![Firebase](https://github.com/user-attachments/assets/firebase-auth-placeholder.png)

---

## 🌍 Integração com API-Football

Consome dados diretamente da [API-Football](https://www.api-football.com/) utilizando endpoints como:

- `/leagues` — Lista de ligas e campeonatos
- `/teams` — Times participantes por temporada

---

## 🧰 Como rodar o projeto

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/futebol_app.git
cd futebol_app
