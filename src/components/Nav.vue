<template>
  <div class="flex h-10 bg-light-green justify-center">
    <div class="flex w-[100%] max-w-[1200px]">
      <div
        class="hidden md:flex w-[200px] items-center bg-brand-gray text-white"
      >
        <img class="w-6 h-6" src="@/assets/images/hamburger.svg" alt="" />
        分類總覽
      </div>
      <ul class="flex items-center overflow-auto">
        <li class="w-[80px] flex-shrink-0">分類1</li>
        <li class="w-[80px] flex-shrink-0">分類2</li>
        <li class="w-[80px] flex-shrink-0">分類3</li>
        <li class="w-[80px] flex-shrink-0">分類4</li>
        <li class="w-[80px] flex-shrink-0">分類5</li>
        <li class="w-[80px] flex-shrink-0">分類6</li>
        <li class="w-[80px] flex-shrink-0">分類7</li>
        <li class="w-[80px] flex-shrink-0">分類8</li>
        <li class="w-[80px] flex-shrink-0">分類9</li>
        <li class="w-[80px] flex-shrink-0">分類10</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Nav",
}
</script>

<style scoped lang="scss"></style>
