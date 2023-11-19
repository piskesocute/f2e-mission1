<script setup>
import { ref } from 'vue';

const data = ref([
  {
    img: 'event-img2.png',
    rwdImg: 'eventrwd-img2.png',
    date: '2023/12/24',
    title: '掃街模式開啟！帶著你的貓耳，來和我一起走！',
    content:
      '街上氣氛真的很棒，從小孩到大人，甚至有些狗狗朋友都帶著貓耳來找我握手，真的太可愛了！',
  },
  {
    img: 'event-img3.png',
    rwdImg: 'eventrwd-img3.png',
    date: '2023/12/20',
    title: '收容所模特兒大比拼！',
    content:
      '今天的收容所不再是一片寂靜。為了讓更多人認識到這裡的毛孩子，我們舉辦了一場前所未有的「模特兒走秀」！',
  },
  {
    img: 'event-img4.png',
    rwdImg: 'eventrwd-img4.png',
    date: '2023/12/26',
    title: '參與台北寵物論壇，爭取貓咪友善環境',
    content:
      '炎炎夏日的周六，我走進了台北寵物論壇，帶著一副貓耳髮箍，決定要全力宣傳「貓咪至上」的理念！',
  },
]);
const getImgUrl = (item) =>
  new URL(`../assets/images/${item.img}`, import.meta.url).href;
const getRwdImgUrl = (item) =>
  new URL(`../assets/images/${item.rwdImg}`, import.meta.url).href;
</script>
<template>
  <section
    class="container py-64 d-flex flex-column justify-content-center align-items-center"
  >
    <div class="row mt-xxl-40 mb-40 mb-xxl-64">
      <SectionTitle>
        <template #enTitle>LATEST EVENTS</template>
        <template #zhTitle>最新活動</template>
      </SectionTitle>
    </div>
    <div class="row w-100 mb-xxl-40 g-24">
      <div class="col-12 col-xxl-6 ps-xxl-0 h-100">
        <img
          src="../assets/images/event-img1.png"
          alt=""
          class="event-img1"
        />
        <p class="mt-16 mb-8 fs-14 lh-base">2023/12/26</p>
        <h5 class="mb-8 fs-20 lh-base inter-font-bold">
          參與台北寵物論壇，爭取貓咪友善環境
        </h5>
        <p class="mb-0 fs-16 lh-base">
          炎炎夏日的周六，我走進了台北寵物論壇，帶著一副貓耳髮箍，決定要全力宣傳「貓咪至上」的理念！我相信，我們的都市中，每一隻貓咪都應該有自己的
          VIP 休憩空間。
        </p>
      </div>
      <div class="col-12 col-xxl-6 pe-xxl-0">
        <div class="d-flex flex-column gap-24">
          <div
            class="d-flex"
            v-for="item in data"
            :key="item.date"
          >
            <img
              :src="getImgUrl(item)"
              alt=""
              class="img-fluid me-16 d-xxl-block d-none"
            />
            <img
              :src="getRwdImgUrl(item)"
              alt=""
              class="img-fluid me-16 d-block d-xxl-none"
            />
            <div class="w-100">
              <p class="mb-8 fs-14 lh-base">{{ item.date }}</p>
              <h5 class="mb-8 fs-16 lh-base inter-font-bold">
                {{ item.title }}
              </h5>

              <p class="mb-0 fs-14 fs-xxl-16 lh-base multiline-ellipsis">
                {{ item.content }}
              </p>
            </div>
          </div>
          <div>
            <button
              type="button"
              class="py-16 px-24 d-inline-block btn btn-btn-gray text-text-primary rounded-5 d-flex justify-content-center align-items-center gap-8 inter-font-semibold fs-16 lh-sm"
            >
              查看更多
              <img
                width="30"
                height="30"
                src="../assets/icons/arrow-right.svg"
                alt=""
              />
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<style lang="scss" scoped>
@import 'bootstrap-icons/font/bootstrap-icons.css';

.event-img1 {
  max-width: 100%;
  height: 100%;
  object-fit: cover;
  @include xxl {
    width: 100%;
  }
}
.multiline-ellipsis {
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-line-clamp: 2;
  overflow: hidden;
}
</style>
