# my-angular-cli
创建Angular的批处理命令集

AaBb1234567890-=

ng new air-workspace --create-application=false  --routing=true --style=sass --skipInstall=true
cd air-workspace

ng generate application air-application  --routing=true --prefix=air   --force=true
npm install --save @angular/material @angular/cdk @angular/animations


ng generate module @core    --routing=true --module=app
ng generate module @theme   --routing=true --module=app
ng generate module account  --routing=true --module=app
ng generate module pages    --routing=true --module=app

ng generate module @theme\components --routing=true --module=@theme
ng generate module @theme\directives --routing=true --module=@theme
ng generate module @theme\layouts    --routing=true --module=@theme
ng generate module @theme\pipes      --routing=true --module=@theme
ng generate module @theme\styles     --routing=true --module=@theme

ng generate module pages\dashboard   --routing=true --module=pages
ng generate module pages\e-commerce  --routing=true --module=pages
ng generate module pages\forms       --routing=true --module=pages
ng generate module pages\tables      --routing=true --module=pages


ng generate component  @theme\components\air-footer        --module=components  --style=sass
ng generate component  @theme\components\air-header        --module=components  --style=sass
ng generate component  @theme\components\air-search-input  --module=components   --style=sass
ng generate component  @theme\components\air-tiny-mce      --module=components   --style=sass

ng generate component  pages\dashboard\rooms       --module=dashboard  --style=sass
ng generate component  pages\dashboard\weather     --module=dashboard  --style=sass

ng generate component  pages\tables\smart-table   --module=tables  --style=sass
ng generate component  pages\tables\tree-grid     --module=tables  --style=sass

ng generate component  account\activate       --style=sass --module=account  
ng generate component  account\password       --module=account  --style=sass
ng generate component  account\password-reset --module=account  --style=sass
ng generate component  account\register       --module=account  --style=sass
ng generate component  account\sessions       --module=account  --style=sass
ng generate component  account\settings       --module=account  --style=sass


ng generate library air-lib  --skipInstall=true
ng generate module pages  --routing=true --project=air-lib  --module=air-lib

ng generate library air-lib2  --skipInstall=true
ng generate module pages  --routing=true --project=air-lib2  --module=air-lib2
