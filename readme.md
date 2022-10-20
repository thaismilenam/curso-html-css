# Curso HTML5 e CSS3: Alura

## Módulo 1: crie uma página web

### 01 - Marcação do primeiro texto
    Introdução ao HTML e às suas tags
    Título e os parágrafos de um texto com tags <h1> e <p>
    Informações do texto:
    - negrito usando <strong>
    - itálico pela tag <em>
### 02 - Separando o conteúdo e informações
    Estrutura básica do HTML
    DOCTYPE: define a versão do HTML utilizado
    <html>, marca o conteúdo a ser renderizado no navegador
    lang define a linguagem da página
    <meta> e da propriedade charset -encoding da nossa página para o navegador,
    <title>: define o título da página
    <head>: separa informações para o navegador
    <body>: separa conteúdo da página
### 03 - Trabalhando com CSS
    (text-align): elemento para alinhar o texto
    (font-size): elemento para tamanho da fonte
    (background): elemento para definir cor do fundo
    (color): elemento para definir cor de textos
    CSS inline: dentro da teg <style> podemos colocar marcações de CSS de elementos 
    Adicionar CSS como um arquivo externo
    Funcionamento do estilo em cascata do CSS
    Importar um arquivo externo de CSS dentro da página HTML
    Como representar cores no CSS pelo nome da cor, hexadecimal ou RGB
### 04 - Estilizando imagens
    Reestruturação do código, CSS inline para CSS em arquivo externo
    Identificador para marcar eum elemento e referenciar no CSS
    Adicionar uma imagem à nossa página e ajutar altura com height e largura com width
    Ajustar espaçamento interno do elemento com padding eespaçamento externo com margin
    Comportamento de um time de front-end
### 05 - Listas e divisões de conteúdo
    Listas não-ordenadas e listas ordenadas
    <li> é a tag para itens da lista
    Classes no CSS servem para marcar itens que são repetíveis
    Como referenciar uma classe no CSS
    Divisões de conteúdo, utilizando a tag <div>
    Cmportamentos de utilização do espaço
    - inline (permite utilizar espaçamento na mesma linha)
    - block (bloqueia espaços na mesma linha)
### 06 - Finalizando a página
    Cabeçalho da página utilizando <header>, que deve ter mais destaque
    Não é recomendado criar estilos usando tags
    Ideal é a utilização de classes.

## Módulo 2: posicionamento, listas e navegação

### 01 - Criando uma nova página
    Revisão da base de uma página HTML
    Lista HTML não ordenada
### 02 - Navegação entre as páginas
    Criar links para outras páginas, do projeto ou páginas externas
    Reforço aos estilos inline e block
    Transformar o texto para todas as letras maiúsculas: uppercase
    Texto em negrito com CSS usando bold
    Como remover a decoração do texto
### 03 - Posicionamento dos elementos
    Remover os estilos que o navegador cria, com reset.css
    Posicionamentos static, relative e absolute dos elementos
    Como posicionar o cabeçalho da página
### 04 - A tag section
    A tag main, para o conteúdo principal da nossa página
    A criar listas complexas, com títulos, imagens e parágrafos
    A utilizar o inline-block
    A praticar e estilizar o conteúdo principal da nossa página
### 05 - Lidando com bordas
    Através do CSS, aplicar bordas nos elementos.
    Os diferentes tipos de bordas.
    A deixar a borda arredondada.
### 06 - Pseudo-classes de estado
    Pseudo-classes CSS
    hover, quando o usuário passa o cursor sobre o elemento
    active, quando um elemento está sendo ativado pelo usuário
    Mudar a cor do texto e/ou da borda de um elemento, ao cursor passar sobre ele
    Mudar a cor da borda de um elemento, ao ser ativado pelo usuário
### 07 - Finalizando a página de produtos
    A tag footer, para o rodapé da nossa página
    Imagem de fundo em um elemento
    Uso da tabela Unicode.

## Módulo 3: trabalhando com formulários e tabelas

### 01 - Criando uma nova página
    Criação da página de contato
    Introdução a formulários
### 02 - Começando um formulário
    Para um formulário HTML se utiliza a tag <form>
    <input> para a entrada de dados do usuário
    Tag <label> para criar etiqueta de input
    Id para o input e associamos esse id ao atributo for do label
    Label possui o display inline e o input possui display inline-block
### 03 - Tipos de campos diferentes
    O textarea, para entradas de texto de mais de uma linha
    O input do tipo radio
    Como agrupar vários input do tipo radio, impedindo que mais de um input seja selecionado
    O input do tipo checkbox
    Que podemos criar um input dentro de um label, assim associando-os
    Mais estilizações para a nossa página
    Como funciona a hierarquia no CSS
    O select, que é seletor, um campo de seleção de um item, e o option, que representa cada opção do seletor
### 04 - Melhorando a semântica
    Tipos de inputs: email, tel, number, password, date, datetime, month e search
    Não permitir que um campo não seja preenchido, pelo atributo required
    Exibir uma sugestão de preenchimento para os campos, através do atributo placeholder
    Deixar uma opção marcada por padrão nos nossos input radio e checkbox, através do atributo checked
    Estruturar melhor o nosso código com fieldset e legend
    Adicionar uma alternativa à imagem, descrevendo-a, com o atributo alt
### 05 - CSS avançado
    Estilizar o botão de envio de formulário
    Realizar transições nos nossos elementos, com a propriedade CSS transition
    Modificar o estilo do ponteiro do mouse, quando passar por cima de determinado elemento pelo cursor
    Transições de aumentar proporcionalmente a escala do elemento ou rotacioná-lo, através do transform
### 06 - Estrutura de tabelas
    Tag table, que representa a tabela
    Tag tr, linha da tabela
    Tag td,  célula da tabela
    Tag thead, o cabeçalho da tabela
    Tag tbody, o corpo da tabela
    Tag th, célula do cabeçalho da tabela
    Tag tfoot, o rodapé da tabela

## Módulo 4: avançando no CSS

### 01 - Adaptando a página inicial Ver primeiro vídeo
    Medidas proporcionais com CSS
    Flutuação dos elementos, com a propriedade float do CSS
    Propriedade clear do CSS
### 02 - Conteúdo externo
    Utilização de fontes externas nas nossas páginas
    Incorporação de um mapa à página
    Incorporação de um vídeo à página
### 03 - Melhorando o CSS
    Melhorar a semântica da página principal, com divisões, classes, ,pseudo-classes
    Background gradiente na página
    Pseudo-elementos
### 04 - Selecionando qualquer coisa
    Seletor >, para acessar os filhos de determinado elemento
    Seletor +, para acessar o primeiro irmão de determinado elemento
    Seletor ~, para acessar todos os irmãos de determinado elemento
    Seletor not, para acessar os elementos, exceto algum
    Propriedade calc
### 05 - Opacidade e sombra
    Opacidade dos elementos, com a propriedade CSS opacity
    Opacidade das cores
    Sombreamento em volta dos elementos, com a propriedade CSS box-shadow
    Sombreamento em textos, com a propriedade CSS text-shadow
### 06 -Design responsivo
    Design responsivo: ajustar a página de acordo com o tamanho da tela do dispositivo
    Meta tag de Viewport
    Media Queries
