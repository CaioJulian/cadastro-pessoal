<template>

        <!-- Footer -->
        <footer :class="'page-footer pt-4 text-white ' + cor" >
            <!-- Container -->
            <div class="container">

                <!-- Footer Links -->
                <div class="container-fluid text-center text-md-left">

                <!-- Grid row -->
                <div class="row">

                    <!-- Grid column -->
                    <div class="col-md-9 mt-md-0 mt-3">

                    <!-- Content -->
                    <h5 class="text-uppercase">{{logo}}</h5>
                    <p>Here you can use rows and columns here to organize your footer content.</p>

                    </div>
                    <!-- Grid column -->

                    <hr class="clearfix w-100 d-md-none pb-3">

                    <!-- Grid column -->
                    <div class="col-md-3 mb-md-0 mb-3">

                        <!-- Links -->
                        <h5 class="text-uppercase">Links</h5>

                        <ul class="list-unstyled">
                        <li>
                            <a href="#!" class="text-white">Link 1</a>
                        </li>
                        <li>
                            <a href="#!" class="text-white">Link 2</a>
                        </li>
                        <li>
                            <a href="#!" class="text-white">Link 3</a>
                        </li>
                        <li>
                            <a href="#!" class="text-white">Link 4</a>
                        </li>
                        </ul>

                    </div>
                    <!-- Grid column -->

                </div>
                <!-- Grid row -->

                </div>
                <!-- Footer Links -->

                <!-- Copyright -->
                <div class="footer-copyright text-center py-3 text-white-50">© 2019 Copyright {{logo}}
                </div>
                <!-- Copyright -->
                
            </div>
            <!-- Container -->

        </footer>
        <!-- Footer -->


</template>

<script>
export default {
  name: 'FooterVue',
  props:['logo','cor'],
  data () {
    return {
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
