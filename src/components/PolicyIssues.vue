<script setup>
import { ref } from 'vue';

const data = ref([
  {
    title: '為毛孩子謀福利！<br/>推動寵物醫療保障方案',
    img: '../assets/images/policy-img1.png',
  },
  {
    title: '打造休閒天堂！<br/>推廣寵物休閒與娛樂場所',
    img: '../assets/images/policy-img2.png',
  },
  {
    title: '推廣寵物飼養教育，讓愛更加專業',
    img: '../assets/images/policy-img3.png',
  },
]);
const getImgUrl = (img) =>
  new URL(`../assets/images/${img}`, import.meta.url).href;
</script>
<template>
  <section class="bg-bg-color-primary-theme">
    <div
      class="container py-64 d-flex flex-column justify-content-center align-items-center"
    >
      <div class="row mt-xxl-40 mb-80 mb-xxl-64">
        <SectionTitle>
          <template #enTitle>POLICY ISSUES</template>
          <template #zhTitle>政策議題</template>
        </SectionTitle>
      </div>
      <div class="mb-xxl-40 d-flex g-md-24 g-xxl-64 row w-100">
        <div
          class="col-12 col-md-6 col-xxl-4 mb-64 mb-md-0 d-flex flex-column justify-content-between"
        >
          <h4 class="mb-0 inter-font-bold fs-24 lh-base px-16 pb-16">
            為毛孩子謀福利！<br />推動寵物醫療保障方案
          </h4>
          <img
            src="../assets/images/policy-img1.png"
            alt=""
            class="img-round"
          />
        </div>
        <div
          class="col-12 col-md-6 col-xxl-4 d-flex flex-column justify-content-between"
        >
          <h4 class="mb-0 inter-font-bold fs-24 lh-base px-16 pb-16">
            打造休閒天堂！<br />推廣寵物休閒與娛樂場所
          </h4>
          <img
            src="../assets/images/policy-img2.png"
            alt=""
            class="img-round"
          />
        </div>
        <div
          class="col-12 col-md-6 col-xxl-4 mt-64 d-flex flex-column justify-content-between"
        >
          <h4 class="mb-0 inter-font-bold fs-24 lh-base px-16 pb-16">
            推廣寵物飼養教育，讓愛更加專業
          </h4>
          <img
            src="../assets/images/policy-img3.png"
            alt=""
            class="img-round"
          />
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
.img-round {
  border-radius: 24px;
}
</style>
