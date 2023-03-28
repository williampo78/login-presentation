<template>
  <div class="bg-green md:flex md:justify-center">
    <div
      class="px-2 py-1 flex items-center justify-between md:w-[100%] md:max-w-[1200px]"
    >
      <div class="flex items-center">
        <div class="flex items-center">
          <img
            class="mr-3 md:hidden"
            src="@/assets/images/hamburger.svg"
            alt=""
          />
          <picture class="w-[180px] mr-5">
            <source
              srcset="@/assets/images/logo@2x.png"
              media="(min-width: 991px)"
            />
            <img src="@/assets/images/logo.svg" />
          </picture>
        </div>

        <div
          class="w-[580px] hidden md:flex bg-white h-8 px-1 justify-between rounded"
        >
          <input
            type="text"
            class="w-[90%] border-0 outline-none border-r-[1px]"
          />
          <span class="text-green flex items-center">
            <img src="@/assets/images/input-search.svg" alt="" />
            搜尋
          </span>
        </div>
      </div>
      <div>
        <div class="flex items-center md:hidden">
          <img src="@/assets/images/search.svg" alt="" />
          <img src="@/assets/images/user.svg" alt="" />
          <img src="@/assets/images/cart.svg" alt="" />
        </div>
        <div class="md:flex items-center hidden">
          <img src="@/assets/images/user-desktop.svg" alt="" />
          <a class="text-white border-r px-2 mr-2" href="">會員登入</a>
          <a href="" class="text-white mr-2">註冊</a>
          <img src="@/assets/images/cart-desktop.svg" alt="" />
          <a href="" class="text-white">購物車</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Header",
}
</script>

<style scoped lang="scss"></style>
