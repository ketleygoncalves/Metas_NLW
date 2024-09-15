# Gerenciador de Metas

Este é um aplicativo de linha de comando (CLI) desenvolvido em Node.js, que permite gerenciar metas pessoais. O usuário pode cadastrar, listar, marcar metas como concluídas, verificar metas abertas, excluir metas e salvar tudo em um arquivo JSON para persistência de dados.

## Funcionalidades

- **Cadastrar meta**: Adiciona uma nova meta à lista.
- **Listar metas**: Mostra todas as metas e permite marcar como concluídas.
- **Metas realizadas**: Exibe as metas já concluídas.
- **Metas abertas**: Exibe as metas que ainda não foram concluídas.
- **Deletar metas**: Remove metas da lista.
- **Persistência de dados**: As metas são salvas em um arquivo `metas.json`.

## Tecnologias

- **Node.js**
- **@inquirer/prompts**: Para criar interfaces de prompt interativas.
- **fs (File System)**: Para ler e escrever em arquivos locais.

## Como utilizar

1. Clone o repositório:
   ```bash
   git clone https://github.com/ketley/exemplo-gerenciador-metas.git
   cd exemplo-gerenciador-metas
   ```
   
2.Instale as dependências:
   ```bash
   npm install
   ```

3.Execute o projeto:
   ```bash
   node app.js
   ```

## Estrutura do Projeto
  ```bash
├── app.js           # Arquivo principal da aplicação
├── metas.json       # Arquivo onde as metas são salvas
└── package.json     # Configuração do projeto e dependências

![image](https://github.com/user-attachments/assets/1683de18-8c7c-403a-8ac0-b75bd6b85516)
