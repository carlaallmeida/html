<h1 align="left">Site CoffeShop</h1>

<p align="left" display="inline-block">

<img src="https://img.shields.io/badge/HTML5-000000?style=for-the-badge&logo=html5&logoColor=white"  alt="top-language"/>
</p>
<p> O projeto foi criado para a disciplina de Construção do Frontend. Seu objetivo aplicar os conceitos da linguagem.</p>
<br> 
        
 <h1 align="left">Pré-requisito</h1>

-  Não há.

<br>

<h1 align="left">Cores e Fontes usadas</h1>
 
 - Background: #1B1007 e o Branco: #fffff
 - Tipo de fonte usada: inherit
 
<br>

<h1 align="left">Explicando o Código</h1>

 **Criação da Página Home**

 <p>Após criar um novo documento, dentro da tag html
 colocamos um parâmetro "lang=pt-br" indicando que o site está em português. Logo em seguida usei a tag *title* para definir um titúlo para a página do site.</p>
<p>Na tag *meta* , o charset= “utf-8” informa ao navegador que o idioma do site está em português, permitindo que ele aceite palavras com acentos e cedilhas.</p>
<p>Dentro da tag body que é onde definimos todo corpo do site, usei uma tag chamada section para cada parte associada ao menu.</p>
<p>Na primeira section criei a class="menu" e  para definir o estilo dentro do documento estilo.css. </p>
<p>Já no documento estilo.css foi criado uma tag .menu li representa a criação de uma lista não ordenada para crição de um menu horizontal.</p>

**Criação Menu Sobre**

<p>Dentro da tag h2  foi criado um id ="Conheca_a_Nossa_Empresa" vinculado ao menu Sobre. Os id's podem ser usados somente uma vez dentro de uma página html. No documento estilo.css os Id's são representados pelo simbolo sustenido #. </p>

**Criação Menu Produto**

<p>Em produtos criei uma tag section vinculada a uma class="container". Os container's em html são usados para
agrupar elementos. No caso do site usei para colocar uma imagem ao lado do texto.</p>

**Criação Menu Loja Virtual**

<p>Para essa parte criei uma tag section vinculada a uma class ="container-venda". Os container's em html são usados para agrupar elementos.</p>
<p>Dentro dessa section também foi criado a div com o id="comprar" que está vinculado a Loja Virtual. As div's são usadas para agrupar elementos. Nesse caso optei por usar a div para atribuir um estilo diferente para "comprar".</p>
<p>Foi criado também um button que está vinculado a class="btn". Esse botão é demonstrativo. Mas, você poderia inserir um link de uma página personalizada de compras.</p>

**Criação do Menu Fale Conosco**

<p>Para a criação do formulário de contato usei uma tag chamada  tabelas que exibem elementos dispostos em linhas e colunas. Dentro de cada tr usado para as linhas criamos um td vinculado a id's diferentes. Foram criados o idNome, idEmail, idAssunto, idMensagem.</p>
<p>Foi criado um button vinculado a uma validação de envio usando a linguagem JavaScript. Para fazer a validação de envio de mensagem com sucesso foi criado a tag script. Foi criado a função "onclick", ou seja, toda vez que o usuário clicar no botão ele receberá um alerta informando que a mensagem foi enviada com sucesso.</p>

**Rodapé**

<p>Foi criado a tag footer para criação do rodapé.</p>

<br>

<h1 align="left">Ferrrameta de Edição</h1>

- Todo o código foi desenvolvido no Visual Studio Code.

<br>

<h1 align="left">Licença</h1>

- MIT License.
