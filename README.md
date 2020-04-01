# my-angular-cli
创建Angular的批处理命令集

AaBb1234567890-=

AaBb1234567890-=

npm install --save @angular/material @angular/cdk @angular/animations


ng new air-workspace --create-application=false  --routing=true --style=scss --skipInstall=true
cd air-workspace

ng generate application air-application  --routing=true --prefix=air   --force=true

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


ng generate component  @theme\components\air-footer        --module=components  --style=scss
ng generate component  @theme\components\air-header        --module=components  --style=scss
ng generate component  @theme\components\air-search-input  --module=components   --style=scss
ng generate component  @theme\components\air-tiny-mce      --module=components   --style=scss

ng generate component  pages\dashboard\rooms       --module=dashboard  --style=scss
ng generate component  pages\dashboard\weather     --module=dashboard  --style=scss

ng generate component  pages\tables\smart-table   --module=tables  --style=scss
ng generate component  pages\tables\tree-grid     --module=tables  --style=scss

ng generate component  account\activate       --style=scss --module=account  
ng generate component  account\password       --module=account  --style=scss
ng generate component  account\password-reset --module=account  --style=scss
ng generate component  account\register       --module=account  --style=scss
ng generate component  account\sessions       --module=account  --style=scss
ng generate component  account\settings       --module=account  --style=scss


ng generate library air-lib  --skipInstall=true

ng generate module framework-library  --routing=true --project=air-lib  --module=air-lib
ng generate module material-design-framework  --routing=true --project=air-lib  --module=framework-library
ng generate component  air-lib\framework-library\material-design-framework\material-button-group.component     --project=air-lib --module=material-design-framework   --style=scss
ng generate component  air-lib\framework-library\material-design-framework\material-input.component.component  --project=air-lib --module=material-design-framework   --style=scss
ng generate component  air-lib\framework-library\material-design-framework\material-number.component           --project=air-lib --module=material-design-framework   --style=scss
ng generate component  air-lib\framework-library\material-design-framework\material-checkboxes.component       --project=air-lib --module=material-design-framework   --style=scss

ng generate module widget-library  --routing=true --project=air-lib    --project=air-lib --module=air-lib
ng generate component  air-lib\widget-library\section.component.ts     --project=air-lib --module=widget-library   --style=scss
ng generate component  air-lib\widget-library\submit.component.ts      --project=air-lib --module=widget-library   --style=scss



