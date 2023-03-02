<template>
  <section class="wow animate__fadeIn">
    <div class="container">
      <div class="row">
        <div class="col-12 blog-content">
          <ul
            class="blog-grid blog-wrapper grid grid-3col xl-grid-3col lg-grid-3col md-grid-2col sm-grid-2col xs-grid-1col hover-option4 blog-post-style3 gutter-extra-large"
          >
            <li class="grid-sizer"></li>

            <!-- start post item -->
            <li
              class="grid-item last-paragraph-no-margin text-center text-sm-start wow animate__fadeInUp"
              data-wow-delay="0.2s"
            >
              <div class="blog-post bg-light-gray">
                <div class="blog-post-images overflow-hidden position-relative">
                  <a href="blog-post-layout-02.html">
                    <img
                      src="https://via.placeholder.com/900x650"
                      alt=""
                      class="img-blok"
                    />
                    <div class="blog-hover-icon">
                      <span class="text-extra-large font-weight-300">+</span>
                    </div>
                  </a>
                </div>
                <div class="post-details padding-40px-all md-padding-20px-all">
                  <a
                    href="blog-post-layout-02.html"
                    class="alt-font post-title text-medium text-extra-dark-gray w-100 d-block lg-w-100 margin-15px-bottom"
                    ><h4>Nama Produk</h4></a
                  >
                  <p>deskriipsi produk</p>
                  <div
                    class="separator-line-horrizontal-full bg-medium-gray margin-20px-tb"
                  ></div>
                  <div class="author">
                    <!-- <span
                      class="text-medium-gray text-uppercase text-extra-small d-inline-block"
                      >by
                      <a href="blog-masonry.html" class="text-medium-gray"
                        >Herman Miller</a
                      >&nbsp;&nbsp;|&nbsp;&nbsp;29 April 2017</span
                    > -->
                    <NuxtLink
                      to="/kelas"
                      class="btn btn-white border link-header btn-header medium btn-rounded align-top sm-no-margin-right text-capitalize"
                    >
                      Beli Produk
                    </NuxtLink>
                  </div>
                </div>
              </div>
            </li>
            <!-- end post item -->
          </ul>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.img {
  max-width: 100px;
}
</style>
