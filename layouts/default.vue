<template>
  <div class="layout">
    <head>
      <link href="https://fonts.googleapis.com/css2?family=Rubik:wght@300;400;500;900&family=Source+Serif+Pro&display=swap" rel="stylesheet">
    </head> 
    <Header />
    <nuxt class="nuxt-content"/>
    <Footer/>
  </div>
</template>
<script>

  import Header from '~/components/Sections/Header'
  import Footer from '~/components/Sections/Footer'

  export default {
    components: {
      Header,
      Footer
    }
  }
</script>
<style lang="scss">
.layout {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

.nuxt-content {
  flex-grow: 1;
}
</style>
