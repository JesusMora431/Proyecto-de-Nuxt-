<template>
    <div>
      <Header />
      <h1>Bienvenido a Nuestro Proyecto Nuxt</h1>
    <p>Este proyecto utiliza Nuxt.js para demostrar el uso de componentes, layouts y rutas.</p>
    <h2>Componentes del Proyecto</h2>
    <ul>
      <li><strong>Header:</strong> Navegación entre las páginas.</li>
      <li><strong>Footer:</strong> Información sobre derechos de autor.</li>
      <li><strong>Botón:</strong> Un botón interactivo que muestra un mensaje al hacer clic.</li>
    </ul>
      <Button label="Click me" />
    </div>
  </template>
  
  <script setup>
  import Header from '~/components/Header.vue';
  import Button from '~/components/ui/Button.vue';
  </script>