<template>
  <div>
    <about-description></about-description>
    <h2 class="h1 mb-4">Experiencia laboral</h2>
    <div class="row mb-4">
      <about-skill
        skill="Diseñador gráfico"
        desc="Desde las redes sociales hasta los folletos. Marco el tono visual de las marcas en los medios digitales e impresos."
        svg-icon="#stack-1"
      ></about-skill>
      <about-skill
        skill="Diseñador Web"
        desc="Wireframing y creación de prototipos. Crear la estructura del sitio web y la interfaz de usuario."
        svg-icon="#laptop-screen-1"
      ></about-skill>
    </div>
  </div>
</template>

<script>
export default {
  name: 'AboutComponent',
}
</script>
