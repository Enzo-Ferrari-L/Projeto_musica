#  Sistema Musical

Sistema web completo para gerenciamento de artistas, álbuns e faixas musicais, desenvolvido com **HTML5** e **CSS3** (Flexbox, CSS Grid e Design Responsivo).

---

##  Sobre o Projeto

O **Sistema Musical** foi construído de forma modular ao longo de 4 etapas (Aulas), estruturando a interface de front-end, formulários interativos, tabelas de dados, filtros de busca e layouts responsivos para dispositivos móveis. A aplicação prepara a base visual completa para integração posterior com back-end em PHP e banco de dados.

---

##  Estrutura de Páginas

- **`login.html`**: Tela de autenticação centralizada com formulário de login e credenciais de teste (`admin` / `123`).
- **`index.html`**: Menu principal (Dashboard) com cartões de acesso rápido em grid para todas as funcionalidades do sistema.
- **`listagem_musicas.html`**: Biblioteca musical com visualização de faixas em tabela, filtros por busca/artista/gênero e ações rápidas (Editar, Excluir, Assistir no YouTube).
- **`cadastro_artista.html`**: Cadastro de artistas com upload de foto (`multipart/form-data`), campos estruturados em grade (`form-grid`) e tabela de artistas cadastrados.
- **`cadastro_musica.html`**: Cadastro de faixas com seleção de artista, link direto para o YouTube, upload da capa do álbum e campo amplo de texto (`textarea`) para a letra da música.
- **`styles.css`**: Folha de estilos unificada contendo variáveis globais (`:root`), reset CSS, utilitários, tabelas, botões padronizados e regras de responsividade.

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **HTML5 Semântico**: Uso de formulários com validações nativas (`required`, `type="url"`, `type="file"`), tabelas organizadas e tags semânticas.
- **CSS3 Moderno**:
  - **Variáveis CSS (`:root`)**: Padronização de paleta de cores (`--primary`, `--blue`, `--green`, `--red`) e sombras.
  - **Flexbox & CSS Grid**: Alinhamento de cabeçalhos (`page-header-bar`), menus em cards (`menu-grid`) e formulários de duas colunas (`form-grid`).
  - **Responsividade (`@media`)**: Layout adaptável para telas de até 768px (smartphones e tablets), empilhando campos e habilitando rolagem lateral em tabelas.

---

##  Estrutura do Repositório

```text
.
├── index.html              # Menu principal (Dashboard)
├── login.html              # Tela de autenticação
├── listagem_musicas.html   # Biblioteca de músicas e filtros
├── cadastro_artista.html   # Formulário e tabela de artistas
├── cadastro_musica.html    # Formulário e tabela de músicas
└── styles.css              # Folha de estilos unificada do sistema
