<template>
  <!-- start header -->
  <header>
    <nav
      class="navbar navbar-default bootsnav navbar-top header-light background-transparent nav-box-width white-link navbar-expand-lg"
    >
      <div class="logonav container-fluid nav-header-container">
        <a href="/">
          <img
            src="~/static/assets/image/logoprojek.png"
            alt="hanado coffee"
            class="img-fluid img-responsive w-140px"
          />
        </a>

        <div class="col accordion-menu pe-0 pe-md-3">
          <button
            type="button"
            class="navbar-toggler collapsed"
            data-bs-toggle="collapse"
            data-bs-target="#navbar-collapse-toggle-1"
          >
            <span class="sr-only">toggle navigation</span>
            <i class="fa fa-bars"></i>
          </button>
          <div
            class="navbar-collapse collapse justify-content-end"
            id="navbar-collapse-toggle-1"
          >
            <ul
              id="accordion"
              class="nav navbar-nav no-margin alt-font text-normal"
              data-in="animate_fadeIn"
              data-out="animate_fadeOut"
            >
              <li class="btn btn-sm">
                <a href="/">Beranda</a>
              </li>
              <li class="btn btn-sm">
                <a href="/about-us">Tentang Kami</a>
              </li>
              <li class="btn btn-sm">
                <a href="">produk</a>
              </li>
              <li class="btn btn-sm">
                <a href="">Login</a>
              </li>
              <!-- <li class="nav-item d-flex align-items-center">
                <button v-if="!isLoaded" class="btn btn-sm">
                  <p class="align-middle">Loading</p>
                </button>
                <a v-else :href="urlAction" class="btn btn-sm">
                  {{ isAuthenticated ? "Dashboard" : "Masuk" }}
                </a>
              </li> -->
            </ul>
          </div>
        </div>
      </div>
    </nav>
  </header>
  <!-- end header -->
</template>

<style>
header a.logo img {
  max-height: 100px !important;
}
img.logonav {
  width: 50%;
}
.img-fluid {
  height: 50px;
}
</style>
