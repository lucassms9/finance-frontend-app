<template>
  <div class="container mx-auto shadow-md px-2">
    <h2 class="my-4 text-2xl font-bold leading-none tracking-tight ">Trasactions</h2>
    <Filters />
    <table class="table-fixed w-full text-sm text-left">
      <thead>
        <tr class="border-b-2 border-t-2 border-gray-200 ">
          <th scope="col" class="py-3 text-gray-400 w-2/4">Reference</th>
          <th scope="col" class=" py-3 text-gray-400">Category</th>
          <th scope="col" class=" py-3 text-gray-400">Date</th>
          <th scope="col" class="text-right py-3 text-gray-400">Amount</th>
        </tr>
      </thead>
      <tbody>
        <tr class="border-b-2 border-gray-100">
          <td class="whitespace-nowrap py-3">The Sliding Mr. )</td>
          <td class="whitespace-nowrap py-3 flex">
            <div class="p-3 text-center bg-orange-300 rounded-md">Vendor</div>
          </td>
          <td class="whitespace-nowrap  py-3">1961/20/22</td>
          <td class="whitespace-nowrap flex justify-end  py-3">
            <div class="flex gap-2">
              <div class="">540.00</div>
              <div class="text-gray-400">GBP</div>
            </div>
          </td>
        </tr>

        <tr class="border-b-2 border-gray-100">
          <td class="whitespace-nowrap py-3">The Sliding Mr. )</td>
          <td class="whitespace-nowrap py-3 flex">
            <div class="p-3 text-center bg-orange-300 rounded-md">Vendor</div>
          </td>
          <td class="whitespace-nowrap  py-3">1961/20/22</td>
          <td class="whitespace-nowrap flex justify-end  py-3">
            <div class="flex gap-2">
              <div class="">540.00</div>
              <div class="text-gray-400">GBP</div>
            </div>
          </td>
        </tr>

      </tbody>
    </table>
  </div>
</template>