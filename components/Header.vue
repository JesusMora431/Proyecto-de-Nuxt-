<template>
    <header class="header">
      <nav>
        <ul>
          <li><NuxtLink to="/">Inicio</NuxtLink></li>
          <li><NuxtLink to="/about">Acerca de</NuxtLink></li>
          <li><NuxtLink to="/contact">Contacto</NuxtLink></li>
        </ul>
      </nav>
    </header>
  </template>
  
  <script setup>
  
  </script>
  
  <style scoped>
  .header {
    background-color: #333;
    padding: 1rem;
    color: white;
  }
  
  nav ul {
    list-style-type: none;
    display: flex;
    gap: 1rem;
  }
  
  nav ul li {
    display: inline;
  }
  
  a {
    color: white;
    text-decoration: none;
  }
  
  a:hover {
    text-decoration: underline;
  }
  </style>