<template>
  <span>
    <header>
      <nav-bar-vue logo="Social" url="#" cor="bg-success"/>
    </header>
    
    <main>
      <div class="container">
        <router-view/>
      </div>
    </main>

    <footer>
      <footer-vue logo="Social" cor="bg-success"/>
    </footer>
  </span>
</template>

<script>
import NavBarVue from '@/components/layouts/NavBarVue'
import FooterVue from '@/components/layouts/FooterVue'

export default {
  name: 'App',
  components:{
    NavBarVue,
    FooterVue
  }
}
</script>

<style>

</style>
