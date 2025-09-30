<h2>Time</h2>

[<img loading="lazy" src="https://avatars.githubusercontent.com/u/79340989?s=400&u=fcfb57bc9a07b8ce0eeae1195e243bb1cb56f6d8&v=4" width=115><br><sub>Claudeny Avelino</sub>](https://github.com/ClaudenyAvelino)

## 🚀 Tecnologias
<div>
  <img src="https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white">
 <!--  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> -->
</div>

Aula de HTML: Estrutura e Ferramentas 🔧🌐
🔖 Sobre

Anotações da aula sobre HTML, com foco em estruturação, ferramentas e boas práticas para iniciantes.

📝 O que foi abordado nesta aula?
1. A Importância da Documentação W3S 📚

A W3Schools (W3S) é uma excelente fonte de aprendizado para quem está iniciando com HTML e outras tecnologias web. A documentação oferece explicações detalhadas sobre as tags, atributos e boas práticas do HTML.

Consultar a documentação é fundamental para entender as funcionalidades da linguagem e aprender como usá-las corretamente.

🔗 Link para a W3Schools: https://www.w3schools.com/

2. O que é HTML e Por que é Considerada uma Linguagem de Marcação? 🤔

HTML (HyperText Markup Language) é uma linguagem de marcação usada para estruturar conteúdo na web. Diferente das linguagens de programação, HTML não executa ações ou processos lógicos, mas define a estrutura de uma página da web, como textos, imagens, links, e muito mais.

Marcação: A linguagem usa tags para marcar diferentes partes do conteúdo (exemplo: títulos, parágrafos, listas).

Objetivo: Organizar o conteúdo de forma que o navegador entenda como exibir na tela do usuário.

3. Estruturar um Documento HTML com Tags e Elementos 🏗️

O HTML usa tags para estruturar e identificar diferentes partes do conteúdo. Cada tag possui uma função específica. As tags de abertura e fechamento delimitam o conteúdo, como:

<html></html>   <!-- Elemento raiz de uma página HTML -->
<head></head>   <!-- Metadados, como título e links para estilos -->
<body></body>   <!-- Conteúdo visível na página -->

4. A Utilidade da Introdução <!DOCTYPE html> ⚙️

A declaração <!DOCTYPE html> informa ao navegador que o documento é um arquivo HTML5. Isso é fundamental para garantir que a página seja interpretada corretamente de acordo com a versão mais recente do HTML.

Mesmo que o arquivo tenha a extensão .html, essa declaração é essencial para definir o contexto do documento.

5. Diferença entre a Metainformação no <head> e o Conteúdo no <body> 💡

<head>: Contém metadados e informações sobre o documento (como o título da página e links para estilos ou scripts). Esses dados não são visíveis diretamente na página, mas são essenciais para seu funcionamento.

<body>: Contém o conteúdo visível da página, como textos, imagens, links e elementos interativos que o usuário verá no navegador.

6. Criar Textos Alternativos (alt) para uma Imagem 🖼️

No HTML, é importante usar o atributo alt para fornecer uma descrição textual de uma imagem. Isso não só ajuda na acessibilidade (para leitores de tela, por exemplo), mas também melhora o SEO da página.

<img src="img/claudeny.png" alt="Descrição da imagem">

7. Acessar a Developer Tools (Ferramentas para Desenvolvedores) de um Navegador 🔍

As Ferramentas para Desenvolvedores são essenciais para:

Inspecionar o HTML, CSS e JavaScript

Editar estilos em tempo real

Monitorar erros no console

Como abrir:

F12 ou Ctrl + Shift + I (Chrome, Firefox e outros navegadores)

8. Quirks Mode (Modo Peculiaridade) 🤖

O Quirks Mode ocorre quando o navegador interpreta um documento HTML de maneira não-padrão, afetando o layout e o comportamento da página.

Esse modo geralmente acontece em páginas que não começam com a declaração <!DOCTYPE html>. Para evitar problemas de compatibilidade, sempre inicie o documento com:

<!DOCTYPE html>

9. Utilizar Extensões no Visual Studio Code (Exemplo: Live Server) 🔌

O Visual Studio Code (VS Code) é uma poderosa IDE. Com a extensão Live Server, você pode visualizar alterações em tempo real no navegador.

💡 Como instalar o Live Server:

Abra o Visual Studio Code.

Vá para a barra lateral de extensões (ícone de quadrado com 4 blocos).

Pesquise por Live Server.

Clique em Instalar.

Clique com o botão direito no arquivo HTML e selecione "Open with Live Server".

✅ Benefícios:

Atualização automática da página no navegador

Visualização em tempo real de mudanças no HTML e CSS

Acelera o desenvolvimento e testes

🧪 Exemplo de Estrutura Completa de um Documento HTML5
<!-- Informa ao navegador que o documento está usando HTML5 -->
<!DOCTYPE html>
<!-- Elemento raiz do documento HTML -->
<html lang="pt-br">

<!-- Seção que contém metadados, título da página e links para arquivos externos (CSS, fontes etc.) -->
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <!-- Define o título da aba do navegador -->
    <title>Portfólio</title>
</head>

<!-- Corpo da página — tudo que aparece visualmente para o usuário -->
<body>
    <!-- Título de nível 1 (o mais importante) -->
    <h1>Isso é um título</h1>

    <!-- Parágrafo de texto comum -->
    <p>Isso é um parágrafo</p>

    <!-- Imagem com descrição alternativa (importante para acessibilidade e SEO) -->
    <img src="html.png" alt="Logo do HTML 5">

    <!-- Fim do conteúdo visível -->
</body>

</html>


📌 Observações:

Esse exemplo mostra a estrutura mínima e funcional de um documento HTML5.

Comentários no HTML são feitos com <!-- comentário aqui --> e não são exibidos no navegador.

O atributo alt na imagem é essencial para acessibilidade e também ajuda com o SEO da página.