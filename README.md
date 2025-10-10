# 📘 Aula de HTML: Estrutura e Ferramentas 🔧🌐

Anotações da aula sobre HTML, com foco em estruturação, ferramentas e boas práticas para iniciantes.

---

## 👨‍🏫 Autor

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/79340989?s=400&u=fcfb57bc9a07b8ce0eeae1195e243bb1cb56f6d8&v=4" width=115><br><sub>Claudeny Avelino</sub>](https://github.com/ClaudenyAvelino)

---

## 🚀 Tecnologias

![HTML](https://img.shields.io/badge/HTML-239120?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-239120?\&style=for-the-badge\&logo=css3\&logoColor=white)

---

## 📑 Conteúdo da Aula

### 1. A Importância da Documentação W3Schools 📚

A W3Schools é uma excelente fonte para aprender HTML e outras tecnologias web.
🔗 [Acesse W3Schools](https://www.w3schools.com/)

---

### 2. O que é HTML? 🤔

**HTML (HyperText Markup Language)** é uma linguagem de marcação usada para estruturar conteúdo na web. Ela **não executa ações**, apenas organiza elementos como:

* Textos
* Imagens
* Links
* Listas

---

### 3. Estrutura Básica de um Documento HTML 🏗️

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Título da Página</title>
</head>
<body>
  <h1>Isso é um título</h1>
  <p>Isso é um parágrafo</p>
  <img src="html.png" alt="Logo do HTML5">
</body>
</html>
```

---

### 4. A Utilidade da Tag `<!DOCTYPE html>` ⚙️

* Define o documento como HTML5.
* Evita o **Quirks Mode** (modo de compatibilidade antiga nos navegadores).

---

### 5. Diferença entre `<head>` e `<body>` 💡

* `<head>`: Contém **metadados** (título da aba, links de estilo, scripts).
* `<body>`: Contém o **conteúdo visível** da página.

---

### 6. Atributo `alt` nas Imagens 🖼️

Melhora a **acessibilidade** e o **SEO** do site.

```html
<img src="assets/claudeny.png" alt="Professor Claudeny">
```

---

### 7. Developer Tools 🔍

Ferramentas do navegador para:

* Inspecionar HTML/CSS
* Depurar erros
* Testar alterações em tempo real

Acessos rápidos:

* `F12`
* `Ctrl + Shift + I`

---

### 8. Quirks Mode 🤖

Modo de renderização "antigo".
**Evite sempre iniciando seus documentos com:**

```html
<!DOCTYPE html>
```

---

### 9. Extensão Live Server no VS Code 🔌

Permite:

* Atualização automática da página no navegador
* Visualização em tempo real de alterações

**Como instalar:**

1. Abrir VS Code
2. Ir em Extensões (`Ctrl+Shift+X`)
3. Procurar por *Live Server*
4. Clicar em **Instalar**

---

### 🧱 Estrutura Semântica do HTML5

```html
<body>
  <header></header> <!-- Cabeçalho -->
  <main></main>     <!-- Conteúdo principal -->
  <footer></footer> <!-- Rodapé -->
</body>
```

---

### ✨ Exemplo de Projeto

```
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8"> 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header></header>
      <main class="apresentacao">
        <section>
            <h1>Eleve seu negócio digital a outro nível <strong class="titulo-destaque">com um Front-end de qualidade!</strong></h1>
            <p>Olá! Sou Joana Santos, desenvolvedora Front-end com especialidade em React, HTML e CSS. Ajudo pequenos negócios e designers a colocarem em prática boas ideias. Vamos conversar?
            </p>
            <a href="https://instagram.com/">Instagram</a>
            <a href="https://github.com/">Github</a>
        </section>
        <img src="/guia/aulaAleatoria/Imagem.png" alt="Foto da claudeny programando">
    </main>
    <footer></footer>
</body>
</html>

```

# 📘 Aula: Atributos HTML

## ✨ O que são atributos HTML?

Atributos HTML são usados para fornecer **informações adicionais** sobre os elementos HTML.

- Sempre aparecem na **tag de abertura**.
- São definidos como **pares nome/valor**: `nome="valor"`.
- Podem ser usados em **quase todos os elementos HTML**.

---

## ✅ Sintaxe

```html
<tag atributo="valor">Conteúdo</tag>
```

Exemplo:

```html
<img src="img_girl.jpg" alt="Menina com jaqueta">
```

---

## 🔗 Atributo href
Usado para criar links com a tag `<a>`.

```html
<a href="https://www.w3schools.com">Visite o W3Schools</a>
```

---

## 🖼️ Atributo src
Usado para indicar o caminho da imagem na tag `<img>`.

```html
<img src="img_girl.jpg">
```

- `src="https://..."` → URL absoluta (imagem externa)  
- `src="imagem.jpg"` → URL relativa (imagem local)  

---

## 📏 Atributos width e height
Definem o tamanho da imagem em pixels.

```html
<img src="img_girl.jpg" width="500" height="600">
```

---

## 🆎 Atributo alt
Texto alternativo para imagens. Exibido se a imagem não carregar.

```html
<img src="img_girl.jpg" alt="Menina com jaqueta">
```

👉 Importante para acessibilidade e SEO.  

---

## 🎨 Atributo style
Aplica estilos CSS diretamente no elemento.

```html
<p style="color:red;">Este é um parágrafo vermelho.</p>
```

---

## 🌍 Atributo lang
Define o idioma da página. Muito usado na tag `<html>`.

```html
<html lang="pt-BR">
```

👉 Ajuda motores de busca e leitores de tela.  

---

## 💬 Atributo title
Exibe um tooltip (dica) ao passar o mouse sobre o elemento.

```html
<p title="Sou uma dica">Passe o mouse aqui</p>
```

---

## 📌 Boas práticas
✔ Use nomes de atributos em minúsculas  
✔ Sempre coloque os valores entre aspas  
✔ Use URLs relativas quando possível  
✔ Use `alt` nas imagens para acessibilidade  

⚠️ Aspas simples ou duplas? Ambas funcionam:

```html
<p title='John "ShotGun" Nelson'></p>
<p title="John 'ShotGun' Nelson"></p>
```

---

## 📋 Tabela Resumo

| **Atributo**   | **Função**                          |
|----------------|-------------------------------------|
| href           | Define o destino de um link         |
| src            | Define o caminho da imagem          |
| width/height   | Define o tamanho da imagem          |
| alt            | Texto alternativo da imagem         |
| style          | Estilização inline                  |
| lang           | Define o idioma da página           |
| title          | Texto exibido ao passar o mouse     |

---

## 🧠 Quiz rápido
Qual das opções abaixo está correta?  

A) `<img src='img_girl.jpg'>`  
B) `<img src('img_girl.jpg')>`  
C) `<img src:'img_girl.jpg'>`  



# CSS – Página de Apresentação
```
/* Remove margens e paddings padrão de todos os elementos */
* {
    margin: 0;
    padding: 0;
}


body {
    height: 100vh; /* Altura total da viewport (tela visível) */
    box-sizing: border-box; /* Inclui padding e borda no cálculo de largura/altura */
    background-color: #04aa6d; /* Fundo preto */
    color: #F6F6F6; /* Texto em cinza claro */
}

/* Container para os links (botões) */
 main{
    display: flex; /* Layout em linha */
    justify-content: space-between; /* Espaço uniforme entre os botões */
}

```


# 🎓 Aula de CSS – Página de Apresentação

Este repositório contém uma introdução prática ao **CSS**, com foco em estilização de páginas, boas práticas e aplicação em layouts modernos.

---


## 📑 Conteúdo da Aula

### 1️⃣ Importando Fontes Personalizadas

```css
@import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Montserrat:wght@400;600&display=swap');
```

* **Krona One** → usada no título
* **Montserrat** → usada nos textos e botões

---

### 2️⃣ Resetando o Estilo Padrão

```css
* {
    margin: 0;
    padding: 0;
}
```

Remove margens e paddings padrão do navegador para garantir consistência no layout.

---

### 3️⃣ Estilizando o `body`

```css
body {
    height: 100vh;
    box-sizing: border-box;
    background-color: #000000;
    color: #F6F6F6;
}
```

---

### 4️⃣ Criando Destaques com Cores

```css
.titulo-destaque {
    color: #22D4FD;
}
```

---

### 5️⃣ Estrutura Principal: `.apresentacao`

```css
.apresentacao {
    margin: 10%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
```

---

### 6️⃣ Área de Texto: `.apresentacao__conteudo`

```css
.apresentacao__conteudo {
    width: 615px;
}
```

---

### 7️⃣ Título do Texto

```css
.apresentacao__conteudo__titulo {
    font-size: 36px;
    font-family: 'Krona One', sans-serif;
}
```

---

### 8️⃣ Parágrafo Descritivo

```css
.apresentacao__conteudo__texto {
    font-size: 24px;
    font-family: 'Montserrat', sans-serif;
}
```

---

### 9️⃣ Botões de Link

```css
.apresentacao__links {
    display: flex;
    justify-content: space-between;
}

.apresentacao__links__link {
    background-color: #22D4FD;
    width: 280px;
    text-align: center;
    border-radius: 16px;
    font-size: 24px;
    font-weight: 600;
    padding: 21.5px 0;
    text-decoration: none;
    color: #000000;
    font-family: 'Montserrat', sans-serif;
}
```

---

## 🖼 Resultado Visual Esperado

* Página escura, texto claro
* Lado esquerdo: título, parágrafo e botões
* Lado direito: imagem ou ilustração

---

## 🎒 Exercício Prático

1. Crie um arquivo `style.css` com o código acima.
2. Crie um HTML com a seguinte estrutura:

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Apresentação</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <section class="apresentacao">
    <div class="apresentacao__conteudo">
      <h1 class="apresentacao__conteudo__titulo">
        Eleve seu negócio com <strong class="titulo-destaque">tecnologia</strong>
      </h1>
      <p class="apresentacao__conteudo__texto">
        Desenvolvedor apaixonado por soluções criativas.
      </p>
      <div class="apresentacao__links">
        <a class="apresentacao__links__link" href="#">GitHub</a>
        <a class="apresentacao__links__link" href="#">LinkedIn</a>
      </div>
    </div>
    <img src="imagem.png" alt="Imagem de apresentação" />
  </section>
</body>
</html>
```

---

## 📌 Dicas

* Use **Live Server** no VS Code para visualizar alterações em tempo real.
* Experimente alterar cores, fontes e tamanhos para entender o impacto no layout.
* Teste o CSS em diferentes navegadores e resoluções para melhorar responsividade.


# 🎨 Aula: Google Fonts — Como Usar Fontes Personalizadas no seu Site

## ✅ Objetivo da Aula
Ensinar como utilizar a biblioteca **Google Fonts** para aplicar diferentes fontes em projetos web com **HTML** e **CSS**.

---

## 📌 O que é o Google Fonts?
O **Google Fonts** é uma biblioteca gratuita do Google com mais de **1000 fontes tipográficas** de código aberto.  
Ele permite que você utilize essas fontes facilmente em sites, sistemas ou qualquer projeto web.

- ✅ Licença livre para uso pessoal e comercial  
- ✅ Compatível com todos os navegadores modernos  
- ✅ Fácil de integrar via HTML ou CSS  

🔗 [Acesse o site oficial do Google Fonts](https://fonts.google.com)

---

## 🧭 Como Navegar no Google Fonts
1. Acesse [https://fonts.google.com](https://fonts.google.com)  
2. Use os filtros para buscar por:  
   - Categoria (Serif, Sans Serif, Display etc.)  
   - Estilo (Regular, Italic, Bold...)  
   - Idioma (incluindo suporte ao português)  
3. Clique em uma fonte para visualizar os estilos e como incorporá-la no seu projeto.  

---

## 📥 Como Importar Fontes

### 🔗 Via `<link>` no HTML
```html
<head>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
</head>
```

### 🧾 Via `@import` no CSS
```css
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
```

---

## 🎨 Como Usar a Fonte no CSS
Aplicar no corpo do texto:
```css
body {
  font-family: 'Roboto', sans-serif;
}
```

Aplicar em títulos:
```css
h1 {
  font-family: 'Lobster', cursive;
}
```

---

## 💡 Dica de Combinação de Fontes
Você pode combinar fontes diferentes para título e corpo do texto. Exemplo:

```html
<link href="https://fonts.googleapis.com/css2?family=Roboto&family=Lobster&display=swap" rel="stylesheet">
```

```css
h1 {
  font-family: 'Lobster', cursive;
}

p {
  font-family: 'Roboto', sans-serif;
}
```

---

## 📚 Leitura Recomendada
📖 [Guia oficial: Primeiros passos com a API Google Fonts](https://developers.google.com/fonts)

---

## 🧪 Atividade Prática
Crie uma página HTML utilizando **duas fontes do Google Fonts**:

1. Acesse o Google Fonts  
2. Escolha uma fonte para o título e outra para o parágrafo  
3. Crie um HTML simples com um `<h1>` e um `<p>`  
4. Importe as fontes e aplique no CSS  

### 💻 Exemplo de código completo:
```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Exemplo com Google Fonts</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&family=Lobster&display=swap" rel="stylesheet">
  <style>
    h1 {
      font-family: 'Lobster', cursive;
    }

    p {
      font-family: 'Roboto', sans-serif;
    }
  </style>
</head>
<body>
  <h1>Bem-vindo ao Google Fonts</h1>
  <p>Este é um exemplo utilizando fontes personalizadas do Google Fonts.</p>
</body>
</html>
```

# 📘 Aula Completa de HTML: Listas

Esta aula cobre os três principais tipos de listas em HTML, com exemplos, explicações e exercícios para iniciantes.

---

## 📌 O que são listas em HTML?

Listas são estruturas que agrupam itens relacionados para melhorar a organização e apresentação do conteúdo em páginas web.

---

## 🔹 Tipos de Listas

### 1. Lista Não Ordenada (`<ul>`)

Itens com marcadores (bolinhas), sem ordem específica.

#### Exemplo:

```html
<ul>
  <li>Maçã</li>
  <li>Banana</li>
  <li>Laranja</li>
</ul>
```

**Resultado:**
- Maçã  
- Banana  
- Laranja  

---

### 2. Lista Ordenada (`<ol>`)

Itens numerados, com ordem importante.

#### Exemplo:

```html
<ol>
  <li>Ligar o forno</li>
  <li>Preparar a massa</li>
  <li>Assar o bolo</li>
</ol>
```

**Resultado:**
1. Ligar o forno  
2. Preparar a massa  
3. Assar o bolo  

---

### 3. Lista de Definição (`<dl>`)

Termos e definições, usada para glossários.

#### Exemplo:

```html
<dl>
  <dt>HTML</dt>
  <dd>Linguagem para estruturar páginas web.</dd>
  <dt>CSS</dt>
  <dd>Folhas de estilo para aparência.</dd>
</dl>
```

**Resultado:**
- **HTML**  
  Linguagem para estruturar páginas web.  
- **CSS**  
  Folhas de estilo para aparência.  

---

## 🎨 Personalização de Listas

Você pode alterar marcadores e numeração com **CSS** ou atributos do HTML.

#### Exemplo:

```html
<ul style="list-style-type: square;">
  <li>Marcador quadrado</li>
  <li>Outro item</li>
</ul>

<ol type="A">
  <li>Numeração em letras maiúsculas</li>
</ol>
```

---

## 📝 Exemplo Completo de Página HTML com Listas

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>Exemplo de Listas</title>
</head>
<body>

  <h1>Exemplo de Listas em HTML</h1>

  <h2>Lista Não Ordenada</h2>
  <ul>
    <li>Arroz</li>
    <li>Feijão</li>
    <li>Leite</li>
  </ul>

  <h2>Lista Ordenada</h2>
  <ol>
    <li>Ferver a água</li>
    <li>Colocar o pó no coador</li>
    <li>Passar a água quente</li>
  </ol>

  <h2>Lista de Definição</h2>
  <dl>
    <dt>CPU</dt>
    <dd>Unidade Central de Processamento</dd>
    <dt>RAM</dt>
    <dd>Memória de acesso aleatório</dd>
  </dl>

</body>
</html>
```

---

## 🏋️ Exercícios

1. Crie uma lista não ordenada com seus **três filmes favoritos**.  
2. Crie uma lista ordenada com **passos para preparar seu prato favorito**.  
3. Monte um glossário simples com pelo menos **dois termos usando lista de definição**.  

---

## ✅ Conclusão

Listas são essenciais para organizar informações na web, melhorando a **legibilidade** e a **usabilidade** do conteúdo.

# 📘 Aula: `header`, `main`, `section` e `div` no HTML

Estas tags fazem parte da **estrutura de layout** em HTML. Algumas são **semânticas** (como `header`, `main` e `section`), ou seja, ajudam a dar significado ao conteúdo, enquanto outras são **genéricas** (como `div`), usadas para agrupamento e estilo.

---

## 🧭 `header` – Cabeçalho da página ou seção

- A `<header>` define o **cabeçalho de uma página ou seção**.
- Pode conter **título**, **logo**, **menu de navegação**, etc.
- Pode ser usada dentro de `<body>`, `<article>`, `<section>`...

```html
<header>
  <h1>Meu Site</h1>
  <nav>
    <a href="#inicio">Início</a>
    <a href="#contato">Contato</a>
  </nav>
</header>
```

---

## 🧱 `main` – Conteúdo principal

- A `<main>` contém o conteúdo **principal** da página.  
- Deve existir apenas **uma tag `<main>`** por página.  
- Não deve estar dentro de `header`, `footer`, `article` ou `aside`.  

```html
<main>
  <h2>Bem-vindo ao nosso site</h2>
  <p>Aqui você encontra as últimas novidades...</p>
</main>
```

---

## 📦 `section` – Seção do documento

- A `<section>` representa uma **seção temática** do conteúdo.  
- Deve conter um **título** (`<h1>` a `<h6>`) sempre que possível.  
- Ideal para dividir o conteúdo em partes lógicas dentro do `<main>`.  

```html
<section>
  <h2>Sobre Nós</h2>
  <p>Somos uma empresa focada em inovação...</p>
</section>
```

---

## 🔲 `div` – Contêiner genérico

- A `<div>` é usada como um **bloco genérico** para agrupar elementos.  
- Não tem significado semântico (não diz o tipo de conteúdo).  
- Muito usada com CSS para **layout** e **estilização**.  

```html
<div class="caixa">
  <p>Este parágrafo está dentro de uma div.</p>
</div>
```

---

## 🧠 Diferença entre as tags

| **Tag**   | **Tipo**     | **Uso principal**                        |
|-----------|--------------|-------------------------------------------|
| `header`  | Semântica    | Cabeçalho de página ou seção             |
| `main`    | Semântica    | Conteúdo principal da página             |
| `section` | Semântica    | Bloco com conteúdo relacionado e título  |
| `div`     | Genérica     | Agrupamento de elementos para layout e estilo |

---

## 📌 Exemplo completo

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Exemplo de Estrutura HTML</title>
</head>
<body>

  <header>
    <h1>Meu Portfólio</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#projetos">Projetos</a>
    </nav>
  </header>

  <main>
    <section id="sobre">
      <h2>Sobre Mim</h2>
      <p>Sou desenvolvedor front-end apaixonado por tecnologia.</p>
    </section>

    <section id="projetos">
      <h2>Meus Projetos</h2>
      <div class="projeto">
        <h3>Projeto 1</h3>
        <p>Descrição do projeto 1.</p>
      </div>
      <div class="projeto">
        <h3>Projeto 2</h3>
        <p>Descrição do projeto 2.</p>
      </div>
    </section>
  </main>

</body>
</html>
```

---

## ✅ Conclusão

- Use `header` para criar cabeçalhos com títulos e menus.  
- Use `main` para destacar o conteúdo principal da página.  
- Use `section` para organizar o conteúdo em blocos temáticos.  
- Use `div` para agrupar elementos sem significado semântico.  


---


## 📌 Exemplo Final HTML completo
```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="cabecalho">
        <nav class="cabecalho__menu">
            <a class="cabecalho__menu__link" href="index.html">Home</a>
            <a class="cabecalho__menu__link" href="sobre-mim.html">Sobre mim</a>
            <a class="cabecalho__menu__link" href="curriculum.html">Currículo</a>
        </nav>
    </header>
    <main class="apresentacao">
        <section class="apresentacao__conteudo">
            <h1 class="apresentacao__conteudo__titulo">Eleve seu negócio digital a outro nível <strong
                    class="titulo-destaque">com um Front-end de qualidade!</strong></h1>
            <p class="apresentacao__conteudo__texto">Olá! Sou Joana Santos, desenvolvedora Front-end com especialidade
                em React, HTML e CSS. Ajudo pequenos negócios e designers a colocarem em prática boas ideias. Vamos
                conversar?
            </p>
            <div class="apresentacao__links">
                <a class="apresentacao__links__link"  href="https://instagram.com/">Instagram</a>
                <a class="apresentacao__links__link"  href="https://github.com/">Github</a>
            </div>
        </section>
        <img src="/guia/aulaAleatoria/Imagem.png" alt="Foto da claudeny programando">
    </main>
    <footer class="rodape">
        <p>Desenvolvido por Claudeny avelino.</p>
    </footer>
</body>

</html>
```


## 📌 Exemplo Final CSS completo
```
@import url('https://fonts.googleapis.com/css2?family=Krona+One&family=Montserrat&display=swap');
:root {
    --cor-primaria: #000000;
    --cor-secundaria: #F6F6F6;
    --cor-terciaria: #22D4FD;


    --fonte-primaria: 'Krona One', sans-serif;
    --font-secundaria: 'Montserrat', sans-serif;
}

* {
    margin: 0;
    padding: 0;
}

body {
    /* height: 100vh; */
    box-sizing: border-box;
   /* background-color: #000000;*/
    background-color: var(--cor-primaria);
    color: #F6F6F6;
}

.titulo-destaque {
    color: #22D4FD;
}

.cabecalho {
    padding: 2% 0% 0% 15%;
}

.cabecalho__menu {
    display: flex;
    gap: 50px;
}
.cabecalho__menu__link {
    font-family: 'Montserrat', sans-serif;
    font-size: 24px;
    font-weight: 600;
    color: #22D4FD;
    text-decoration: none;
}
.apresentacao {
    /* margin:10% 15%; */
    padding: 5% 15%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.apresentacao__conteudo{
     width: 615px;
     display: flex;
     flex-direction: column;
     gap: 40px;
}
.apresentacao__conteudo__titulo{
    font-size: 36px;
    font-family: 'Krona One', sans-serif;
}
.apresentacao__conteudo__texto{
     font-size: 24px;
     font-family: 'Montserrat', sans-serif;
}
.apresentacao__links{
    display: flex;
    justify-content: space-between;
}
.apresentacao__links__link{
        background-color: #22D4FD;
    width: 280px;
    text-align: center;
    border-radius: 16px;
    font-size: 24px;
    font-weight: 600;
    padding: 21.5px 0;
    text-decoration: none;
    color: #000000;
    font-family: 'Montserrat', sans-serif;
}
.rodape {
    padding: 24px;
    color: #000000;
    background-color: #22D4FD;
    text-align: center;
    font-family: 'Montserrat', sans-serif;
    font-size: 24px;
    font-weight: 400;
}

/*Variáveis CSS*/
```

---
📚 **Atividade HTML e CSS**  
Acesse aqui

[![Formulario](assets/html-css.png)](https://forms.gle/Ku8EgGNLCYigmuAh6)
---

**Projeto final**
**HTML - index**

```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portifolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="cabecalho">
        <nav class="cabecalho__menu">
            <a class="cabecalho__menu__link" href="index.html">Home</a>
            <a class="cabecalho__menu__link" href="sobre-mim.html">Sobre mim</a>
            <a class="cabecalho__menu__link" href="curriculum.html">Currículo</a>
            <a class="cabecalho__menu__link" href="contato.html">Contato</a>
        
        </nav>
    </header>
    <main class="apresentacao">
        <section class="apresentacao__conteudo">
            <h1 class="apresentacao__conteudo__titulo">Eleve seu negócio digital a outro nível <strong
                    class="titulo-destaque">com um Front-end de qualidade!</strong></h1>
            <p class="apresentacao__conteudo__texto">Olá! Sou Joana Santos, desenvolvedora Front-end com especialidade
                em React, HTML e CSS. Ajudo pequenos negócios e designers a colocarem em prática boas ideias. Vamos
                conversar?
            </p>
            <div class="apresentacao__links">
                <a class="apresentacao__links__link" href="https://instagram.com/">Instagram</a>
                <a class="apresentacao__links__link" href="https://github.com/">Github</a>
            </div>
        </section>
        <img class="teacher" src="/guia/aulaAleatoria/Imagem.png" alt="Foto da claudeny programando">
    </main>
    <footer class="rodape">
        <p>Desenvolvido por Claudeny avelino.</p>
    </footer>
</body>

</html>

```

**Projeto final**
**HTML - sobre-mim**
```
 <!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre mim</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="cabecalho">
        <nav class="cabecalho__menu">
            <a class="cabecalho__menu__link" href="index.html">Home</a>
            <a class="cabecalho__menu__link" href="sobre-mim.html">Sobre mim</a>
            <a class="cabecalho__menu__link" href="curriculum.html">Currículo</a>
            <a class="cabecalho__menu__link" href="contato.html">Contato</a>
        </nav>
    </header>

    <main class="apresentacao">
        <section class="apresentacao__conteudo">
            <h1 class="apresentacao__conteudo__titulo">Sobre mim</h1>
            <p class="apresentacao__conteudo__texto">At vero eos et accusamus et iusto odio dignissimos ducimus qui
                blanditiis praesentium voluptatum deleniti
                atque corrupti quos dolores et quas molestias excepturi sint occaecati cupiditate non provident,
                similique sunt in culpa qui officia deserunt mollitia animi, id est laborum et dolorum fuga.</p>
            <p class="apresentacao__conteudo__texto">Et harum quidem rerum facilis est et expedita distinctio. Nam
                libero tempore, cum soluta nobis est
                eligendi optio cumque nihil impedit quo minus id quod maxime placeat facere possimus, omnis voluptas
                assumenda est, omnis dolor repellendus. Temporibus autem quibusdam et aut officiis debitis aut rerum
                necessitatibus saepe eveniet ut et voluptates repudiandae sint et molestiae non recusandae. Itaque earum
                rerum hic tenetur a sapiente delectus, ut aut reiciendis voluptatibus maiores alias consequatur aut
                perferendis doloribus asperiores ipsum delis forum birol parela maxime infena. Excepteur sint occaecat
                cupidatat non.</p>
        </section>
        <img src="/guia/aulaAleatoria/Imagem.png" alt="Foto da claudeny programando">
    </main>

    <footer class="rodape">
        <p>Desenvolvido por Claudeny Avelino.</p>
    </footer>
</body>

</html>


```

**Projeto final**
**HTML - curriculum**
```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="cabecalho">
        <nav class="cabecalho__menu">
            <a class="cabecalho__menu__link" href="index.html">Home</a>
            <a class="cabecalho__menu__link" href="sobre-mim.html">Sobre mim</a>
            <a class="cabecalho__menu__link" href="curriculum.html">Currículo</a>
            <a class="cabecalho__menu__link" href="contato.html">Contato</a>
            
        </nav>
    </header>
    <main class="apresentacao">
        <section class="apresentacao__conteudo">
            <h1 class="apresentacao__conteudo__titulo">Currículo</h1>
            <p class="apresentacao__conteudo__texto">Olá! Sou Claudeny Avelino, desenvolvedor Front-end com
                especialidade em React, HTML e CSS. Ajudo pequenos negócios e designers a colocarem em prática boas
                ideias. Vamos conversar?
            </p>
            <h2 class="apresentacao__conteudo__titulo">Experiências</h2>
            <div class="apresentacao__conteudo__titulo">
                <ul class="apresentacao__conteudo__texto">
                    <li>
                        SENAC tal (2020 - 2021) - Analista de Comunicação.
                    </li>
                    <li>
                        MP tal (2019 - 2020) - Analista Desenvolvimento WEB.
                    </li>
                </ul>
            </div>

            <h2 class="apresentacao__conteudo__titulo">Estudos</h2>
            <div class="apresentacao__conteudo__texto">
                <ul class="apresentacao__conteudo__texto">
                    <li>
                        UNIT tal (2020 - 2021) - Licenciatura
                    </li>
                    <li>
                        IFS tal (2019 - 2020) - Sistema de Informação
                    </li>
                    <li>
                        UFS tal (2019 - 2020) - Enfermagem
                    </li>
                </ul>
            </div>



        </section>
        <img src="/guia/aulaAleatoria/Imagem.png" alt="Foto da claudeny programando">
    </main>
    <footer class="rodape">
        <p>Desenvolvido por Claudeny.</p>
    </footer>

</body>

</html>
```

**Projeto final**
**HTML - contato**
```
<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contato</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header class="cabecalho">
        <nav class="cabecalho__menu">
            <a class="cabecalho__menu__link" href="index.html">Home</a>
            <a class="cabecalho__menu__link" href="sobre-mim.html">Sobre mim</a>
            <a class="cabecalho__menu__link" href="curriculum.html">Currículo</a>
            <a class="cabecalho__menu__link" href="contato.html">Contato</a>
        
        </nav>
    </header>

    <main class="apresentacao">
        <section class="apresentacao__conteudo">
            <h1 class="apresentacao__conteudo__titulo">Contato</h1>

            <form class="formulario-contato">
                <label for="fname">Primeiro nome:</label><br>
                <input type="text" id="fname" name="fname" value="Ana"><br>
                <label for="lname">Sobrenome::</label><br>
                <input type="text" id="lname" name="lname" value="Maria"><br><br>
                <input type="submit" value="Submit">
            </form>

        </section>
        <img src="/guia/aulaAleatoria/Imagem.png" alt="Foto da claudeny programando">
    </main>

    <footer class="rodape">
        <p>Desenvolvido por Claudeny Avelino.</p>
    </footer>
</body>

</html>

```



---


📂 **HTML5 e CSS3 - domine a web do futuro - Autor (Casa do Código)**  

[![Acesse aqui](/assets/html-livro.png)](https://1drv.ms/b/c/c939bce3230fd75c/EVzXDyPjvDkggMkWdwIAAAABp8OywWxNLbS7DM1ERZ7poA?e=ovmMBH)  

---

📚 **Indicação de Leitura**  

[![Livro de HTML e CSS](assets/livro-html-css.png)](https://www.amazon.com.br/HTML-CSS-Projete-construa-sites-Wyke/dp/8576089394)  

*Livro recomendado: "HTML e CSS – Projete e Construa Sites" de Jon Duckett.*  


