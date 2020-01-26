<template>
  <div class="h-56 bg-blue-500 bg-top background">
    <div class="min-h-screen p-6 tracking-widest">
      <div class="">
        <div class="flex flex-row justify-between">
          <img class="w-5 h-5" src="~/assets/left-arrow.svg" />
          <img src="~/assets/menu.svg" />
        </div>
        <h1 class="mt-8 mb-4 font-bold text-center text-white">Payment</h1>
        <div
          class="flex flex-col content-around h-48 p-4 my-2 font-semibold text-white bg-red-400 rounded-lg shadow-xl"
        >
          <div class="">
            <img src="~/assets/mcard.svg" />
          </div>
          <div class="flex flex-row items-center mt-3">
            <div class="text-3xl dots">•••• •••• ••••</div>
            <div class="mt-1 ml-4 numbers">1234</div>
          </div>
          <div class="flex flex-row justify-between mt-8">
            <div class="">Mujahid Fakhrul Anuar</div>
            <div class="">01/23</div>
          </div>
        </div>
      </div>

      <div class="margin">
        <h1 class="font-bold text-gray-800">Card number</h1>
        <div class="px-5 py-4 text-gray-500 bg-white rounded-lg shadow-lg">
          0000 0000 0000 0000
        </div>
      </div>

      <div class="margin">
        <div class="flex flex-row">
          <div class="flex-grow ">
            <h1 class="font-bold text-gray-800">Expiry date</h1>
            <div
              class="px-5 py-4 mr-4 text-gray-500 bg-white rounded-lg shadow-lg"
            >
              MM/YY
            </div>
          </div>

          <div>
            <h1 class="font-bold text-gray-800">Secure code</h1>
            <div class="px-5 py-4 text-gray-500 bg-white rounded-lg shadow-lg">
              CVV
            </div>
          </div>
        </div>
        <!-- <div class="flex flex-row justify-between">
        <h1 class="font-bold text-gray-800">Expiry date</h1>
        <h1 class="font-bold text-gray-800">Secure code</h1>
      </div>
      <div class="flex flex-row text-gray-500">
        <div class="flex-grow px-5 py-4 mr-4 bg-white rounded-lg shadow-lg ">
          MM/YY
        </div>
        <div class="flex-grow px-5 py-4 bg-white rounded-lg shadow-lg ">
          CVV
        </div>
      </div> -->
      </div>

      <div class="margin">
        <h1 class="font-bold text-gray-800">Name on card</h1>
        <div class="px-5 py-4 text-gray-500 bg-white rounded-lg shadow-lg">
          Mujahid Fakhrul Anuar
        </div>
      </div>

      <div
        class="px-5 py-4 font-bold text-center text-white bg-red-400 rounded-lg shadow-lg margin"
      >
        Pay
      </div>
      <hr class="mx-20 mt-8 mt-12 border-2 border-gray-400 rounded" />
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
