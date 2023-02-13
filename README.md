<h1 align="center"> Bem-vindo ao projeto individual modulo3 👋 </h1>
&nbsp;
<h2 align="justify">Este projeto visa criar um Servidor json com duas rotas e 3 
dados que o usuário poderá realizar os métodos GET, POST, PUT e DELETE(CRUD).</h2>
&nbsp;

### 🏠 [Homepage](https://fernandoap46.github.io/PIM3)

### ✨ [Demo](https://fernandoap46.github.io/PIM3)

## Tecnologias utilizadas
&nbsp;
![image1](https://github.com/fernandoap46/assets-img/blob/main/assets/img/json.JPG)
&nbsp;
## Como criar o servidor json
&nbsp;
<h3 align="justify">-O primeiro passo e criar dentro da pasta do se projeto o arquivo com 
a extensão ".json", para este projeto usaremos o arquivo db.json.</h3>
&nbsp;
<h3 align="justify">Para criar cada rota é necessário que os três dados estejam
num array, com o nome da rota envolvido em colchetes como abaixo:</h3>
&nbsp;

![image1](https://github.com/fernandoap46/assets-img/blob/main/assets/img/1.JPG)

&nbsp;
<h3 align="justify">-O segundo passo e abrir o terminal, e caso não esteja dentro da página
do seu projeto é necessário navegar até ela, e executar o comando " npx json-server --watch db.json"
(db.json se refere ao nome do nosso servidor)</h3>
&nbsp; 
<h3 align="justify">Se tudo estiver correto, o terminal informara o link do seu servidor, e das suas 
rotas criadas, caso tudo esteja certo aperte Crt+ o seletor esquerdo do mouse e a pagina de confirmação
devera abrir desta forma em seu navegador:</h3>
&nbsp;

![image2](https://github.com/fernandoap46/assets-img/blob/main/assets/img/2.JPG)<br>
<h3 align="justify">Agora tudo está pronto, já podemos testar nossas requisições Post, Get, Put & Delete,
(CRUD) utilizando JSON Server.</h3>
&nbsp;

## Como utilizar o CRUD NO db.json

<h3 align="justify">Para este projeto foi utilizado os postman para fazer os testes de CRUD.</h3>
&nbsp;
<h3 align="justify">GET- puxar informações do db.json</h3>
<h3 align="justify">No Postman selecione GET e a rota desejada, no exemplo abaixo estamos acessando a rota loja, e ele deve retornar as informações do objeto loja dentro do nosso db.json.</h3>
&nbsp;

![image3](https://github.com/fernandoap46/assets-img/blob/main/assets/img/3.JPG)
&nbsp;
<h3 align="justify">POST- Enviar uma nova informação para o db.json</h3>
<h3 align="justify">Selecione POST e a rota desejada, selecione em Body, modifique o tipo de arquivo para JSON, e informe as novas informações do usuário conforme configuração do seu projeto:</h3>
&nbsp;

![image4](https://github.com/fernandoap46/assets-img/blob/main/assets/img/5.JPG)
&nbsp;
<h3 align="justify">PUT- Editar informações db.json</h3>
<h3 align="justify">Selecione PUT e a rota desejada, no final da rota adicione "/" e o número do id que deseja alterar, selecione Body, modifique o tipo de arquivo para JSON, e informe o que deseja ser alterado do id que selecionou:</h3>
&nbsp;

![image5](https://github.com/fernandoap46/assets-img/blob/main/assets/img/6.JPG)
&nbsp;
<h3 align="justify">DELET- Deletar informações db.json</h3>
<h3 align="justify">Selecione DELET e a rota desejada, no final da rota adicione "/" e o número do id que deseja deletar, e após 
confirmar a informação será deletada</h3>
&nbsp;

![image6](https://github.com/fernandoap46/assets-img/blob/main/assets/img/8.JPG)



## Author

👤 **Fernando Agostinho Pereira**

* Github: [@fernandoap46](https://github.com/fernandoap46)
* LinkedIn: [@https:\/\/www.linkedin.com\/in\/fernando-agostinho-pereira-b76399189](https://linkedin.com/in/https:\/\/www.linkedin.com\/in\/fernando-agostinho-pereira-b76399189)
