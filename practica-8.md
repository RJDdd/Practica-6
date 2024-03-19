a. ¿Cómo se inicializa un repositorio en Git? 

  Con git init 

b. ¿Cómo creas un repositorio en GitHub? 

  Se pude iniciar mediante github en -> Home -> New

c. ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub? 

  Con este orden: 
  git init
  git add .
  git commit -m "Primer commit"
  git branch -M main
  git remote add origin https://github.com/usuario/repositorio.git
  git push -u origin main

d. ¿Cuál es el flujo básico de trabajo en Git y GitHub? 

  Primero haces un archivo "*.md*", con la terminal "git add ." luego git commit -m "Primer commit"" sea un nuevo repositorio sigue: "git branch -M main" y "git remote add origin https://github.com/usuario/repositorio.git". Si no es un nuevo repositorio saltas el paso anterior y usas "git push -u origin main"

e. ¿Para qué sirve el archivo .gitignore? 

  Sirve para que el repositorio no senseñe archivos expecificos que escoje el programador

f. ¿Cuál es el propósito de una rama? 

  Poder que distintos peogramadores puedan trabajar uno mas archivos y hacerle cambios en paralelo a los demás.

g. ¿Qué es una fusión? 

  Cuando haces "git marge" entre 2 ramas 

h. Explica los diferentes tipos de fusión que existen. 

  Puedes fucionar una rama secundaria a la principal o entre 2 ramas secundarias

i. ¿Cómo puedes ver el historial de tu repositorio? 

  Mediante github viendo los commits hechos

j. ¿Cuál es el propósito de una etiqueta? 

  No lo se. 
  