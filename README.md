<h1 align="center"> Bem-vindo ao projeto individual modulo3 👋 </h1>
&nbsp;
<h2 align="justify">Este projeto visa criar um Servidor json com duas rotas e 3 
dados que o usuário poderá realizar os métodos GET, POST, PUT e DELETE(CRUD).</h2>
&nbsp;

### 🏠 [Homepage](https://fernandoap46.github.io/PIM3)

### ✨ [Demo](https://fernandoap46.github.io/PIM3)

## Como criar o servidor json
&nbsp;
<p align="justify">-O primeiro passo e criar dentro da pasta do se projeto o arquivo com 
a extensão ".json", para este projeto usaremos o arquivo db.json.</p>
&nbsp;
<p align="justify">Para criar cada rota é necessário que os três dados estejam
num array, com o nome da rota envolvido em colchetes como abaixo:</p>
&nbsp;

![image2](https://imgbox.com/X8LOWJVo)

&nbsp;
<p align="justify">-O segundo passo e abrir o terminal, e caso não esteja dentro da página
do seu projeto é necessário navegar até ela, e executar o comando " npx json-server --watch db.json"
(db.json se refere ao nome do nosso servidor)</p>
&nbsp; 
<p align="justify">Se tudo estiver correto, o terminal informara o link do seu servidor, e das suas 
rotas criadas, caso tudo esteja certo aperte Crt+ o seletor esquerdo do mouse e a pagina de confirmação
devera abrir desta forma em seu navegador:</p>
&nbsp;

![image](https://imgbox.com/dvTnP6O1)<br>
<p align="justify">Agora tudo está pronto, já podemos testar nossas requisições Post, Get, Put & Delete,
(CRUD) utilizando JSON Server.</p>
&nbsp;

## Como utilizar o CRUD NO db.json

<p align="justify">Para este projeto foi utilizado os postman para fazer os testes de CRUD.</p>
&nbsp;
<p align="justify">GET- puxar informações do db.json</p>
<p align="justify">No Postman selecione GET e a rota desejada, no exemplo abaixo estamos acessando a rota loja, e ele deve retornar as informações do objeto loja dentro do nosso db.json.</p>
&nbsp;

![image2](https://imgbox.com/TtE5Nx96)
&nbsp;
<p align="justify">POST- Enviar uma nova informação para o db.json</p>
<p align="justify">Selecione POST e a rota desejada, selecione em Body, modifique o tipo de arquivo para JSON, e informe as novas informações do usuário conforme configuração do seu projeto:</p>
&nbsp;

![image2](https://imgbox.com/Lh20mLoH)
&nbsp;
<p align="justify">PUT- Editar informações db.json</p>
<p align="justify">Selecione PUT e a rota desejada, no final da rota adicione "/" e o número do id que deseja alterar, selecione Body, modifique o tipo de arquivo para JSON, e informe o que deseja ser alterado do id que selecionou:</p>
&nbsp;

![image2](https://imgbox.com/QuUXHvqt)
&nbsp;
<p align="justify">DELET- Deletar informações db.json</p>
<p align="justify">Selecione DELET e a rota desejada, no final da rota adicione "/" e o número do id que deseja deletar, e após 
confirmar a informação será deletada</p>
&nbsp;

![image2](https://imgbox.com/3EivqNjE)



## Author

👤 **Fernando Agostinho Pereira**

* Github: [@fernandoap46](https://github.com/fernandoap46)
* LinkedIn: [@https:\/\/www.linkedin.com\/in\/fernando-agostinho-pereira-b76399189](https://linkedin.com/in/https:\/\/www.linkedin.com\/in\/fernando-agostinho-pereira-b76399189)