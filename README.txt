BAIXAR NODE JS

npm init -y
npm i json-server

trocar SCRIPT por "start": "json-server --watch db.json --port 3001"
entrar no localhos

sudo npm i -g @angular/cli
ng new frontend --minimal

angular.json modificar para - "inlineTemplate": false,
                                "inlineStyle": false,

app.component.ts - deletar o template e o style, adicionar templateUrl: 'app.component.html'
criar arquivo na pasta app com nome app.component.html

ng add @angular/material
ng generate component components/template/header #gerar arquivos HTML,CSS,TS
import { MatToolbarModule } from '@angular/material/toolbar'; app.module.ts
declarar nos IMPORTS

<app-header></app-header> dentro do app.component.html
<app-footer></app-footer> dentro do app.component.html

import { MatSidenavModule } from '@angular/material/sidenav';
import { MatListModule } from '@angular/material/list';

ng g d directives/red #diretiva
ng g s components/product/product #service

npm start