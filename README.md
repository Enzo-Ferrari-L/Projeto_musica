# Sistema Musical - Front-End

Este repositório contém o desenvolvimento do front-end completo para o Sistema Musical, construído ao longo das Aulas 1 a 4. O projeto apresenta uma interface responsiva, estilizada de forma centralizada e preparada para integração com Back-End (PHP / Banco de Dados na Sprint 2).

 Estrutura de Arquivos

O projeto é organizado com todos os arquivos na raiz da aplicação e centralização de estilo:

.
├── login.html             # Tela 1: Autenticação de Usuário
├── index.html             # Tela 2: Menu Principal Navegável
├── cadastro_artista.html  # Tela 3: Cadastro e Listagem de Artistas (Criadores)
├── cadastro_musica.html   # Tela 4: Cadastro e Listagem de Músicas (Obras)
├── listagem_musicas.html  # Tela 5: Biblioteca Musical com Filtros
└── styles.css             # Folha de estilos única centralizada (:root)


 Telas do Sistema

Login (login.html): Tela centralizada com formulário de autenticação, validação de campos obrigatórios (required) e exibição de credenciais de teste (admin / 123).

Menu Principal (index.html): Painel (Dashboard) com navegação em grade (menu-grid) direcionando para as demais funcionalidades.

Cadastro de Artista (cadastro_artista.html): Formulário em 2 colunas para cadastro do criador com suporte a upload de imagem (enctype="multipart/form-data"), além da tabela de artistas cadastrados.

Cadastro de Música (cadastro_musica.html): Formulário completo para cadastro da obra musical (título, artista via <select>, álbum, gênero, link do YouTube, capa e letra) e tabela local de dados.

Biblioteca Musical (listagem_musicas.html): Tela de exibição das obras cadastradas com barra de filtros (busca geral, por artista e por gênero) e ações diretas (Assistir no YouTube, Editar e Excluir).

 Recursos e Tecnologias

HTML5 Semântico: Estruturação limpa com tags semânticas, acessibilidade básica e formulários preparados para submissão POST/GET.

CSS3 Moderno:

Variáveis CSS (:root): Gerenciamento centralizado da paleta de cores (--primary, --blue, --green, --red, etc.), sombras e espaçamentos.

Layout Flexbox e CSS Grid: Alinhamento adaptativo para cartões, formulários de 2 colunas (form-grid) e tabelas.

Design Responsivo (@media max-width: 768px): Adaptação automática para dispositivos móveis (tabelas com rolagem horizontal, botões empilhados e formulários em coluna única).
