<template>
  <div class="bg-green md:flex md:justify-center">
    <div class="px-2 py-1 flex items-center justify-between md:max-w-[1200px]">
      <div class="flex items-center">
        <img
          class="mr-3 md:hidden"
          src="@/assets/images/hamburger.svg"
          alt=""
        />
        <picture class="w-[180px]">
          <source
            srcset="@/assets/images/logo@2x.png"
            media="(min-width: 991px)"
          />
          <img src="@/assets/images/logo.svg" />
        </picture>
      </div>

      <div class="hidden md:flex bg-white h-8 justify-between">
        <input type="text" />
        <span class="text-green flex items-center">
          <img src="@/assets/images/input-search.svg" alt="" />
          搜尋
        </span>
      </div>
      <div class="flex items-center">
        <img src="@/assets/images/search.svg" alt="" />
        <img src="@/assets/images/user.svg" alt="" />
        <img src="@/assets/images/cart.svg" alt="" />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Header",
};
</script>

<style scoped lang="scss"></style>
