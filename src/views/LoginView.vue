<script lang="ts" setup>
</script>
<template>
<form class="w-full px-8">
    <h2 class="text-base/7 font-semibold text-gray-900">Login</h2>
    <p class="mt-1 text-sm/6 text-gray-600">Use your Email and Password to login.</p>

    <div class="mt-10 grid grid-cols-1 gap-x-6 gap-y-8">
        <div class="sm:col-span-3">
          <label for="first-name" class="block text-sm font-medium text-gray-900">Email ID</label>
          <div class="mt-2">
            <input type="text" name="first-name" id="first-name" autocomplete="given-name" class="block w-full rounded-md bg-white px-3 py-1.5 text-base text-gray-900 outline-1 -outline-offset-1 outline-gray-300 placeholder:text-gray-400 focus:outline-2 focus:-outline-offset-2 focus:outline-indigo-600" />
          </div>
        </div>

        <div class="sm:col-span-3">
          <label for="last-name" class="block text-sm font-medium text-gray-900">Password</label>
          <div class="mt-2">
            <input type="text" name="last-name" id="last-name" autocomplete="family-name" class="block w-full rounded-md bg-white px-3 py-1.5 text-base text-gray-900 outline-1 -outline-offset-1 outline-gray-300 placeholder:text-gray-400 focus:outline-2 focus:-outline-offset-2 focus:outline-indigo-600" />
          </div>
        </div> 
    </div>
    <div class="mt-6 flex items-center justify-start gap-x-6">
          <button type="submit" class="rounded-md bg-indigo-600 px-3 py-2 text-sm font-semibold text-white shadow-xs hover:bg-indigo-500 focus-visible:outline-2 focus-visible:outline-offset-2 focus-visible:outline-indigo-600">Save</button>
    </div>
</form>
</template>
 
