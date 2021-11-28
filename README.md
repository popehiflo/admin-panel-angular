# ## Organización de directorios (posibles)
```
/e2e
/node_modules
/src
  /app
    /pagenotfound       ...Comp. para cualquier ruta no existente
    /auth               ...Toda la parte de autenticación
      /login            ...Comp. login
      /register         ...Comp. register
      auth.module.ts    ...Modulo donde se agrupa comp. de auth
    pages             ...Páginas o interfaces de nuestra app
      /account-settings ...Comp. configuracion de cuenta (Cambiar tema)
      component       ...Componentes personalizados
      form
      icons
      tables
      ...
      pages-routing.module.ts   ...Sub rutas, para gestionar comp. de /pages como hijas
      pages.component.xxx       ...Comp. donde se agrupa/renderiza paginas "protegidas"
      pages.module.ts           ...Modulo donde se agrupa componentes/paginas "protegidas"             
    shared            ...Componentes que se utilizan en toda la app
      /breadcrumbs
      /header
      /sidebar
      shared.module.ts   ...Donde se agrupa componentes compartidos
  /assets              ...Imagenes, Temas, CSS, Icons ...
    RECURSOS PARA EL TEMA, ANIMACION, COLOR ...
    https://animate.style/
    https://pictogrammers.github.io/@mdi/font/1.7.22/
    https://pxhere.com/

    https://valor-software.com/ng2-charts/#/GeneralInfo
    https://fontawesome.com/cheatsheet/free/solid
    https://getbootstrap.com/docs/4.1/components/buttons/
  /environments
    ...
.browserslistrc
.editorconfig
.gitignore
...
```
