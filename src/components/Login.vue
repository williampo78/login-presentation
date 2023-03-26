<template>
  <div class="min-h-[60vh] my-[40px]">
    <div class="md:flex md:justify-center">
      <div class="md:flex md:max-w-[1200px]">
        <img
          class="hidden md:block md:mr-[-200px]"
          src="@/assets/images/pic-pharmacy.png"
          alt=""
        />
        <form
          class="py-[60px] px-[15px] bg-white md:border md:border-silver md:w-[620px]"
          action=""
        >
          <h3 class="text-2xl font-bold mb-[20px]">會員登入</h3>
          <div
            class="flex flex-col my-3 md:flex-row md:items-center md:ml-[50px] md:mr-[120px]"
          >
            <label
              class="text-left md:w-[60px] md:mr-[15px] md:text-right"
              for=""
              >手機</label
            >
            <input class="border rounded h-[40px] flex-grow" type="text" />
          </div>
          <div
            class="flex flex-col my-4 md:flex-row md:items-center md:ml-[50px] md:mr-[120px]"
          >
            <label
              class="text-left md:w-[60px] md:mr-[15px] md:text-right"
              for=""
              >密碼</label
            >
            <input class="border rounded h-[40px] flex-grow" type="text" />
          </div>
          <div
            class="flex flex-col my-4 md:flex-row md:items-center md:ml-[50px] md:mr-[120px]"
          >
            <label
              class="text-left md:w-[60px] md:mr-[15px] md:text-right"
              for=""
              >驗證碼</label
            >
            <input class="border rounded h-[40px] flex-grow" type="text" />
          </div>
          <div
            class="flex my-3 md:flex-row md:items-center md:ml-[50px] md:mr-[120px]"
          >
            <label
              class="text-left md:w-[60px] md:mr-[15px] md:text-right"
              for=""
            ></label>
            <img
              class="max-w-[180px]"
              src="@/assets/images/captcha.png"
              alt=""
            />
            <button>
              <img class="ml-4" src="@/assets/images/btn-refresh.svg" alt="" />
            </button>
          </div>

          <button
            class="bg-green w-full h-[40px] rounded-md mt-8 md:max-w-[60%] text-white"
          >
            登入
          </button>

          <div class="flex my-4 justify-center">
            <a class="text-green pr-6 mr-6 border-black border-r" href=""
              >忘記密碼</a
            >
            <p>我還不是會員，</p>
            <a class="text-green flex" href=""
              >加入會員 <img src="@/assets/images/btn-next.svg" alt=""
            /></a>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: "Login",
}
</script>

<style scoped lang="scss"></style>
