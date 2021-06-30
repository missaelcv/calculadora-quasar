# Quasar App (calculadora1)

A Quasar Framework app

## Install the dependencies
```javascript
npm install
```
## Name and Proyect 
```javascript
quasar create <folder_name> --branch next
```

### Lint the files install the next code in CMD
```javascript
npm i mathjs
```

### Start the app in development mode
```javascript
quasar dev
```

### Build the app for production
```bash
quasar build
```

## Cambio de hash a history en quasar.confing
```javascript
 vueRouterMode: 'history',
 ```

## Index.vue Inicio para modificacion 
```javascript
<template>
  <q-page class="flex flex-center">
    <img  alt="Quasar logo" src="~assets/quasar-logo-vertical.svg"
      style="width: 200px; height: 200px">
  </q-page>
</template>
<script>
import { defineComponent } from 'vue';
export default defineComponent({
  name: 'PageIndex'
})
</script>
```

## Centralizar columnas
```javascript
 <div class="row justify-center">
 ```


## Creando la Tarjeta con Section y clase para Creal el Texto de la calculadora
```javascript
 <div class="row justify-center">
     <div class="col-12 col-md-8">
       <q-card>
         <q-card-section class="bg-primary text-white">
           <div class=" text-h6">Calculadora App</div>
         </q-card-section>
       </q-card>
    </div>  </div>
```

### Customize the configuration
See [Configuring quasar.conf.js](https://v2.quasar.dev/quasar-cli/quasar-conf-js).
