<template>
  <section class="my-4 border-t-2 py-12 px-4">
    <div class="flex flex-wrap -mx-4">
      <div class="lg:w-1/2 px-4 mb-4 lg:mb-0">
        <img
          class="rounded shadow-md"
          src="img/placeholders/pictures/paper.jpg"
          alt=""
        />
      </div>
      <div class="lg:w-1/2 px-4">
        <h2 class="text-4xl mb-4 font-heading">
          All Purpose Paper 80gsm - 500 sheets - 10 Reams
        </h2>
        <p class="mb-6 text-gray-500 leading-relaxed">
          Premium quality home and office paper for all printing and copying
          machines. It is a flexible paper capable of switching from one machine
          to another with great print results.
        </p>
        <div class="mb-6">
          <button
            class="inline-flex items-center justify-center h-8 w-8 mr-2 bg-gray-400 rounded-full"
          ></button
          ><button
            class="inline-flex items-center justify-center h-8 w-8 mr-2 bg-gray-300 rounded-full"
          ></button
          ><button
            class="inline-flex items-center justify-center h-8 w-8 mr-2 bg-gray-200 rounded-full"
          ></button>
        </div>
        <div class="flex mb-6">
          <span class="text-2xl">$10</span>
          <div class="flex flex-wrap ml-4">
            <div class="w-1/2">
              <input
                class="appearance-none block w-full py-2 px-4 leading-snug text-gray-700 bg-gray-200 focus:bg-white border border-gray-200 focus:border-gray-500 rounded md:rounded-r-none focus:outline-none"
                type="number"
                value="1"
              />
            </div>
            <div class="w-1/2">
              <button
                class="inline-block w-full py-3 px-4 leading-none text-white bg-indigo-500 hover:bg-indigo-600 rounded md:rounded-l-none"
              >
                Buy
              </button>
            </div>
          </div>
        </div>
        <div class="pt-4 border-t">
          <a class="text-blue-700 hover:underline" href="#">Add to favorites</a>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
