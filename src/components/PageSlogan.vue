<script setup></script>
<template>
  <section class="bg-bg-color-primary-theme">
    <div
      class="container py-64 d-flex flex-column justify-content-center align-items-center"
    >
      <div class="my-40 text-center">
        <p
          class="my-class mantou-font d-none d-xxl-block fs-xxl-64 lh-base mb-16"
        >
          台灣的明天 喵先鋪路
        </p>
        <p class="my-class mantou-font fs-52 mb-0 d-xxl-none lh-1">
          台灣的明天
        </p>
        <p class="my-class mantou-font fs-52 mb-24 lh-1 d-xxl-none">喵先鋪路</p>
        <div class="d-inline-block">
          <div
            class="d-flex justify-content-center align-items-center bg-xxl-white rounded-4 py-12 px-16 box-shadow"
          >
            <div
              class="rounded-circle number-three d-flex justify-content-center align-items-center btn-primary-gradient text-white me-16"
            >
              <span class="fs-24 fs-xxl-32 lh-base inter-font-black">3</span>
            </div>
            <h3
              class="mb-0 inter-font-bold text-primary-theme fs-24 fs-xxl-40 lh-base mb-0"
            >
              喵立翰 Miao Li-Han
            </h3>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.number-three {
  width: 50px;
  height: 50px;
  @include md {
    width: 33px;
    height: 33px;
  }
}
.box-shadow {
  box-shadow: 0px 4px 12px #a3b4cb33;
  @include md {
    box-shadow: none;
  }
}
</style>
