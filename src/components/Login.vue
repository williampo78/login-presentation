<template>
  <div class="md:flex justify-center">
    <div class="md:flex w-full max-w-[1200px]">
      <div class="hidden md:block flex-shrink-0 mr-[-15%]">
        <img src="@/assets/images/pic-pharmacy.png" alt="" />
      </div>
      <form
        class="px-[15px] pt-[30px] pb-[25px] bg-white md:flex-1  md:max-w-[620px] md:border border-silver md:rounded md:py-[60px] md:pr-28 md:pl-[50px]"
        action=""
      >
        <h3 class="text-xl mb-5 font-bold ">會員登入</h3>

        <div class="flex flex-col my-2 gap-y-2 md:flex-row md:justify-end">
          <label class="text-left md:mr-4 md:text-right md:w-[60px]" for="">手機</label>
          <input class="border rounded h-10 flex-1" type="text" />
        </div>
        <div class="flex flex-col my-2 gap-y-2 md:flex-row md:justify-end">
          <label class="text-left md:mr-4 md:text-right md:w-[60px]" for="">密碼</label>
          <input class="border rounded h-10 flex-1" type="text" />
        </div>
        <div class="flex flex-col my-2 gap-y-2 md:flex-row md:justify-end">
          <label class="text-left md:mr-4 md:text-right md:w-[60px]" for="">驗證碼</label>
          <input class="border rounded h-10 flex-1" type="text" />
        </div>
        <div class="flex">
          <img src="@/assets/images/captcha.png" alt="" />
          <img src="@/assets/images/btn-refresh.svg" alt="" />
        </div>
        <button
          class="bg-green text-white h-10 rounded w-full mt-[30px] mb-[15px]"
        >
          登入
        </button>
        <div class="flex justify-center">
          <a
            class="text-green font-bold pr-[10px] mr-[10px] border-r border-green"
            href=""
            >忘記密碼</a
          >
          <p>我還不是會員，</p>
          <a class="flex text-green font-bold" href=""
            >加入會員
            <img src="@/assets/images/btn-next.svg" alt="" />
          </a>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Login",
};
</script>

<style scoped lang="scss"></style>
