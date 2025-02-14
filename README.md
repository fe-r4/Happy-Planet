# 🌍 Aplicativo - CRUD de Planetas com Flutter e SQLite

## 💀 Sobre o Projeto
Este aplicativo foi desenvolvido para gerenciar informações de planetas fictícios, implementando um sistema CRUD (Create, Read, Update, Delete) utilizando Flutter e SQLite.

🔹 **Objetivo:** Criar um app responsivo, com um design moderno e persistência de dados local.  
🔹 **Destaques:** Interface intuitiva, design atualizado e armazenamento eficiente via banco de dados local.

## 🛠️ Tecnologias Utilizadas
📌 **Linguagem:** Dart  
📌 **Framework:** Flutter  
📌 **Banco de Dados:** SQLite  
📌 **Arquitetura:** MVC (Model-View-Controller)  
📌 **IDE:** Project IDX  
📌 **Emulador:** Android Studio  

## 🔥 Funcionalidades do Aplicativo
✅ Cadastrar um novo planeta (Nome, Distância do Sol, Tamanho e Apelido opcional)  
✅ Listar planetas cadastrados  
✅ Visualizar detalhes de um planeta  
✅ Editar as informações do planeta  
✅ Excluir planetas com confirmação antes da exclusão  
✅ Persistência dos dados no SQLite  
✅ Design moderno e responsivo  

## 🎨 Interface do Usuário (UI)
- **Tela inicial:** Lista de planetas cadastrados.  
- **Tela de Cadastro/Edição:** Formulário para adicionar ou modificar um planeta.  
- **Tela de Detalhes:** Exibição completa das informações de um planeta.  
- **Design atualizado:** Estilo minimalista, cores escuras e experiência fluida.  

## 🛠️ Como Executar o Projeto
1️⃣ **Instalar as dependências**  
```sh
flutter pub get
```
2️⃣ **Rodar o aplicativo no emulador/dispositivo**  
```sh
flutter run
```
💡 **Dica:** Certifique-se de que o emulador Android ou um dispositivo físico está conectado antes de rodar o app.

## 📚 Estrutura do Projeto
```
crud_planetas/
│── lib/
│   ├── main.dart                # Tela principal (lista de planetas)
│   ├── modelos/
│   │   ├── planeta.dart          # Modelo de dados do planeta
│   ├── controles/
│   │   ├── controle_planeta.dart # Lógica do CRUD (banco de dados)
│   ├── telas/
│   │   ├── tela_planeta.dart      # Tela de cadastro/edição
│── android/ (código nativo Android)
│── assets/ (imagens e ícones)
│── pubspec.yaml  # Dependências do Flutter
│── README.md  # Informações do projeto
```

## 🏆 Requisitos Atendidos
✔ CRUD completo com validação de campos  
✔ Banco de Dados SQLite para persistência local  
✔ Código modular e organizado seguindo o padrão MVC  
✔ Confirmação antes de excluir um planeta  
✔ Design atualizado e responsivo  
✔ Comentários explicativos no código  

---  
🚀 **Este projeto foi programado por fe-r4!**  
