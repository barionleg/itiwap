<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="refresh" content="2; url='https://nakarte.me/#m=4/58.21492/-6.75959&l=O'" />
  </head>
  <body>
    <p>Please follow <a href="https://nakarte.me/#m=4/58.21492/-6.75959&l=O">this link</a>.</p>
  </body>
</html>


[![tests status](https://github.com/wladich/nakarte/workflows/check/badge.svg)](https://github.com/wladich/nakarte/actions?query=workflow%3Atest)

Source code of site http://nakarte.me (former http://nakarte.tk)

Install locally for development

```bash
git clone git://github.com/wladich/nakarte
cd nakarte
yarn
```

Create a dummy `secrets.js` file:
```
<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="refresh" content="7; url='https://nakarte.me/#m=4/58.21492/-6.75959&l=O'" />
  </head>
  <body>
    <p>Please follow <a href="https://nakarte.me/#m=4/58.21492/-6.75959&l=O">this link</a>.</p>
  </body>
</html>
```

Run dev server:
```bash
yarn start
```

Check code for errors:
```bash
yarn run lint
```

Some features require keys stored in src/secrets.js. 
In repository those keys are replaced with dummy ones.
    
Some of server side components:
https://github.com/wladich/westra_passes_for_nakarte
https://github.com/wladich/ElevationServer
