# Projeto_previsao_tempo

<div align="center">
  <img align="left" height="250" src="https://github.com/saniodev/SanioDev/assets/93998809/012c92a5-7758-4d9c-b1af-c7bbfff6faf7"/>
</div>




 ## Instruções Gerais

O projeto é dividido em duas partes: back-end e front-end, cada uma com seu próprio repositório no GitHub.

 [Previsao do tempo Back-end](https://github.com/saniodev/previsao_tempo_api)

 [Previsao do tempo Front-end](https://github.com/saniodev/previsao_tempo)

## 🚀 Começando

Siga as etapas abaixo para configurar e executar o projeto em seu ambiente local.

### 📋 Pré-requisitos

- Node.js: [Instalação do Node.js](https://nodejs.org/)
- MySQL: [Instalação do MySQL](https://dev.mysql.com/doc/mysql-installation-excerpt/en/)

| Tecnologia | Descrição |
| --- | --- |
| Node.js | Ambiente de execução do servidor |
| MySQL | Sistema de gerenciamento de banco de dados |
| React | Biblioteca JavaScript para construção da interface do usuário |

### 🔧 Instalação

## Back-End (Node.js)

O back-end é um servidor Node.js que fornece uma API RESTful (CRUD).
### tabela mysql  
![image](https://github.com/saniodev/Projeto_previsao_tempo/assets/93998809/d4f58370-b2f6-46e5-a7ef-dbeb78b29b03)

### Endpoints
#### [Swagger UI da API](http://localhost:3000/swagger)

| Método | Rota                        | Descrição                              |
|--------|-----------------------------|----------------------------------------|
| POST   | /login/user                 | Autenticação de Usuário                |
| POST   | /user/create                | Criar Usuário                          |
| GET    | /user/list                  | Lista de Usuários                      |
| PUT    | /user/update/{id}           | Atualizar Usuário                     |
| DELETE | /user/delete/{id}           | Deletar Usuário                       |
| POST   | /clima/weather/{id}         | Obter previsão do tempo por ID         |
| POST   | /clima/current/{id}         | Obter condições climáticas atuais por ID |
| POST   | /clima/city/{id}            | Obter previsão do tempo por cidade e ID |


## Front-End (React)

O front-end é um aplicativo React que permite ao usuário:

- *Previsão do Tempo Local:*
  - Visualize as condições climáticas da sua região atual ao acessar o site.

- *Previsão para os Próximos 5 Dias:*
  - Obtenha informações detalhadas sobre o clima para os próximos 5 dias, permitindo que você se planeje com antecedência.

- *Consulta a Outras Cidades:*
  - Explore a previsão do tempo de outras cidades inserindo o nome da cidade desejada.

## Como Usar

1. *Acesso ao Clima Local:*
   - Ao acessar o site, a previsão do tempo local será exibida automaticamente na página inicial.

2. *Consulta a Outras Cidades:*
   - Utilize a barra de pesquisa para inserir o nome da cidade desejada para obter informações específicas sobre o clima dessa região.

## Tecnologias Utilizadas

- *Frontend:*
  - Desenvolvido com React e Next.js para uma experiência de usuário rápida e responsiva.

- *Estilo:*
  - Utilização do Tailwind CSS para estilização moderna e eficiente.
O aplicativo React se conecta ao back-end por meio de requisições HTTP.

## Executando o Projeto

1. Inicie o servidor MySQL.
2. Navegue até o diretório do back-end e execute yarn dev para iniciar o servidor Node.js.
3. Em outro terminal, navegue até o diretório do front-end e execute yarn dev para iniciar o aplicativo React.

## Contribuindo

Pull requests são bem-vindos. Para mudanças importantes, abra um problema primeiro para discutir o que você gostaria de mudar.

## Licença

MIT
