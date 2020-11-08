<script>

export default {
  data() {
    return {};
  },
  mounted() {},
  methods: {}
};
</script>
<template>
  <div class="topnav">
    <div class="container-fluid">
      <nav class="navbar navbar-light navbar-expand-lg topnav-menu">
        <div id="topnav-menu-content" class="collapse navbar-collapse">
          <ul class="navbar-nav">

            <li class="nav-item">
              <router-link class="nav-link" :to="{name: 'jobs'}">
              
                <i class="bx bx-briefcase mr-2"></i>
                Jobs
              </router-link>
            </li>

            <li class="nav-item">
              <router-link class="nav-link" :to="{name: 'ajenda'}">
                <i class="bx bx-calendar mr-2"></i>
                Ajenda
              </router-link>
            </li>

            <li class="nav-item">
              <router-link class="nav-link" :to="{name: 'mails'}">
                <i class="bx bx bx-envelope mr-2"></i>
                Mails
              </router-link>
            </li>

            <li class="nav-item">
              <router-link class="nav-link" :to="{name: 'reports'}">
                <i class="bx bx bx-bar-chart-alt mr-2"></i>
                Reports
              </router-link>
            </li>

            <li class="nav-item">
              <router-link class="nav-link" :to="{name: 'settings'}">
                <i class="bx bx bxs-cog mr-2"></i>
                Settings
              </router-link>
            </li>

          </ul>
        </div>
      </nav>
    </div>
  </div>
</template>