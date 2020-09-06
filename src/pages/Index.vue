<template>
<div style="height: 100vh;background-color: #002e44; color: #afbfdf; text-align: center; width: 100vw; height: 100vh; margin: auto;">
  <Layout>
    
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="./logo.png" style="margin: auto;" width="435" />
    
    <h1>Пленер Клюква</h1>
   
    <p style="margin: auto;">
      - это международный аудиовизуальный ежегодный пленер, проходящий в интересных северных местах республики коми и окрестностей.
    </p>

    <p class="home-links" style="margin: auto;">
      <a href="https://gridsome.org/docs" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>

  </Layout>
</div>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.body{
	background-color: #002e44;
	color: #ededed;
}
.a{
	color: #e49e23;
}
.home-links a {
  margin-right: 1rem;
	color: #aebede;
}
</style>
