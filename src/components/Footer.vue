<template>
  <div class="bg-green">
    <div class="flex justify-center">
      <div
        class="flex justify-center py-[21px] w-full md:max-w-[1200px] md:justify-between md:py-[30px]"
      >
        <div class="hidden md:flex flex-1 text-white text-[13px]">
          <dl class="flex-1 text-left">
            <dt class="text-[18px] font-bold">關於我們</dt>
            <dd class="my-1">認識我們</dd>
            <dt class="my-1">門市據點</dt>
            <dd class="my-1">描述二有很多內容說明</dd>
          </dl>
          <dl class="flex-1 text-left">
            <dt class="text-[18px] font-bold">購物流程</dt>
            <dd class="my-1">運費及配送</dd>
            <dt class="my-1">付款方式</dt>
            <dd class="my-1">免責聲明</dd>
          </dl>
          <dl class="flex-1 text-left">
            <dt class="text-[18px] font-bold">會員專區</dt>
            <dd class="my-1">紅利點數</dd>
            <dt class="my-1">會員服務條款</dt>
            <dd class="my-1">隱私權政策</dd>
          </dl>
          <dl class="flex-1 text-left">
            <dt class="text-[18px] font-bold">客服中心</dt>
            <dd>常見問題Q&A</dd>
            <dt class="my-1">退換貨須知</dt>
            <dd class="my-1">與我們聯繫</dd>
            <dd class="my-1">防詐騙宣導</dd>
          </dl>
        </div>

        <div class="flex flex-col">
          <ul class="flex text-white justify-center md:hidden">
            <li class="px-3 border-r border-white">關於我們</li>
            <li class="px-3 border-r border-white">購物流程</li>
            <li class="px-3">客服中心</li>
          </ul>
          <div class="flex justify-center my-[15px] md:order-2">
            <div class="hidden md:block pr-[10px] border-r border-white">
              <img src="@/assets/images/logo-qrcode.9a55fd8.png" alt="" />
            </div>
            <img class="mx-[10px]" src="@/assets/images/icon-fb.svg" alt="" />
            <img class="mx-[10px]" src="@/assets/images/icon-ig.svg" alt="" />
            <img
              class="mx-[10px]"
              src="@/assets/images/icon-youtube.svg"
              alt=""
            />
            <img class="mx-[10px]" src="@/assets/images/icon-line.svg" alt="" />
          </div>
          <div class="text-white md:order-1 md:text-left">
            <p>健康力科技股份有限公司</p>
            <p>Dr.Advice Technology Corporation Limited</p>
          </div>
          <div class="mt-[15px] flex justify-center md:hidden">
            <img class="mx-[10px]" src="@/assets/images/app-store.png" alt="" />
            <img
              class="mx-[10px]"
              src="@/assets/images/google-play.png"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Footer",
}
</script>

<style scoped lang="scss"></style>
