---

# Descrição do Projeto: Minha Estante Virtual

## Visão Geral do Cliente

Olá!

Estou buscando o desenvolvimento de uma **"Minha Estante Virtual"**, uma página web pessoal para catalogar e exibir meus livros. O objetivo principal é ter um espaço online organizado onde eu possa registrar os livros que já li, os que estou lendo e os que desejo ler. Quero que a página seja visualmente agradável, fácil de usar e que transmita meu amor pela leitura.

Pense nisso como um **portfólio interativo dos meus interesses literários**. Não preciso de funcionalidades complexas de banco de dados ou login de usuário; o foco é no front-end para praticar HTML, CSS e JavaScript.

---

## Estrutura e Conteúdo da Página

A página deverá ser dividida em seções claras para organizar os livros. A ideia é que cada livro seja apresentado como um **"card"** individual, contendo as informações essenciais.

### Seções Principais:

1.  **Cabeçalho (Header):**
    * Um título chamativo, como "Minha Estante Virtual" ou "Biblioteca Pessoal".
    * Uma pequena frase de efeito sobre leitura.
    * Talvez um ícone sutil relacionado a livros.

2.  **Menu de Navegação:**
    * Links que permitam ao usuário navegar rapidamente entre as seções: "Lidos", "Lendo Agora" e "Lista de Desejos".

3.  **Seção "Lidos":**
    * Um título claro.
    * Uma galeria de cards para os livros que já foram lidos.

4.  **Seção "Lendo Agora":**
    * Um título.
    * Um ou mais cards para os livros que estão sendo lidos no momento.

5.  **Seção "Lista de Desejos":**
    * Um título.
    * Cards para os livros que eu quero ler no futuro.

6.  **Rodapé (Footer):**
    * Informações simples, como "Criado por [Seu Nome]" e o ano.

### Conteúdo de Cada Card de Livro:

Cada card de livro deve conter:
* **Capa do Livro:** Imagem da capa (essencial!).
* **Título do Livro.**
* **Autor(es).**
* **Breve Sinopse/Minha Opinião:** Um parágrafo curto sobre o livro ou o porquê de ele estar na lista.
* **Gênero(s):** Ex: "Ficção Científica", "Fantasia", "Romance".
* **Ano de Publicação.**
* **Nota Pessoal (Opcional):** Você pode implementar um sistema simples de estrelas (3 a 5 estrelas) apenas com CSS/HTML para os livros "Lidos".

---

## Design e Experiência do Usuário (CSS)

O design é crucial para a Estante Virtual. Quero que seja **limpo, moderno e responsivo**, adaptando-se bem a telas de celulares, tablets e computadores.

### Ideias de Estilo:

* **Layout de Grid ou Flexbox:** Para organizar os cards de forma eficiente nas seções. Os cards devem se ajustar dinamicamente ao tamanho da tela.
* **Cores:** Uma paleta de cores agradável e não muito chamativa, talvez tons suaves ou terrosos combinados com um toque de cor para destaque.
* **Tipografia:** Escolha de fontes legíveis e que combinem com o tema literário. Títulos podem ter uma fonte mais impactante, enquanto o corpo do texto deve ser claro.
* **Efeitos de Hover:** Ao passar o mouse sobre um card de livro, algo sutil deve acontecer (ex: uma leve elevação, uma sombra, ou um efeito de escala).
* **Sombras e Bordas Arredondadas:** Podem ser usadas nos cards para dar uma aparência mais profissional e agradável.
* **Espaçamento:** Garanta bom espaçamento entre os elementos para evitar a sensação de "congestionamento".

---

## Funcionalidades Interativas (JavaScript)

Para dar vida à página e demonstrar suas habilidades em JavaScript, algumas interações seriam bem-vindas.

### Sugestões de Interatividade:

* **Filtragem de Livros:**
    * Um campo de busca simples no cabeçalho ou logo abaixo do menu. Ao digitar, os cards de livros devem ser filtrados em tempo real (ou ao apertar Enter), mostrando apenas aqueles que correspondem ao título ou autor digitado.
    * **Botões de filtro por Gênero:** Pense em botões (ex: "Mostrar Fantasia", "Mostrar Ficção Científica") que, ao serem clicados, escondam os cards de outros gêneros e mostrem apenas os do gênero selecionado. Um botão "Mostrar Todos" deve resetar o filtro.

* **"Marcar como Lido" / "Adicionar à Lista":**
    * Para praticar, você pode adicionar um pequeno botão ou ícone nos cards da "Lista de Desejos" que, ao ser clicado, "moveria" visualmente o livro para a seção "Lidos" (isso não precisa ser persistente no backend, apenas uma mudança de classes CSS via JS para simular o movimento).

* **Navegação Suave (Smooth Scroll):**
    * Ao clicar nos links do menu de navegação, a página deve rolar suavemente até a seção correspondente.

---

## Conteúdo (Texto e Imagens)

Para facilitar seu trabalho, você pode obter o conteúdo da seguinte forma:

* **Imagens das Capas:**
    * Pesquise as capas dos livros no **Google Imagens**, **Amazon**, **Goodreads** ou diretamente nos sites das editoras. Salve-as em uma pasta `images/` no seu projeto.
    * Caso não encontre uma capa específica, você pode usar um placeholder simples.
* **Informações dos Livros (Título, Autor, Sinopse, Gênero, Ano):**
    * Use sites como **Goodreads.com** ou até mesmo a **Wikipédia** para coletar esses dados. Adapte a sinopse para ser bem curta e direta.
* **Seus Livros:** Escolha alguns livros que você realmente goste e que se encaixem nas categorias "Lidos", "Lendo Agora" e "Lista de Desejos". Pense em 5 a 10 livros para cada seção para começar.

---
## Estrutura de Pastas (Padrão de Organização)

Nossa estrutura de pastas segue uma abordagem limpa e funcional, sem enumeração numérica, priorizando nomes descritivos em `camelCase` (para JavaScript) e `kebab-case` (para HTML/CSS, quando aplicável) para maior clareza e manutenibilidade.

# Convenções de Nomenclatura

Para manter o código limpo, consistente e fácil de entender, este projeto segue convenções de nomenclatura específicas para diferentes tipos de arquivos e elementos.

---

## `kebab-case` para HTML, CSS e Nomes de Arquivos/Pastas Gerais

O **`kebab-case`** (`exemplo-de-nome`) é utilizado para:

* **Nomes de Pastas:** Todas as pastas do projeto (exceto a raiz principal) utilizam `kebab-case`.
    * Exemplo: `styles/`, `scripts/`, `assets/`, `docs/`
* **Nomes de Arquivos HTML e CSS:** Arquivos HTML (quando houver mais de um) e todos os arquivos CSS.
    * Exemplo: `index.html` (padrão, não se aplica o `-`), `main-styles.css`, `header-component.css`
* **Nomes de Arquivos de Mídia (Imagens, Ícones, etc.):** Para clareza e compatibilidade em URLs.
    * Exemplo: `book-cover-image.jpg`, `app-icon.png`
* **Classes e IDs no CSS e HTML:** Essencial para a padronização do CSS.
    * Exemplo: `.book-card-container`, `#main-header`, `id="reading-list-section"`
* **Atributos `data-*` no HTML:**
    * Exemplo: `data-book-id="123"`, `data-category="fiction"`

**Motivação:** O `kebab-case` é amplamente reconhecido e preferido para a web por ser amigável para URLs, legível e por evitar problemas de sensibilidade a maiúsculas/minúsculas em diferentes sistemas de arquivos.

---

## `camelCase` para JavaScript

O **`camelCase`** (`exemploDeNome`) é estritamente aplicado para todos os elementos dentro do JavaScript e para os nomes dos arquivos JavaScript.

* **Nomes de Arquivos JavaScript:**
    * Exemplo: `mainScript.js`, `bookFilterUtil.js`, `smoothScroll.js`
* **Variáveis e Constantes:**
    * Exemplo: `const bookTitle = "O Pequeno Príncipe";`, `let currentPage = 1;`
* **Funções:**
    * Exemplo: `function filterBooksByGenre() { ... }`, `function updateReadingStatus() { ... }`
* **Classes (se aplicável):**
    * Exemplo: `class BookCard { ... }`

**Motivação:** O `camelCase` é a convenção padrão da comunidade JavaScript, o que torna o código mais familiar e colaborativo para outros desenvolvedores, além de ser otimizado para a sintaxe da linguagem.

---

Ao seguir essas convenções, garantimos um código coeso e de alta qualidade em todo o projeto.