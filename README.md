# Docker Wordpress Stack
Repositório com as configurações necessárias para rodar em Docker
- <b>Requisitos</b><br>
<i>Apache</i><br>

- <b>O que foi  utilizado?</b><br>
<i>Apache</i><br>
<i>Mysql</i><br>
<i>PhpMyAdmin</i><br>

- Como utilizar?<br>

<i>Necessário preencher ou alterar as informações do banco no arquivo <b>environment</b> ou alterar as configurações ou portas     dentro do <b>docker-composer.yml</b></i><i>
  O Docker inicia um banco vazio caso não seja adicionado nenhum <b>dump.sql</b> na pasta <b>mysql-dump</b>, caso possua um       banco ele recupera o Dump na primeira vez, cria um volume para salvar os dados dali em diante passa a salvar os no volume!</i>

