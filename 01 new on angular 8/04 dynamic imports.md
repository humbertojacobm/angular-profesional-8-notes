app-routing.module.ts
```typescript

 {
        path: 'home',
        loadChildren: 
          () => import('./home/home.module')
                .then(m => m.HomeModule)
 }

```
La idea es que la ruta sea dinamica para que el seo y el webpack sigan funcionando.

Pero en un caso extremo podrias hacer que eso sea dinamico.