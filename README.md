# Análise Request
  O objetivo deste pequeno projeto é ter algo que faça uma análise do retorno de uma 'request' de um ou mais sites
definido previamente pelo usuário usuário.
  A linguagem utilizada foi o Shell Script, utilizando como ferramenta de request o cURL.

### Requests
  A principal função do script é fazer um request para cada site registrado no arquivo e retornar o valor da
solicitação. Por exemplo: caso não seja encontrado a página registrada será retornado "404".
<img src='https://i.imgur.com/QPcPY9f.png' height='400'> 

### Criando lista de sites
  Uma das funções do script é registrar sites em um arquivo localizado em "$HOME/.request_list.txt". Para isso é
informar o nome do site e sua respectiva URL.

<img src='https://i.imgur.com/w2Cla3G.png' height='400'> 

### Checando sites registrados
  É possível imprimir os sites registrados em ".request_list.txt" no terminal de maneira organizada.
<img src='https://i.imgur.com/gyvq0Xr.png' height='400'> 
  
### Deletando site registrado
  É possível deletar um dos sites registrados no arquivo ".request_list.txt".
<img src='https://i.imgur.com/XfsmQLf.png' height='500'> 
