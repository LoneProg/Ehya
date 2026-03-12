<script setup>
  import NavBar from './components/NavBar.vue'
</script>

<template>
  <div>
    <div className="bg-[#00b8d9] h-200">
      <NavBar />
      <div class="flex justify-between mt-28">
        <div class="ml-24">
          <h2 class="font-['DM-Sans'] text-[64px] font-bold text-white">We help you <br> grow your business faster</h2>
          <div>
            <img src="./assets/curve.png" alt="Curve" class="w-1/5">
          </div>
          <p class="font-['DM-Sans'] text-[16px] font-normal leading-6.5 text-left text-white w-[60%]">Ehya is the instagram analytics platform teams use to stay focused on the goals, track engagement or report your business</p>
          <div class="flex gap-4 items-center demo">
            <button class="font-['DM-Sans'] text-[12px] font-medium w-49.25 leading-5 text-center border-none cursor-pointer py-4 px-[1.9rem] rounded-sm">See how it works</button>
            <p class="font-['DM-Sans'] text-[16px] font-normal leading-6.5 text-left text-white w-[60%]">Get a free demo &#8594;</p>
          </div>
        </div>
        <div>
          <img src="./assets/graph.png" alt="Graph" class="w-full">
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .demo button {
    color: rgba(0, 168, 219, 1);
    background: white;
  }
  .demo button:hover{
    color: white;
    background: linear-gradient(278.21deg, #005490 1.66%, #328bcb 96.78%);
  }
</style>