<script>
import HorizontalTopbar from "./partials/horizontal-topbar";
import HorizontalNav from "./partials/horizontal-nav";
import RightBar from "./partials/right-bar";
import Footer from "./partials/footer";


/**
 * Horizontal-layout
 */
export default {
  components: {
    HorizontalTopbar,
    HorizontalNav,
    Footer,
    RightBar,
  },
  data() {
    return {};
  },
  computed: {
   
  },
  created: () => {
  
  },
  methods: {
    
  },
  mounted() {
   
  },
};
</script>

<template>
  <div>
    <!-- Begin page -->
    <div id="layout-wrapper">
      <HorizontalTopbar :type="'light'" :width="'fluid'" />
      <HorizontalNav />
      <!-- ============================================================== -->
      <!-- Start right Content here -->
      <!-- ============================================================== -->
      <div class="main-content">
        <div class="page-content">
          <div class="container-fluid">
            <slot />
          </div>
          <!-- container-fluid -->
        </div>
        <!-- End Page-content -->
        <Footer />
      </div>
      <!-- end main content-->
    </div>
    <!-- END layout-wrapper -->
    <RightBar />
  </div>
</template>