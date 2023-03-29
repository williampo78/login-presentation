<template>
  <div class="flex h-10 bg-light-green justify-center">
    <div class="flex w-[100%] max-w-[1200px]">
      <div
        class="hidden md:flex w-[200px] items-center bg-brand-gray text-white"
      >
        <img class="w-6 h-6" src="@/assets/images/hamburger.svg" alt="" />
        分類總覽
      </div>
      <ul class="flex gap-x-2  items-center overflow-auto">
        <li class="min-w-[80px] flex-shrink-0 " v-for="(item, index) in list" :key="index">
          {{ item }}
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Nav",
  data() {
    return {
      list: [
        "首頁",
        "健康力專區",
        "文字最多六字",
        "樂活美食",
        "養顏美容",
        "熱銷專區",
        "益生菌",
        "醫療器材",
        "視力保健",
      ],
    };
  },
};
</script>

<style scoped lang="scss"></style>
