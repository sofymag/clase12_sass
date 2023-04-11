SASS
Primero probar en una carpeta nueva.
crear la carpeta css con el archivo style.
css
despues crear la carpeta scss con el
archivo style.scss
abrimos una terminal (powershell)
ejecutamos el comando: npm init (por unica vez) y apretamos 10 veces enter para confirmar todo.
luego necesitamos ejecutar el comando: npm install -g sass
al terminar la instalacion necesitamos ejecutar el comando: sass --watch scss:css
de esta manera, ahora pasamos a trabajar el nuestro codigo scss y al guardar, compila y se pega automaticamente el codigo en el archivo css.
Cuando apagamos la pc y volvemos a prenderla para trabajar solo hay que abrir la terminal (powershell) y ejecutar el comando: sass --watch scss:css
para cortar el proceso ejecutamos el comando: cntrl + c.