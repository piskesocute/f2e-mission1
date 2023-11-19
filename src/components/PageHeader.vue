<script setup></script>
<template>
  <NavbarComponent />
  <section class="container-fluid header-height overflow-hidden">
    <div class="row">
      <h2
        class="mantou-font fs-52 fs-lg-96 lh-1 mt-32 mt-lg-96 mb-16 text-center"
      >
        <span class="my-class d-lg-block d-none">台灣的明天 喵先鋪路</span>
        <span class="my-class d-lg-none d-block">台灣的明天</span>
        <span class="my-class d-lg-none d-block">喵先鋪路</span>
      </h2>
    </div>
    <div class="row mb-8">
      <div
        class="d-flex flex-column flex-md-row justify-content-center align-items-center gap-md-16"
      >
        <div
          class="text-center rounded-4 bg-text-primary text-white py-12 px-16 my-md-8"
        >
          <h3 class="mb-0 inter-font-bold fs-20 fs-lg-28 lh-base">
            2024 立委參選人
          </h3>
        </div>
        <div
          class="d-flex justify-content-center align-items-center py-12 px-16 box-shadow rounded-4"
        >
          <div
            class="rounded-circle number-three d-flex justify-content-center align-items-center btn-primary-gradient text-white me-16"
          >
            <span class="fs-24 fs-lg-32 lh-base inter-font-black">3</span>
          </div>
          <h3
            class="mb-0 inter-font-bold text-primary-theme fs-28 fs-lg-40 lh-base"
          >
            喵立翰 Miao Li-Han
          </h3>
        </div>
      </div>
    </div>
    <!-- 一個佔滿剩下高度空間的img -->
    <div class="row">
      <div class="d-flex justify-content-center align-items-center">
        <img
          src="@/assets/images/headerimg.svg"
          alt=""
          class="img-fluid max-height"
        />
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.number-three {
  width: 50px;
  height: 50px;
  @include md {
    width: 40px;
    height: 40px;
  }
}
.header-height {
  height: auto;
}
.max-height {
  max-height: 100%;
  object-fit: contain;
}
.box-shadow {
  box-shadow: 0px 4px 12px #a3b4cb33;
}
</style>
