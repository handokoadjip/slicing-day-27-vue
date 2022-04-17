<template>
  <footer>
    <div class="container">
      <div class="row align-items-center py-4">
        <div class="col-lg-12 d-flex justify-content-center">
          <div class="wrapper">
            <ul class="text-uppercase d-inline mp-0">
              <li class="d-inline">
                <router-link class="nav-link fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">Home
                </router-link>
              </li>
              <li class="d-inline">
                <router-link class="nav-link fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">Products
                </router-link>
              </li>
              <li class="d-inline">
                <router-link class="nav-link fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">Imprint
                </router-link>
              </li>
              <li class="d-inline">
                <router-link class="nav-link fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">Contact
                </router-link>
              </li>
              <li class="d-inline">
                <router-link class="nav-link fw-bold d-lg-inline d-block text-fade-2 text-center" to="#">Cart
                </router-link>
              </li>
            </ul>
          </div>
        </div>
      </div>

      <div class="row align-items-center pt-3 pb-4">
        <div class="col-lg-12 d-flex justify-content-center">
          <div class="wrapper">
            <p class="m-0 fs-6 text-fade-3 text-center">Copyright &copy; KAMI</p>
          </div>
        </div>
      </div>

      <div class="row align-items-center py-5">
        <div class="col-lg-12 d-flex justify-content-center">
          <div class="wrapper">
            <router-link class="fs-5 text-uppercase px-5 py-3 border border-secondary border-3" to="">back to site
            </router-link>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>