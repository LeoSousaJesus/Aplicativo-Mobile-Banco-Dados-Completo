# Aplicação Banco de Dados

Este é um aplicativo Android simples desenvolvido para demonstrar o uso do banco de dados local **SQLite** no Android. O aplicativo permite ao usuário criar um banco de dados, inserir registros (nome, telefone e e-mail) e consultar os dados cadastrados, navegando entre os registros (primeiro, anterior, próximo e último).

## Funcionalidades

- **Criação do Banco de Dados:** Permite a criação de um banco de dados SQLite local, com uma tabela `usuarios` para armazenar os registros.
- **Gravação de Registros:** Possibilita o cadastro de novos usuários com Nome, Telefone e E-mail.
- **Consulta de Dados:** Permite visualizar os registros gravados, com navegação pelos registros através de botões (Primeiro, Anterior, Próximo e Último).

## Estrutura do Projeto

O projeto é composto por três *Activities* principais:

*   **`MainActivity`**: A tela inicial do aplicativo, que contém as opções para Criar Banco de Dados, Cadastrar Dados e Consultar Dados.
*   **`GravaRegistrosActivity`**: A tela responsável pelo formulário de inserção de novos usuários no banco de dados.
*   **`ConsultaDadosActivity`**: A tela que exibe os dados gravados e permite a navegação entre os registros do banco de dados.

## Tecnologias e Ferramentas Utilizadas

*   **Java:** Linguagem de programação principal utilizada no desenvolvimento do aplicativo.
*   **Android SDK:** Framework de desenvolvimento para dispositivos Android (mínimo SDK 26, target SDK 34).
*   **SQLite:** Sistema de gerenciamento de banco de dados relacional leve e embutido, utilizado para armazenar os dados localmente no dispositivo.
*   **Gradle:** Sistema de automação de build (Plugin Android Application versão 8.7.2).

## Como Executar o Projeto

1.  Clone este repositório para o seu computador.
2.  Abra o projeto no **Android Studio**.
3.  Sincronize o projeto com os arquivos do Gradle (se não ocorrer automaticamente).
4.  Execute o aplicativo em um emulador ou em um dispositivo físico Android.

---
Desenvolvido como demonstração de operações CRUD básicas no Android com SQLite.
