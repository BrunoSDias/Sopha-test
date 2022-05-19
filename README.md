# Avaliação Sopha

## Desafio

Criar CRUD de cadastro de cliente e área logada em ReactJS, utilizando aplicação Ruby on Rails como API.<br>
O processo de autenticação pode ser feita manualmente ou utilizando alguma gem pública.<br>
Não é necessário hospedar a aplicação.

<b> Conhecimentos necessários</b>
- Ruby
- Ruby on Rails
- JS
-  ReactJS
-  SQL

<b> Conhecimentos adicionais</b>
- Material UI
- AWS (S3, EC2, RDS, EB)

<b>Solução</b>
- Criar repositório com sua solução no Github
- A solução deve estar pronta para rodar
- Instruções do build do código e de uso devem estar claras (database migrations etc)
- Todas as instruções devem estar no arquivo README

<b> Requisitos da solução </b>
- Ruby versão 2.7 ou maior
- Ruby on Rails versão 5.1.7 ou maior
- ReactJS versão 16 ou maior

## Itens mandatórios
- Pagina para cadastro do cliente (new)
- Pagina para edição dos dados do cliente (edit)
- Página de listagem dos clientes (index)
- Página de login
- Área logada (Pode ser apenas uma página em branco, com, por exemplo, a mensagem "Bem vindo {nome_do_cliente}" para sabermos se o login foi um sucesso)
- Botão de remoção do cliente na index
- Testes Unitários da aplicação Rails utilizando mini test (https://guides.rubyonrails.org/testing.html#rails-meets-minitest)

## Opcionais (que podem auxiliar na avaliação)
- Utilizar MUI (https://mui.com/pt/) para a aplicação ReactJS
- Construção da aplicação ReactJS utilizando componentes funcionais


## Exemplo de README

> # API CRUD de cadastro de cliente 
> 
> ## Dependencias do Sistema
> * Ruby versão 2.3.7.
> * Rails versão 5.1.7.
> ## Instruções de Build
> ### Comandos
> ` bundle install` - Instalá as gems utilizadas no projeto;<br>
> ` rails db:create` - Para gerar a base de dados dentro do projeto;<br>
> ` rails db:migrate` - Para migrar as tabelas do projeto para dentro do banco de dados;<br>
> ` rails db:seed ` - Para carregar os dados em base;
