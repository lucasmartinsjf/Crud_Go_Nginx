# CRUD feito em Go seguindo o padrão template, o mesmo encontra-se em ambiente de conteiner
## Containers:
  - APP (Go) porta 9000 (não exposta)
  - PhpMyAdmin porta 8088 (exposta)
  - Mysql porta 3306 (não exposta)
  - Nginx porta 80 (exposta)
  

 ## Dependencias: 
  - Go (Caso necessite realizar teste fora do Docker)
  - Docker 
  - Docker Compose
  - Caso utilize algum ambiente com firewall, favor liberar as portas 80, 8088 para acesso ao app e phmyadmin respectivamente.

## Instalação: 
  - Executar Arquivo deploy.sh, cuja o mesmo irá realizar a instalação das dependencias, 
 

  - Abrir o navegador na porta 8088, Acessar o phpmyadmin com as credenciais configuradas no arquivo ".env", e executar o arquivo db.sql.

  - Ao final acessar o navegador no endereço:  http://"SEU_IP".

## Esboço do Projeto: 
  - https://drive.google.com/file/d/1zR9odygZPJ6acLRmr4xsCJY8U8JEomk8/view?usp=sharing
 
