
<template>
  <div class="layout">

    <header class="header">
      <nav class="nav" style="margin: auto; position: sticky; z-index:2;">
        <g-link class="nav__link" to="/">Главная</g-link>
       <g-link class="nav__link" to="/news">Новости</g-link>
       <g-link class="nav__link" to="/plainairs">Пленеры</g-link>
<g-link class="nav__link" to="/map">Карта</g-link>       
       <g-link class="nav__link" to="/participants">Участники</g-link>
        <g-link class="nav__link" to="/about">О проекте</g-link>
      </nav>
    </header>
    <g-image alt="--------" src="./w2.png" style="margin: auto; margin-bottom: 50px; margin-top: -85px; max-width: 500px; opacity: 0.1; position: sticky; z-index: 0;" />
    <slot/>
  </div>
</template>

<static-query>
query {
  metaData {
    siteName
  }
}
</static-query>

<style>

body {
	background-color: 002e44;
  font-family: Source Sans Pro,Arial,sans-serif;
  margin:0;
  padding:0;
  line-height: 1.5;
}

.layout {
  max-width: 760px;
  margin: 0 auto;
  padding-left: 20px;
  padding-right: 20px;
}

.header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
  height: 80px;
}

.nav__link {
  margin-left: 25px;	
color: #aebede;
}

</style>
