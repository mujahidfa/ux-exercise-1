<template>
  <div class="bg-top bg-blue-500 h-56 background">
    <div class="p-6 min-h-screen tracking-widest">
      <div class="">
        <div class="flex flex-row justify-between">
          <img class="h-5 w-5" src="~/assets/left-arrow.svg" />
          <img src="~/assets/menu.svg" />
        </div>
        <h1 class="text-white font-bold text-center mb-4 mt-8">Payment</h1>
        <div
          class="flex flex-col p-4 h-48 my-2 bg-red-400 rounded-lg content-around shadow-xl text-white font-semibold"
        >
          <div class="">
            <img src="~/assets/mcard.svg" />
          </div>
          <div class="flex flex-row mt-3 items-center">
            <div class="text-3xl dots">•••• •••• ••••</div>
            <div class="ml-4 mt-1 numbers">1234</div>
          </div>
          <div class="flex flex-row justify-between mt-8">
            <div class="">Mujahid Fakhrul Anuar</div>
            <div class="">01/23</div>
          </div>
        </div>
      </div>

      <div class="margin">
        <h1 class="font-bold text-gray-800">Card number</h1>
        <div class="py-4 px-5 bg-white rounded-lg shadow-lg text-gray-500">
          0000 0000 0000 0000
        </div>
      </div>

      <div class="margin">
        <div class="flex flex-row">
          <div class="flex-grow ">
            <h1 class="font-bold text-gray-800">Expiry date</h1>
            <div
              class="py-4 px-5 mr-4 bg-white rounded-lg shadow-lg text-gray-500"
            >
              MM/YY
            </div>
          </div>

          <div>
            <h1 class="font-bold text-gray-800">Secure code</h1>
            <div class="py-4 px-5 bg-white rounded-lg shadow-lg text-gray-500">
              CVV
            </div>
          </div>
        </div>
        <!-- <div class="flex flex-row justify-between">
        <h1 class="font-bold text-gray-800">Expiry date</h1>
        <h1 class="font-bold text-gray-800">Secure code</h1>
      </div>
      <div class="flex flex-row text-gray-500">
        <div class="py-4 px-5 mr-4 flex-grow bg-white rounded-lg shadow-lg ">
          MM/YY
        </div>
        <div class="py-4 px-5 flex-grow bg-white rounded-lg shadow-lg ">
          CVV
        </div>
      </div> -->
      </div>

      <div class="margin">
        <h1 class="font-bold text-gray-800">Name on card</h1>
        <div class="py-4 px-5 bg-white rounded-lg shadow-lg text-gray-500">
          Mujahid Fakhrul Anuar
        </div>
      </div>

      <div
        class="margin py-4 px-5 bg-red-400 rounded-lg shadow-lg text-white font-bold text-center"
      >
        Pay
      </div>
      <hr class="mt-8 border-gray-400 border-2 rounded mx-20 mt-12" />
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style>
.margin {
  @apply my-8;
}
.dots {
  word-spacing: 10px;
}
.numbers {
  letter-spacing: 5px;
}
</style>
