# HTML

* <h2>Oque é semântica HTML?<h2>

A Semântica HTML é o uso correto das tags HTML para indicar o significado do conteúdo de uma página web. Isso significa que cada tag deve ser usada de forma apropriada para descrever o que o conteúdo representa.

Por exemplo, para escrevermos um título, devemos utilizar a tag ``<h1>``, enquanto um parágrafo deve ser envolvido pela tag ``<p>``. Quando usamos as tags corretas para cada tipo de conteúdo, a página se torna mais acessível e legível para os usuários e mecanismos de busca.


* <h2>O que são tags?</h2>

O HTLM é uma linguagem de hipertexto e marcação, e esta é sua principal característica, o que a torna tão poderosa para desenvolvimento de sites. As marcações são inseridas nos textos, porem para os olhos dos leitores elas são invisíveis, pois sua principal finalidade é de passar instruções ao navegador para que o mesmo possa renderizar uma pagina.

Todas as marcações são realizadas pelas tags que em geral são estruturas de linguagem de marcação que contém instruções. Os navegadores interpretam essas instruções e a partir disso renderizam uma pagina. A forma mais comum de utilização das tags, são como delimitadores de estilo ou de conteúdo, ou seja ela agrupa os conteúdos de acordo com o tipo, forma e formatações e com isso outras linguagem como por exemplo CSS podem aplicar estilizações a este conteúdo.

As tags também são responsáveis por criar elementos nas paginas web com a função de organizar, identificar e limitar o conteúdo de uma pagina. Cabe então ao Browser reconhecer esses elementos, e renderizá-las apresentando seu conteúdo aos usuários.

Os elementos normalmente são criados com uma tag de abertura e uma de fechamento feitas com um nome entre colchetes angulares “<>” conforme o exemplo:

![exemplo tag](https://www.homehost.com.br/blog/wp-content/uploads/2019/07/tag_html.png)

* <h2>O que são classes (HTML)</h2>

O atributo global class especifica uma ou mais classes para o elemento HTML. Esse atributo pode ser reutilizado, ajudando a pessoa desenvolvedora a não repetir códigos, além de permitir o uso de diferentes classes simultaneamente.
Para melhor organização do projeto, também possuímos padrões para nomear essas classes como o Block Element Modifier. É possível acessar elementos específicos pela sua classe no Javascript através de funções como o document.getElementsByClassName() ou através do seletor de classe CSS, representado pelo símbolo ponto (.).

![image](https://github.com/Anton1oo/aula-frontEnd/assets/136518102/d3f7a4d2-0eaa-486b-905a-3d1955454e64)


* <h2>O que é id (HTML)?</h2>

O atributo Id especifica uma identificação única para o elemento HTML. Por questões de boas práticas, não deve ser reutilizado e nem conter espaços em seu nome, pois o navegador irá identificar o espaço como parte dele, já que os elementos não podem ter mais de um Id.
É geralmente utilizado para referenciar os elementos em scripts Javascript, através da função nativa document.getElementById(). Caso usado no CSS e referenciado através do símbolo de cerquilha (#).

![exemplo id](https://sariasan.com/wp-content/uploads/2019/12/word-image-1.jpeg)

* <h2>O que é section (HTML)?</h2>

O elemento HTML ``<section>`` representa uma seção genérica contida em um documento HTML, geralmente com um título, quando não existir um elemento semântico mais específico para representá-lo.

Por exemplo, um menu de navegação deve estar dentro um elemento ``<nav>``, mas uma lista de resultados de pesquisa ou a exibição de um mapa e seus controles não possuem elementos específicos, e podem ser colocados dentro de uma ``<section>``.
Pode usar imagens e links para fonte de estudo e referências.

Vc pode usar uma section para definir áreas ou regiões para:

* Textos introdutórios
* Listagens
* Mapas
* Comentários
* Informações de contato
* Etc...

[leia sobre](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/section)
