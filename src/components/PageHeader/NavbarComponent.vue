<script setup></script>
<template>
  <nav class="page-nav px-24 bg-bg-color-primary-theme">
    <div class="container-fluid px-24 py-12 nav-box-bg rounded-4 mt-16">
      <div class="d-flex justify-content-between align-items-center w-100">
        <a
          class="navbar-brand d-flex justify-center align-items-center m-0 gap-8 py-0"
          href="#"
        >
          <div class="logo-icon">
            <img
              src="@/assets/images/logo.svg"
              alt=""
              class="img-fluid"
            />
          </div>

          <h1
            class="inter-font-bold fs-20 fs-md-24 lh-base text-primary-theme mb-0"
          >
            喵立翰 Miao Li-Han
          </h1>
        </a>
        <ul
          class="list-unstyled mb-0 justify-content-center align-items-center gap-10 fs-18 text-primary-theme d-none d-lg-flex"
        >
          <li>
            <a
              href=""
              class="text-text-primary fw-normal"
              >候選人主張</a
            >
          </li>
          <li>
            <a
              href=""
              class="text-text-primary fw-normal"
              >最新活動</a
            >
          </li>
          <li>
            <a
              href=""
              class="text-text-primary fw-normal"
              >政策議題</a
            >
          </li>
          <li>
            <a
              href=""
              class="text-text-primary fw-normal"
              >小額捐款</a
            >
          </li>
          <li>
            <a
              href=""
              class="text-text-primary fw-normal"
              >民眾服務信箱</a
            >
          </li>
        </ul>
        <ul
          class="list-unstyled mb-0 justify-content-center align-items-center gap-16 d-none d-md-flex"
        >
          <li>
            <a href="">
              <img
                src="@/assets/images/facebook.svg"
                alt=""
              />
            </a>
          </li>
          <li>
            <a href="">
              <img
                src="@/assets/images/instagram.svg"
                alt=""
              />
            </a>
          </li>
          <li>
            <a href="">
              <img
                src="@/assets/images/youtube.svg"
                alt=""
              />
            </a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>
<style lang="scss" scoped>
.page-nav {
  padding-top: 99px;
  @include md {
    padding-top: 0px;
    padding-bottom: 16px;
  }
}

.nav-box-bg {
  width: calc(100% - 48px);
  background-color: #ffffffe5;
  position: fixed;
  z-index: 1;
  top: 0;

  @include md {
    position: relative;
    width: 100%;
  }
  @include sm {
  }
}
.logo-icon {
  width: 100%;
  height: auto;
  @include md {
    width: 34px;
    height: auto;
  }
}
</style>
