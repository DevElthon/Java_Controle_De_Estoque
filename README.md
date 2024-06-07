# Aplicação Desktop para controle de estoque

A aplicação foi desenvolvida utilizando Java e Swing JFrame. O objetivo da mesma é servir como 
um software de gestão de produtos e processador de pedidos.

# Requisitos para rodar aplicação:
- JDK 22
- Mysql Server

#Setup da aplicação:

No MySQL server Cliente, execute a linha: CREATE DATABASE inventory;

Para rodar a primeira vez, é necessário instalar as bibliotecas disponibilizadas no diretório
JavaUsedLibraries. Após isso, execute o script ConnectionProvider.java modificando a senha do
DriverManager JDBC para a senha do seu MySQL server. Por fim, descomente as linhas no script 
tables.java e modifique os parâmetros do seu appuser da maneira que achar melhor (para configurar
seu administrador).

Para executar o programa, basta executar o Run File em login.
Obs: caso exista algum conflito por conta de Path de imagens, abra o Navigator do login e passe 
por todos os elementos.
