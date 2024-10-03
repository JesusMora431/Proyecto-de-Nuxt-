<<template>
    <button class="btn" @click="handleClick">{{ label }}</button>
  </template>
  
  <script setup>
  defineProps({
    label: {
      type: String,
      required: true
    }
  });
  
  // Función para manejar el clic
  const handleClick = () => {
    alert('¡Botón clicado!'); // Prueba si esto se muestra al hacer clic
  };
  </script>
  
  <style scoped>
  .btn {
    padding: 10px 20px;
    background-color: #42b883;
    color: white;
    border: none;
    border-radius: 5px;
    cursor: pointer; /* Cambia el cursor al pasar por encima */
  }
  
  .btn:hover {
    background-color: #36a77b; /* Cambia el color en hover */
  }
  </style>