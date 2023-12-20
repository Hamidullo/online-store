<template>
    <div>
        <h2 class="text-3xl font-bold mb-8">Мy profile</h2>
    </div>
    <div
    class="relative bg-white border border-slate-100 rounded-3xl p-8 cursor-pointer transition hover:-translate-y-2 hover:shadow-xl">

    <img src="../assets/profile.svg" />

    <div class="flex justify-between mt-5">
      <div class="flex flex-col">
        <span class="text-slate-400">Name:</span>
        <b></b>
      </div>
    </div>

    <div class="flex justify-between mt-5">
      <div class="flex flex-col">
        <span class="text-slate-400">Email:</span>
        <b></b>
      </div>
    </div>
    <div class="flex justify-between mt-5">
      <div class="flex flex-col">
        <span class="text-slate-400">Address:</span>
        <b></b>
      </div>
    </div>
  </div>
</template>

<script>
    export default {
        
    }
</script>
