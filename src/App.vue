<template>
  <span>
    <header>
      <nav-bar-vue logo="Social" url="#" cor="bg-success"/>
    </header>

    <main>
      <div class="container">
        <div class="row">

          <grid-vue tamanho="4">
            <card-menu-vue>
              <img src="" class="card-img-top" alt="">
              <div class="card-body">
                <h5 class="card-title">Maria</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </card-menu-vue>
            <card-menu-vue>
              <h3> Teste menu </h3>
            </card-menu-vue>
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
import CardMenuVue from '@/components/layouts/CardMenuVue'

export default {
  name: 'App',
  components:{
    NavBarVue,
    FooterVue,
    GridVue,
    CardMenuVue
  }
}
</script>

<style>

</style>
