# Nota para los colaboradores en Español:

Aunque este es un repo personal, hace parte del repo de `Staging`, proceso previo para hacer merge a el repo original. Esta decisión se tomó conjuntamente con @getify para reducir el ruido en el repo master, [siga conversación acá](https://github.com/getify/You-Dont-Know-JS/pull/1378).

Sin embargo, para todas las contribuciones habrá un `Contributors` pages en Español.

# ¿Cómo empezar a ser un colaborador?

1. Fork este proyecto y clonar su propio repositorio.
2. Hacer un branch nuevo `git checkout -b pr/branch-name`

> Tip: Mantega el `master` apuntando al repo original (Esto aplica para todos los repos de código libre)
> Así también se pueden hacer Pull Request desde su branches locales
>
> ```
> git remote add upstream https://github.com/You-Dont-Know-JS-ES/Traduccion.git
> git fetch upstream
> git branch --set-upstream-to=upstream/master master
> ```
>
> Esto agregará el repositorio original como "remote" y lo llama "upstream". Luego
> hará un "Fetch" del git y toda la info que esté remota, haciendo que su rama `master`
> local cuando se haga un `git pull` tome toda la información del repositorio remoto.
> Luego puede sacar todos los branches del `master` actualizado.
> De tal manera que siempre recomendamos actualizar su rama `master`.`git pull`

## Pull Request antes de iniciar una traducción

`Por favor hacer un PR antes de comenzar una traducción` Esto es un indicador para la comunidad de que usted va a trabajar en una traducción y evitar que cuando usted termine se de cuenta de que ya alguién trabajó en eso antes.

La unidad mínima de traducción es en Markdown un bloque de `###` ó `##`.

### Sobre el nombre de su(s) branch(es):

Se deben llamar los branches con el siguiente formato: 
  `pr/título_del_libro/nombre_de_capitulo/#titulo/##subtema/###subtema` según sea el caso. 

### Sobre el nombre de su pull request: 

 Una vez se haya decidido a traducir una sección de cualquiera de los libros, por favor asignar un título a su pull request de la siguiente forma
 
  `[InProgress]título_del_libro/nombre_de_capitulo/#titulo/##subtema/###subtema` según sea el caso. 

Si luego de realizar los cambios necesarios, considera que su traducción definitivamente se encuentra lista para revisión por favor renombrar su pull request como
  
  `[Done]título_del_libro/nombre_de_capitulo/#titulo/##subtema/###subtema` según sea el caso.

La filosofía de trabajo es: traducir el archivo, y todo trabajo pendiente se deja en inglés, para que sea claro para los colaboradores lo que hace falta por traducir.

Para este proceso se debe tener en cuenta la seccion que se tradujo con los siguientes parametros:

1. Revisar si el branch ya se encuntre de manera remota para evitar multiples ramas con nombres iguales `git branch -r`. Si el branch existe y falta terminar la traducción o desea corregirlo, hacer el pull correspondiente al branch a editar `git pull origin pr/../..`
2. Si el branch no existe, al crearlo, el nombre debe seguir la siguiente estructura teniendo en cuenta los títulos que se representan con el signo numeral (#) en el .md. Con base en lo anterior, se espera lo siguiente: `pr/título_del_libro/nombre_de_capitulo/#titulo/##subtema/###subtema` según sea el caso.
3. Realizar el debido push al repositorio de su cuenta. Si ya su traducción definitivamente se encuentra lista para revisión, renombrar  el PR como `[Done]título_del_libro/nombre_de_capitulo/#titulo/##subtema/###subtema` para que el revisor quede notificado.
4. Si ya ha hecho varios commits y piensa subir su versión final, por favor hacer un rebase interactivo en su local a master y dejar un solo commit con el mismo nombre del branch. Para mayor información sobre como realizar esto, visite este [enlace](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)

## Parametros a tener en cuenta en el momento de la traducción

Esta es una traducción hecha por contribuidores por lo que su interpretacion puede variar de acuerdo al usuario. Es importante tener en cuenta que las anectodas o pensamientos que el autor mencione, traducirlos en primera persona y los demas textos en tercera persona.

# El order de traduccíon será el siguiente

## Titles

En este momento vamos a comenzar el primer libro. Detalles de donde se va en el capitulo se detallarán acá:

- Read online (free!): ["Up & Going"](up%20&%20going/README.md#you-dont-know-js-up--going), Published: [Buy Now](http://www.ebooks.com/1993212/you-don-t-know-js-up-going/simpson-kyle/) in print, but the ebook format is free!
- Read online (free!): ["Scope & Closures"](scope%20&%20closures/README.md#you-dont-know-js-scope--closures), Published: [Buy Now](http://www.ebooks.com/1647631/you-don-t-know-js-scope-closures/simpson-kyle/)
- Read online (free!): ["this & Object Prototypes"](this%20&%20object%20prototypes/README.md#you-dont-know-js-this--object-prototypes), Published: [Buy Now](http://www.ebooks.com/1734321/you-don-t-know-js-this-object-prototypes/simpson-kyle/)
- Read online (free!): ["Types & Grammar"](types%20&%20grammar/README.md#you-dont-know-js-types--grammar), Published: [Buy Now](http://www.ebooks.com/1935541/you-don-t-know-js-types-grammar/simpson-kyle/)
- Read online (free!): ["Async & Performance"](async%20&%20performance/README.md#you-dont-know-js-async--performance), Published: [Buy Now](http://www.ebooks.com/1977375/you-don-t-know-js-async-performance/simpson-kyle/)
- Read online (free!): ["ES6 & Beyond"](es6%20&%20beyond/README.md#you-dont-know-js-es6--beyond), Published: [Buy Now](http://www.ebooks.com/2481820/you-don-t-know-js-es6-beyond/simpson-kyle/)
