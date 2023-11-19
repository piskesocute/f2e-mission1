<script setup></script>
<template>
  <section class="bg-bg-color-primary-theme">
    <div
      class="container px-0 py-64 py-md-60 py-xxl-64 d-flex flex-column justify-content-center align-items-center"
    >
      <div class="row w-100 mt-40 mb-xxl-64 p-0">
        <div class="col-12 col-md-6 ps-md-0 mb-24 mb-md-0">
          <div class="py-40 px-24 p-xxl-96 bg-primary-theme h-100 rounded-5">
            <p class="mb-16 text-white mantou-font fs-40 fs-xxl-52 lh-base">
              小額支持喵喵
            </p>
            <p class="mb-24 inter-font-semibold fs-20 lh-sm text-white">
              您的小筆捐款，是每隻毛孩未來的大大動力！
            </p>
            <div class="d-flex justify-content-center align-items-center gap-1">
              <div class="w-50">
                <button
                  type="button"
                  class="btn btn-white py-16 px-24 rounded-5"
                >
                  <span
                    class="fs-16 lh-base text-text-primary inter-font-bold me-1"
                    >小額捐款</span
                  >
                  <img
                    src="../assets/icons/arrow-right.svg"
                    alt=""
                  />
                </button>
              </div>
              <div class="w-50 overflow-hidden">
                <img
                  src="../assets/images/donate-img1.png"
                  alt=""
                  class="donate-img d-none d-xxl-block"
                />
                <img
                  src="../assets/images/donatepad-img1.png"
                  alt=""
                  class="donate-img d-xxl-none"
                />
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 col-md-6 pe-md-0">
          <div class="py-40 px-24 p-xxl-96 bg-text-primary h-100 rounded-5">
            <p class="mb-16 text-white mantou-font fs-40 fs-xxl-52 lh-base">
              民眾服務信箱
            </p>
            <p class="mb-24 inter-font-semibold fs-20 lh-sm text-white">
              親愛的鄉親，每一位市民的意見都是我們社區前進的原動力
            </p>
            <div class="d-flex justify-content-center align-items-center gap-1">
              <div class="w-50">
                <button
                  type="button"
                  class="btn btn-white py-16 px-24 rounded-5"
                >
                  <span class="text-text-primary inter-font-bold me-1"
                    >填寫表單</span
                  >
                  <img
                    src="../assets/icons/arrow-right.svg"
                    alt=""
                  />
                </button>
              </div>
              <div class="w-50 overflow-hidden">
                <img
                  src="../assets/images/donate-img2.png"
                  alt=""
                  class="donate-img d-none d-xxl-block"
                />
                <img
                  src="../assets/images/donatepad-img2.png"
                  alt=""
                  class="donate-img d-xxl-none"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.donate-img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
</style>
