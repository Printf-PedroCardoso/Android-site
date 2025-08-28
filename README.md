# Projeto Android - Curiosidades de Tecnologia

Este projeto é a resolução do Desafio 10 do **Curso de HTML5 e CSS3** ministrado pelo professor Gustavo Guanabara, do Curso em Vídeo. O objetivo era construir uma página web responsiva do zero, aplicando os conhecimentos adquiridos ao longo do curso.

O site apresenta curiosidades sobre a história do mascote do sistema operacional Android, incluindo a origem do seu nome, suas primeiras versões e a inspiração para o seu design.

![Preview do Site](https://raw.githubusercontent.com/gustavoguanabara/html-css/master/desafios/d010/imagens/tela-site.png)

---

### 📋 Sobre o Desafio

A proposta do desafio era replicar uma página completa, com os seguintes requisitos:
* [cite_start]**Cabeçalho:** Com título, parágrafo e menu de navegação, utilizando um fundo com gradiente[cite: 13].
* [cite_start]**Conteúdo Principal:** Artigo com títulos, parágrafos, imagens, um vídeo incorporado do YouTube e links externos[cite: 13, 14].
* [cite_start]**Layout Responsivo:** O site deveria se adaptar a diferentes tamanhos de tela, especialmente para dispositivos móveis[cite: 16].
* **Estilização Avançada:**
    * Uso de fontes personalizadas.
    * Imagens que se adaptam ao tamanho da tela (`<picture>`).
    * [cite_start]Listas estilizadas com marcadores personalizados[cite: 14].
    * Uma seção de conteúdo extra com fundo e bordas arredondadas.
* [cite_start]**Rodapé:** Uma área final com links[cite: 15].

---

### 🚀 Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

* **HTML5:** Para a estruturação semântica do conteúdo.
* **CSS3:** Para a estilização, layout e responsividade da página. Foram aplicados conceitos como:
    * `@font-face` para fontes personalizadas.
    * Gradientes (`linear-gradient`).
    * Sombreamento (`box-shadow` e `text-shadow`).
    * Media Queries (indiretamente, através da tag `<picture>`).

---

### 📂 Estrutura do Repositório

O repositório está organizado da seguinte forma:

├── index.html                  # Arquivo principal da página
├── style.css                   # Folha de estilos
└── pacote-projeto-d010/        # Pasta com os recursos do projeto
  ├── imagens/                # Contém todas as imagens utilizadas
  ├── android-site.txt        # Contém os textos utilizados
  └── fontes/                 # Contém a fonte personalizada 'idroid'

---

### ✨ Funcionalidades Implementadas

* **Header com Gradiente:** O cabeçalho utiliza um gradiente de cores verdes, conforme solicitado no desafio.
* **Fonte Personalizada:** A fonte "idroid" foi importada e aplicada nos títulos `<h1>` e `<h2>` para dar uma identidade visual ao projeto.
* **Responsividade de Imagens:** As imagens principais (`dan-droids.png` e `irina-blok.jpg`) são carregadas em versões menores para telas com largura de até 820px, otimizando o desempenho.
* **Vídeo Incorporado:** Um vídeo do YouTube sobre a história do Android foi adicionado utilizando um `<iframe>`.
* [cite_start]**Links Estilizados:** Links externos possuem uma formatação especial e um emoji para identificação visual[cite: 14].
* **Seção "Quer aprender mais?":** Uma área de destaque foi criada com um layout de duas colunas para a lista de versões do Android, dentro de uma caixa com estilização própria.

---

### 🙏 Créditos

Este projeto foi desenvolvido como parte do **Curso de HTML5 e CSS3**. [cite_start]Todos os créditos do conceito, design e materiais (textos, imagens e fontes) são do professor **Gustavo Guanabara**[cite: 6].

* [cite_start]**Repositório Original do Desafio:** [GitHub - gustavoguanabara](https://github.com/gustavoguanabara/) [cite: 6, 8, 20, 51, 62]
* [cite_start]**Curso Gratuito:** [Curso em Vídeo](http://youtube.com/cursoemvideo/playlists) [cite: 57]

---
