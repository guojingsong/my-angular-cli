

// 建立workSpace

ng new prototype-lib --create-application=false  --routing=true --style=scss --skipInstall=true

cd prototype-lib 

// 建立Lib
ng generate library prototype-lib-client  --skipInstall=true

ng generate directive csv-out  --project prototype-lib-client

ng generate module prototype-lib-client  --project prototype-lib-client

ng generate service --project prototype-lib-client.

```
PS D:\GitLibWorkSpace\prototype-lib> npm run test
> prototype-lib@0.0.0 test D:\GitLibWorkSpace\prototype-lib
> ng test prototype-lib-client
```

// Git remote 设定
git remote add origin http://192.168.7.187/AirDO/prototype-lib.git   

