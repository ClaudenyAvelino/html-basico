# Aula de HTML: Estrutura e Ferramentas 🔧🌐

## O que foi abordado nesta aula? 📝

### 1. A Importância da Documentação W3S 📚
A **W3Schools** (W3S) é uma excelente fonte de aprendizado para quem está iniciando com **HTML** e outras tecnologias web. A documentação oferece explicações detalhadas sobre as tags, atributos e boas práticas do HTML. Consultar a documentação é um passo fundamental para **entender** as funcionalidades da linguagem e aprender como usá-las corretamente.

- **Link para a W3Schools**: [https://www.w3schools.com/](https://www.w3schools.com/)

### 2. O que é HTML e Por que é Considerada uma Linguagem de Marcação? 🤔
**HTML** (HyperText Markup Language) é uma **linguagem de marcação** usada para estruturar conteúdo na web. Diferente das linguagens de programação, HTML não executa ações ou processos lógicos, mas define a **estrutura** de uma página da web, como textos, imagens, links, e muito mais.

- **Marcação**: A linguagem usa **tags** para marcar diferentes partes do conteúdo (exemplo: títulos, parágrafos, listas).
- **Objetivo**: Organizar o conteúdo de forma que o navegador entenda como exibir na tela do usuário.

### 3. Estruturar um Documento HTML com Tags e Elementos 🏗️
O HTML usa **tags** para estruturar e identificar diferentes partes do conteúdo. Cada tag possui uma função específica. As tags de abertura e fechamento delimitam o conteúdo, como:

- **`<html></html>`**: Elemento raiz de uma página HTML.
- **`<head></head>`**: Contém metadados, como o título e links para estilos.
- **`<body></body>`**: Contém o conteúdo visível na página, como textos, imagens, etc.

### 4. A Utilidade da Introdução `<!DOCTYPE html>` ⚙️
A declaração `<!DOCTYPE html>` informa ao navegador que o documento é um arquivo HTML5. Isso é fundamental para garantir que a página seja interpretada corretamente de acordo com a versão mais recente do HTML. Mesmo que o arquivo tenha a extensão `.html`, essa tag é essencial para definir o contexto.

### 5. Diferença entre a Metainformação no `<head>` e o Conteúdo no `<body>` 💡
- **`<head>`**: Contém **metadados** e informações sobre o documento (como o título da página e links para estilos ou scripts), que não são visíveis diretamente na página, mas são essenciais para o seu funcionamento.
- **`<body>`**: Contém o **conteúdo visível** da página, como textos, imagens, links, e outros elementos interativos que o usuário verá no navegador.

### 6. Criar Textos Alternativos (alts) para uma Imagem 🖼️
No HTML, é importante usar o atributo `alt` para fornecer uma **descrição textual** de uma imagem. Isso não só ajuda na **acessibilidade** para pessoas com deficiências visuais, mas também melhora o SEO da página.

Exemplo:
```html
<img src="imagem.jpg" alt="Descrição da imagem">

### 7. Acessar a Developer Tools (Ferramentas para Desenvolvedores) de um Navegador 🔍
As **Ferramentas para Desenvolvedores** são essenciais para inspecionar, depurar e entender o funcionamento do código HTML, CSS e JavaScript em tempo real no navegador.

- Para acessar as **Developer Tools** no navegador, basta pressionar `F12` ou `Ctrl + Shift + I` em navegadores como **Chrome** e **Firefox**.
- As ferramentas ajudam a **inspecionar o HTML da página**, **editar o CSS** diretamente no navegador e **monitorar erros** no console do JavaScript.

### 8. Quirks Mode (Modo Peculiaridade) 🤖
O **Quirks Mode** ocorre quando o navegador interpreta um documento HTML de maneira **não-padrão**, afetando o layout e o comportamento da página. Esse modo geralmente ocorre em documentos mais antigos ou em páginas que não começam com a declaração `<!DOCTYPE html>`. Para garantir que o seu código HTML seja interpretado corretamente, sempre comece o seu arquivo com a declaração `<!DOCTYPE html>`.

### 9. Utilizar Extensões no Visual Studio Code (Exemplo: Live Server) 🔌
O **Visual Studio Code (VS Code)** é uma poderosa ferramenta de desenvolvimento. Com a instalação da extensão **Live Server**, você pode visualizar as alterações feitas em tempo real diretamente no seu navegador, sem a necessidade de atualizar a página manualmente.

- **Como instalar o Live Server**:
  1. Abra o **Visual Studio Code**.
  2. Acesse a **barra lateral de extensões** (ícone quadrado com 4 pequenos quadrados).
  3. Pesquise por **Live Server** e clique em **Instalar**.
  4. Após a instalação, clique com o botão direito no arquivo HTML e selecione **Open with Live Server**.

- **Benefícios do Live Server**:
  - Atualização automática da página no navegador sempre que o código for alterado.
  - Permite ver em tempo real as modificações feitas no HTML e no layout da página.
