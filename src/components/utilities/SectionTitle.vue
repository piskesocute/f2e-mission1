<script setup></script>
<template>
  <div class="d-flex flex-column text-center">
    <div>
      <h6
        class="d-inline-block rounded-2 inter-font-bold bg-text-primary py-8 px-12 text-white lh-base mb-0 fs-16"
      >
        <slot name="enTitle"></slot>
      </h6>
    </div>
    <p class="d-inline-block mb-0 my-class mantou-font fs-52 fs-lg-64 lh-base">
      <slot name="zhTitle"></slot>
    </p>
  </div>
</template>
<style lang="scss" scoped></style>
