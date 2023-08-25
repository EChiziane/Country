# Nome do Projeto: Country information System(CIS)

# Descrição do projecto:

O Que é:  O projeto envolve o desenvolvimento de um aplicativo web usando Angular e a implementação do padrão de gerenciamento de estado Redux. O sistema se conectará a uma API externa para buscar e compartilhar dados de maneira eficiente. Através da estrutura do Angular e do fluxo unidirecional do Redux, o aplicativo garantirá um controle consistente e previsível do estado da aplicação. Ao consumir a API externa, o sistema atualizará automaticamente as informações exibidas na interface, garantindo dados sempre atualizados. A combinação dessas tecnologias oferecerá uma experiência de usuário fluida e interativa, com atualizações instantâneas baseadas em dados em tempo real.
O que Faz: Esse projeto desenvolve um aplicativo web utilizando a framework Angular e implementa o padrão de gerenciamento de estado Redux. O objetivo principal do aplicativo é consumir dados de uma API externa e exibi-los de forma eficiente na interface do usuário. O uso do padrão Redux garante um controle estruturado e previsível do estado da aplicação, enquanto a integração com a API externa permite que o aplicativo atualize automaticamente as informações conforme os dados na API são atualizados. Em resumo, o aplicativo permite aos usuários acessar e interagir com dados em tempo real provenientes da API externa, proporcionando uma experiência dinâmica e responsiva..

Como Fiz: Para alcançar as funcionalidades mencionadas na descrição, a aplicação utilizará uma combinação de tecnologias e abordagens de desenvolvimento. Vamos destacar algumas etapas que podem ser adotadas para implementar as características do sistema:
1. Banco de Dados: A aplicação utilizará um banco de dados SQL para armazenar todas as informações relevantes sobre o fornecimento de cada entrega. Serão criadas tabelas para armazenar dados sobre indivíduos, fornecedores, destinos e informações específicas de cada entrega, como a quantidade de material transportado, a data e outras informações pertinentes.
2. Backend: O desenvolvimento do backend será feito utilizando ASP.NET C#. Ele será responsável por processar as requisições do usuário, acessar o banco de dados para ler e gravar informações e realizar a lógica de negócio do sistema. O backend também poderá conter a lógica para criar gráficos informativos e gerar relatórios.
3. Frontend: A interface do usuário será criada usando HTML, CSS e TypeScript para fornecer uma experiência interativa e responsiva. O frontend permitirá aos usuários visualizar e inserir informações sobre as entregas de materiais, bem como a geração e visualização dos gráficos e relatórios.
4. Gráficos Informativos: A aplicação utilizará bibliotecas de gráficos, como Chart.js ou D3.js, para criar gráficos interativos e informativos. Os dados obtidos do banco de dados serão usados para gerar visualizações gráficas que mostram informações como a quantidade total de material entregue por mês, a distribuição dos fornecedores e outros dados relevantes.
5.Relatórios: A geração de relatórios será feita no backend, utilizando bibliotecas ou frameworks que suportem a criação de documentos em PDF, como o iTextSharp. Os relatórios podem conter informações consolidadas sobre as entregas, fornecedores mais frequentes, desempenho por período e outros dados importantes para a tomada de decisões.
6. Autenticação e Autorização: Para garantir a segurança dos dados e restringir o acesso somente a usuários autorizados, a aplicação implementará um sistema de autenticação e autorização. Isso pode ser realizado usando ASP.NET Identity, que permite gerenciar contas de usuários e permissões.

O que usei:
Para desenvolver esse aplicativo usei as seguintes ferramentas 
Linguagem:C#, typescript
Framework: Asp.Net Core 6, Angular;
Versionamento: Git & GitHub;
DataBase: PostGresql;
Como Usar 
Baixe e instale .net SDK 6;
Baixe e instale VsCode, Visual Studio ou qualquer outra IDE;

# Frontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you
change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also
use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a
package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out
the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
