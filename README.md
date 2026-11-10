
# 🎵 Sistema Musical PHP

Sistema de gerenciamento de catálogo musical desenvolvido em **PHP** e **MySQL**, criado como projeto de aprendizado no curso de Desenvolvimento de Sistemas do **SENAI Jacob Lafer**.

---

## 👤 Autor

- **Nome:** Miguel Caparroz Neves
- **Turma:** 1IDDS (Desenvolvimento de Sistemas)
- **Instituição:** SENAI Jacob Lafer

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** PHP
- **Banco de Dados:** MySQL
- **Interface:** HTML, CSS
- **Segurança:** Hash de senha com BCRYPT (`password_hash`) e requisições seguras com *Prepared Statements* (evitando SQL Injection)

---

## 🚀 Funcionalidades

- **Autenticação de Usuários:** Sistema de login seguro com controle de sessão (`valida_sessao.php`).
- **Gestão de Artistas (CRUD):**
  - Cadastrar artistas com nome, gênero, país e foto de perfil.
  - Redimensionamento e otimização automática de imagens enviadas.
  - Listagem, edição e remoção de artistas.
- **Gestão de Músicas (CRUD):**
  - Cadastrar músicas associadas a um artista.
  - Inserção de capa do álbum, gênero, letra e link do YouTube.
  - Tratamento e conversão de URLs do YouTube para reprodução/acesso direto.
- **Biblioteca Musical & Filtros:**
  - Busca geral por título, álbum ou artista.
  - Filtros dinâmicos por gênero e artista específico.
  - Remoção de arquivos de imagem físicos ao excluir registros do banco.

---

## 🗄️ Estrutura do Banco de Dados

O banco de dados é composto por três tabelas principais:
1. `usuarios`: Armazena credenciais de acesso.
2. `artistas`: Armazena informações dos artistas/bandas.
3. `musicas`: Armazena as faixas associadas aos artistas.

