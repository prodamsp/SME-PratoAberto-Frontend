[![Maintainability](https://api.codeclimate.com/v1/badges/7d34f4c49b56a7c38466/maintainability)](https://codeclimate.com/github/prefeiturasp/SME-PratoAberto-Frontend/maintainability)

# Frontend

Website do projeto Prato Aberto que permite à população descobrir o cardápio das escolas públicas de São Paulo. A plataforma pode ser acessada em https://pratoaberto.sme.prefeitura.sp.gov.br/.

# Dependências

 * [angular-cli](https://github.com/angular/angular-cli)
 * Sass (latest)
 * Typescript (latest)

# Organização do projeto

 * instalar dependências via cli com o comando --save-dev
 * manter templates em arquivos separados, da mesma forma que já é proposto pelo @angular-cli na criação de componentes
 * classes devem ser criadas via @angular-cli e escritas em Typescript
 * CSS utiliza Sass
 * a pasta `src/assets` concentra qualquer asset necessário, como imagens, fontes e dados

# Deploy

 1. `ng build -prod`, gera a versão de distribuição na pasta `dist`
 2. `npm install`
 3. `ng-serve`, para rodar uma versão do servidor de desenvolvimento
