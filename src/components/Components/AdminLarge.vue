<template>
  <section class="my-4 border-t-2 py-8 px-4">
    <div class="flex flex-wrap -mx-4">
      <div class="w-full lg:w-1/4 px-4 mb-4 lg:mb-0">
        <div class="h-full border rounded shadow">
          <div class="flex items-center justify-between py-3 px-4 border-b">
            <h3 class="text-lg font-heading">Income</h3>
            <span
              class="py-1 px-3 text-sm text-white font-semibold bg-green-500 rounded-full"
              >Monthly</span
            >
          </div>
          <div class="flex flex-col p-4">
            <h3 class="text-3xl mb-3 font-heading font-semibold">108,200</h3>
            <span>Total income</span><span class="text-green-500">82%</span>
          </div>
        </div>
      </div>
      <div class="w-full lg:w-1/4 px-4 mb-4 lg:mb-0">
        <div class="h-full border rounded shadow">
          <div class="flex items-center justify-between px-4 py-3 border-b">
            <h3 class="text-lg font-heading">Orders</h3>
            <span
              class="py-1 px-3 text-sm text-white font-semibold bg-green-500 rounded-full"
              >Monthly</span
            >
          </div>
          <div class="flex flex-col p-4">
            <h3 class="text-3xl mb-3 font-heading font-semibold">128,430</h3>
            <span>New orders</span><span class="text-green-500">32%</span>
          </div>
        </div>
      </div>
      <div class="w-full lg:w-1/4 px-4 mb-4 lg:mb-0">
        <div class="h-full border rounded shadow">
          <div class="flex items-center justify-between px-4 py-3 border-b">
            <h3 class="text-lg font-heading">Visits</h3>
            <span
              class="py-1 px-3 text-sm text-white font-semibold bg-green-500 rounded-full"
              >Monthly</span
            >
          </div>
          <div class="flex flex-col p-4">
            <h3 class="text-3xl mb-3 font-heading font-semibold">81,248</h3>
            <span>New visits</span><span class="text-green-500">24%</span>
          </div>
        </div>
      </div>
      <div class="w-full lg:w-1/4 px-4 mb-4 lg:mb-0">
        <div class="h-full border rounded shadow">
          <div class="flex items-center justify-between px-4 py-3 border-b">
            <h3 class="text-lg font-heading">Conversions</h3>
            <span
              class="py-1 px-3 text-sm text-white font-semibold bg-red-500 rounded-full"
              >Today</span
            >
          </div>
          <div class="flex flex-col p-4">
            <h3 class="text-3xl mb-3 font-heading font-semibold">7%</h3>
            <span>Purchased more than once</span
            ><span class="text-red-500">82%</span>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
