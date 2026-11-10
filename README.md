#  Sistema Musical - Versão Dinâmica (PHP & MySQL)


Bem-vindo ao repositório do **Sistema Musical**! Esta é a evolução do nosso projeto desenvolvido em sala de aula, que agora conta com um **backend completo**. O sistema deixou de ser estático e passou a gerenciar dados reais, contando com autenticação segura de usuários, comunicação com banco de dados e operações de CRUD (Criar, Ler, Atualizar e Deletar) para artistas e músicas.


#  Tecnologias Utilizadas
**Frontend:** HTML5, CSS3 (styles.css)
**Backend:** PHP
**Banco de Dados:** MySQL
#  Estrutura do Projeto e Arquivos


Abaixo está o detalhamento de cada arquivo desenvolvido nesta etapa de integração:


**Banco de Dados e Configuração**
  * bd.sql: Script de criação do banco de dados e das tabelas necessárias (usuários, artistas, músicas).
  * conexao.php: Arquivo responsável por estabelecer a comunicação segura entre as páginas PHP e o banco de dados MySQL.
**Segurança e Autenticação**
  * login.php: Página de entrada convertida para PHP para validar as credenciais no banco de dados.
  * geraSenha.php: Script utilitário para gerar hashes de senha seguros (criptografia) para os usuários no banco de dados.
  * valida_sessao.php: Script incluído nas páginas protegidas para garantir que apenas usuários logados possam acessar o sistema.
  * logout.php: Encerra a sessão ativa do usuário e o redireciona de volta para a tela de login.
**Interface Dinâmica (CRUD)**
  * index.php: Dashboard principal, agora protegido por sessão e com saudações dinâmicas.
  * cadastro_artista.php: Formulário que envia os dados do novo artista diretamente para o banco de dados via método POST.
  * cadastro_musica.php: Interface para inserção de novas faixas associadas aos artistas cadastrados no banco.
  * listagem_musicas.php: Página que realiza consultas (SELECT) no banco de dados para renderizar a tabela de músicas dinamicamente na tela.
  * styles.css: Mantém toda a identidade visual, estruturação e responsividade do sistema[cite: 7].



##  Autoria


 **Miguel Porto**
