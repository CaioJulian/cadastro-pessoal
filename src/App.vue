<template>
  <span>
    <header>
      <nav-bar-vue logo="Social" url="#" cor="bg-success"/>
    </header>

    <main>
      <div class="container">
        <div class="row">

          <grid-vue tamanho="4">
            Menu
          </grid-vue>

          <grid-vue tamanho="8">
            <router-view/>
          </grid-vue>

        </div>
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
import GridVue from '@/components/layouts/GridVue'

export default {
  name: 'App',
  components:{
    NavBarVue,
    FooterVue,
    GridVue
  }
}
</script>

<style>

</style>
