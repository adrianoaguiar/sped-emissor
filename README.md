# sped-emissor
Abixo estão as propostas para a criação do emissor,seja para NFe, CTe ou MDFe.

Estas propostas foram discutidas por hangout no dia 29/04/2016, mas ainda são apenas propostas.


## FrontEnd (Interface)

- Html5
- AngularJS
- Boostrap
- jQuery (se necessário)
- outros (Rest, Oauth2, ...)

Deve ser formada uma equipe que irá lidar especificamente com o FRONTEND e outra que irá lidar com o backend.

**A interface deve representar o emissor da SEFAZ SP o tanto quanto possivel.**

## BackEnd

Restful (Lumen - microframework Laravel)

Receber e responder aos dados brutos da interface.
Essa API restful, conectar o NFePHP diretamente.

### Persistência dos dados

Os dados brutos da interface deverão ser persistidos em base de dados da escolha desenvolvedor e em caso de instalação "LOCAL" deverá ser usado o SqLite.

### Autenticação RestFul

- [OAuth2](http://esbenp.github.io/2015/05/26/lumen-web-api-oauth-2-authentication/)
- [JWT](https://laravelista.com/json-web-token-authentication-for-lumen)

A forma de autenticação junto ao serviço pode ser feita pelos modelos acima, mas ainda não temos uma decisão sobre o assunto.

## Parametros para Desenvolvimento:

Todo o desenvolvimento deverá ser estruturado atraves dos Milestones e Issues do GitHub, e todos os interessados podem e devem contribuir, seja nas ideias, código, documentação, testes, avaliação, etc.

Serão estabelecidos alguns critérios de testes e de qualidade de código para servir de orientação aos desenvolvedores.


## Instalação e Distribuição do Pacote

Em principio o PHP deve rodar em Servidor, porém nada impede que essa aplicação seja encasulada e distribuida para rodar localmente.

Uma terceira equipe deve cuidar especificamente dessa forma de distribuição e instalação visto que requer outros tipos de conhecimento para permitir essa funcionalidade.


