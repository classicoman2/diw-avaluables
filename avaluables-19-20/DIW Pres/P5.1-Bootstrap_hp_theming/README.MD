 # P5.1 Bootstrap Law page
  The practice instructions are available [here](https://docs.google.com/document/d/11Z3gUzkBTwO1wgG_K-ztp-jCrTAGXYZNtEgs4WBdAuU/edit#)

## Theming
The student must use [Bootstrap Theming](https://github.com/classicoman2/bootstrap4-theming-test) 

## Canvis Juny 2020

- Paleta de colors creada amb: https://material.io/design/color/the-color-system.html#tools-for-picking-colors
- Color primari i variants de color primari
- Paleta del color primari disponible aqui:  https://material.io/resources/color/#!/?view.left=0&view.right=0&primary.color=3d6b1e

## Fitxer custom.scss

- Inclou els fitxers .scss necessaris - he optat per la solució més senzilla, carregant-ho tot a l'hora. Podria triar carregar només els fitxers .scss de Bootstrap que me fessin falta.
- Override de variables com `$body-bg` o `$theme-colors`
- Override de classes com `btn-primary`i `btn-secondary` (doncs estic pintant aquest botó amb un color secundari) i ....

Per a que aquesta pàgina funcioni, s'ha d'establir un mecanisme per compilar el SCSS a CSS i també, s'ha d'instal·lar manualment el bootstrap

`npm install bootstrap`