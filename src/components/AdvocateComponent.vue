<script setup>
import SectionTitle from './utilities/SectionTitle.vue';
</script>
<template>
  <div class="container-fluid bg-primary-theme overflow-hidden d-flex py-10">
    <span class="text-white mantou-font fs-40 fs-lg-64 lh-1 marquee-content">
      為喵星人，護台灣！ 從喵的眼中，看見台灣 喵的未來，人的希望</span
    >
    <span class="text-white mantou-font fs-40 fs-lg-64 lh-1 marquee-content2">
      為喵星人，護台灣！ 從喵的眼中，看見台灣 喵的未來，人的希望</span
    >
  </div>
  <div class="bg-bg-color-secondary-theme">
    <div
      class="container py-64 d-flex justify-content-center align-items-center"
    >
      <div class="row w-100 my-lg-40 bg-white rounded-24">
        <div class="col-12 col-lg-6 ps-lg-0">
          <div class="py-40 py-lg-64 px-24 px-lg-40">
            <SectionTitle class="mb-32">
              <template #enTitle>ADVOCATE</template>
              <template #zhTitle>候選人主張</template>
            </SectionTitle>
            <h3
              class="inter-font-bold fw-bold fs-24 fs-lg-28 lh-base text-start text-text-primary mb-32"
            >
              我堅信 ! 藉由推動更完善的<strong class="text-primary-theme"
                >貓咪福利</strong
              >和相關政策，更是間接地投資於<strong class="text-primary-theme"
                >台灣的未來</strong
              >。
            </h3>
            <p
              class="mb-0 text-text-primary text-start inter-font-regular fs-16 fs-lg-18 fw-normal lh-base"
            >
              畢竟，民眾的身心健康與工作熱情是推動經濟的核心動力。透過完善的貓咪福利政策，為台灣的
              GDP 經濟帶來巨大效益。<br />
              因此，我期望能在立法院內推進這些政策，確保每一隻貓咪都能得到他們應有的照顧，同時也為台灣的經濟發展助一臂之力。讓我們一同護航台灣的幸福經濟，從照顧每一隻貓咪開始。
            </p>
          </div>
        </div>
        <div class="col-12 col-lg-6 p-0 ps-lg-12 pe-lg-0">
          <div class="d-flex justify-content-center align-items-center h-100">
            <img
              src="@/assets/images/advocate-img.png"
              alt=""
              class="advocate-img"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.marquee-content {
  display: inline-block;
  white-space: nowrap;
  animation: marquee 10s linear infinite;
}
.marquee-content2 {
  display: inline-block;
  white-space: nowrap;
  animation: marquee2 10s linear infinite;
}
.advocate-img {
  min-width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 0 24px 24px 0;
  @include lg {
    border-radius: 0 0 24px 24px;
  }
}

@keyframes marquee {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-100%);
  }
}
@keyframes marquee2 {
  0% {
    transform: translateX(0);
  }
  100% {
    transform: translateX(-100%);
  }
}
</style>
