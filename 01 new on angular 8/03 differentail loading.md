pollyfill sirve para agregar un script en caso que el navegador sea muy antiguo.
Es una funcionalidad que ya esta en angular por defecto.

Pero pollyfill ya tiene un defecto es que esta agregando este script con ese peso para todas los navegadores.

Entonces con angular 8 se puede solucionar.

Recuerda que polyfill genera

polifill-es5 para navegadores viejos.
polifill-es2015 para navegadores nuevoes.

entonces en polyfill hay el type="module" que solo agrega el scrit es2015 en caso lo necesitemos.

```json

{
  "compileOnSave": ..,
  "compilerOptions": {
...
    "module": "esnext",
    ...
    "target": "es2015",
...
    ]
  }
}
 ```