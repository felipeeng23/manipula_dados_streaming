# 🎶 Streaming de Música - Banco de Dados

Este repositório contém um projeto de manipulação de dados de **streaming de música**, simulando um sistema de gerenciamento de usuários, artistas, álbuns, músicas e playlists em uma plataforma de streaming.

## 📝 Descrição

O projeto consiste na criação e manipulação de um banco de dados que modela uma plataforma de streaming de música, abordando tabelas como **usuários**, **artistas**, **álbuns**, **músicas**, **playlists** e a relação entre elas. Através de operações **CRUD** (Criar, Ler, Atualizar, Deletar), o repositório demonstra como interagir com dados em um sistema de gerenciamento de banco de dados (SGBD) usando SQL.

## 💻 Tecnologias Utilizadas

- **Banco de Dados**: MySQL / MariaDB
- **SQL**: Consultas de criação, manipulação e exclusão de dados
- **Ferramentas**: MySQL Workbench ou qualquer outro cliente SQL

## 🔧 Funcionalidades

- **Criação de Tabelas**: Estruturação do banco de dados com tabelas como `usuarios`, `artistas`, `albuns`, `musicas`, `playlists`, e a tabela de relacionamento `playlist_musicas`.
- **Inserção de Dados**: Exemplos de inserção de dados fictícios para alimentar as tabelas.
- **Manipulação de Dados**: Comandos de `UPDATE`, `DELETE` e `ALTER TABLE` para modificar, excluir e ajustar a estrutura das tabelas.
- **Relacionamento de Tabelas**: Utilização de chaves estrangeiras para criar relações entre artistas, álbuns, músicas e playlists.

## 🚀 Como Usar

1. Clone este repositório em sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/streaming-de-musica.git
2. Importe o arquivo SQL para o seu banco de dados:

Abra o MySQL Workbench ou qualquer outro cliente SQL.
Crie um novo banco de dados:
sql
Copiar
CREATE DATABASE streaming_musica;
Importe o arquivo SQL com as tabelas e dados fictícios.
sql
Copiar
source caminho/para/o/arquivo.sql;

3. Execute os comandos SQL para manipulação de dados:

4. Insira, altere ou exclua registros nas tabelas de usuarios, artistas, albuns, musicas e playlists.

## 📚 O que você aprenderá
Como modelar um banco de dados para uma plataforma de streaming.
Como utilizar SQL para manipulação de dados, incluindo inserções, atualizações e exclusões.
Como usar relações entre tabelas para simular um sistema de recomendação de músicas.
Práticas de normalização de dados e otimização de consultas em bancos relacionais.
## 🚧 Roadmap
 Criar estrutura inicial do banco de dados.
 Inserir dados fictícios nas tabelas.
 Implementar funções de busca e recomendação de músicas.
 Adicionar mais funcionalidades, como gerenciamento de playlists personalizadas.
## 👥 Contribuições
Contribuições são bem-vindas! Se você tiver ideias para melhorar este projeto ou encontrar algum erro, fique à vontade para criar uma issue ou enviar um pull request.

## 🔗 Links Úteis
https://dev.mysql.com/doc/

