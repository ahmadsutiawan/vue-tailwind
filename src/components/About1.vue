<template lang="">
  <div class="pt-32">
    <h1 class="text-3xl font-bold text-gray-300 text-center">My Abilities</h1>
    <h4 class="text-3xl font-light text-gray-300 mb-10 text-center">
      I can provide to you in a professional manner
    </h4>

    <!-- grid -->

    <div class="flex gap-10">
      <div class="flex flex-col gap-10">
        <div class="grid grid-cols-3 gap-10">
          <!-- card -->
          <div class="border-2 border-gray-800 rounded-2xl p-5 bg-slate-950 group">
            <img
              src="/assets/delivery-man.png"
              alt=""
              class="h-60 flex mx-auto opacity-35 transform transition-transform duration-200 hover:rotate-6"
            />
            <h1 class="text-xl font-bold text-gray-300 mb-5 transition-transform duration-200 group-hover:translate-x-2">About Me</h1>
            <p class="text-gray-500 text-center transition-transform duration-200 group-hover:translate-x-2">
              lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem
              ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem
              ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum
            </p>
          </div>

          <div class="border-2 border-gray-800 rounded-2xl p-5 bg-slate-950 transition-colors duration-300 hover:bg-gray-800">
            <img
              src="/assets/competence.png "
              alt=""
              class="h-60 flex mx-auto opacity-35"
            />
            <h1 class="text-xl font-bold text-gray-300 mb-5">Skill Set</h1>
            <p class="text-gray-500 text-center">
              lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem
              ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem
              ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum
            </p>
          </div>

          <div class="border-2 border-gray-800 rounded-2xl p-5 bg-slate-950 overflow-hidden hover:border-gray-300 hover:shadow-[0_0_20px_rgba(255,255,255,0.8)] transition-all duration-300">
            <img
              src="/assets/reputation.png"
              alt=""
              class="h-60 flex mx-auto opacity-35 transform transition-transform duration-200 hover:scale-110"
            />
            <h1 class="text-xl font-bold text-gray-300 mb-5 ">Experience</h1>
            <p class="text-gray-500 text-center">
              lorem ipsum lorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem
              ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsumlorem
              ipsumlorem ipsumlorem ipsumlorem ipsumlorem ipsum
            </p>
          </div>
        </div>
      </div>
    </div>
    <!-- grid bawah -->
    
  </div>
</template>
<script>
export default {
  name: "About1",
};
</script>

<style scoped>
.perspective {
  perspective: 1000px;
}
.rotate-x-12 {
  transform: rotateX(12deg);
}
.rotate-y-6 {
  transform: rotateY(6deg);
}
</style>
