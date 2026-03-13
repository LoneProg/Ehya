<script setup>
  import NavBar from './components/NavBar.vue'
</script>

<template>
  <div>
    <div className="bg-[#00b8d9] h-200">
      <!-- navbar -->
      <NavBar />
      <div class="flex justify-between mt-28">
        <!-- hero -->
        <div class="ml-24">
          <h2 class="font-['DM-Sans'] text-[64px] font-bold text-white">We help you <br> grow your business faster</h2>
          <div>
            <img src="./assets/curve.png" alt="Curve" class="w-1/5">
          </div>
          <p class="font-['DM-Sans'] text-[16px] font-normal leading-6.5 text-left text-white w-[60%]">Ehya is the instagram analytics platform teams use to stay focused on the goals, track engagement or report your business</p>
          <div class="flex gap-4 items-center">
            <button class="font-['DM-Sans'] text-[12px] font-medium w-49.25 leading-5 text-center border-none cursor-pointer py-4 px-[1.9rem] rounded-sm bg-white text-[rgba(0,168,219,1)]">See how it works</button>
            <p class="font-['DM-Sans'] text-[16px] font-normal leading-6.5 text-left text-white w-[60%] hover:text-white">Get a free demo &#8594;</p>
          </div>
        </div>
        <div>
          <img src="./assets/graph.png" alt="Graph" class="w-full">
        </div>
      </div>
      <div class="w-1/2 m-auto flex gap-20 items-center justify-center mt-40 mb-20">
        <!-- sponors -->
         <img src="./assets/slack.png" alt="slack" class="size-1/5">
         <img src="./assets/netflix.png" alt="netflix" class="size-1/5">
         <img src="./assets/google.png" alt="google" class="size-1/5">
         <img src="./assets/airbnb.png" alt="airbnb" class="size-1/5">
         <img src="./assets/uber.png" alt="uber" class="size-1/5">
      </div>
      <div class="flex px-20 justify-between items-center w-full">
        <div>  
          <div class="absolute w-[30%]">
            <img src="./assets/iPhone.png" alt="Iphone" class="w-full">
          </div>
          <div class="relative z-[-2] left-10">
            <img src="./assets/arrow.png" alt="Arrow" class="w-full">
          </div>
        </div>
        <div class="justify-between items-center w-[45%]">
          <h3 class="font-['DM-Sans'] font-bold text-4xl leading-14 tracking-[0.3px] text-[rgba(3,77,130,1)]">Measure Inpressions and Peach Post</h3>
          <p>Graphs displaying your reference for metrics like follower evolution, average engagement rate per post and reach and impressions to give you the insights.</p>
          <a href="#">Learn about graphs &#8594;</a>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
  .demo button:hover{
    color: white;
    background: linear-gradient(278.21deg, #005490 1.66%, #328bcb 96.78%);
  }
</style>