<template>
  <section>
    <div class="testimonial pt-[88px]">
      <div class="container">
        <div class="flex justify-between items-center text-white mb-20">
          <h1 class="font-bold text-[40px] text-start">Testimonials</h1>
          <div class="flex gap-3">
            <button
              class="size-12 rounded-lg p-2 flex justify-center items-center border border-white/30"
              type="button"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-8"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M15.75 19.5 8.25 12l7.5-7.5"
                />
              </svg>
            </button>
            <button
              class="size-12 rounded-lg p-2 flex justify-center items-center border border-white/30"
              type="button"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-8"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="m8.25 4.5 7.5 7.5-7.5 7.5"
                />
              </svg>
            </button>
          </div>
        </div>
        <div class="grid grid-cols-3 gap-8">
          <div class="bg-white rounded-[20px] pt-[56px] p-8 relative">
            <div class="absolute left-8 -top-[20%] rounded-full size-20">
              <img
                class="w-full object-cover"
                src="../assets/sebastian.png"
                alt="sebastian"
              />
            </div>
            <div class="flex items-start justify-between">
              <div>
                <h3 class="font-bold">Sebastian</h3>
                <span class="text-xs">Graphic design</span>
              </div>
              <div class="flex gap-[2px] items-center mt-1">
                <img
                  v-for="i in Number(5)"
                  class="size-[18px]"
                  src="../assets/star.png"
                  alt="star"
                />
              </div>
            </div>
            <p class="leading-relaxed mt-6">
              Lorem Ipsum is simply dummy text<br />
              of the printing and typesetting <br />
              industry. Lorem Ipsum has been the industry's standard dummy text.
            </p>
          </div>
          <div class="bg-white rounded-[20px] pt-[56px] p-8 relative">
            <div class="absolute left-8 -top-[20%] rounded-full size-20">
              <img
                class="w-full object-cover"
                src="../assets/evangeline.png"
                alt="evangeline"
              />
            </div>
            <div class="flex items-start justify-between">
              <div>
                <h3 class="font-bold">Evangeline</h3>
                <span class="text-xs">Model</span>
              </div>
              <div class="flex gap-[2px] items-center mt-1">
                <img
                  v-for="i in Number(5)"
                  class="size-[18px]"
                  src="../assets/star.png"
                  alt="star"
                />
              </div>
            </div>
            <p class="leading-relaxed mt-6">
              Lorem Ipsum is simply dummy text<br />
              of the printing and typesetting <br />
              industry. Lorem Ipsum has been the industry's standard dummy text.
            </p>
          </div>
          <div class="bg-white rounded-[20px] pt-[56px] p-8 relative">
            <div class="absolute left-8 -top-[20%] rounded-full size-20">
              <img
                class="w-full object-cover"
                src="../assets/alexander.png"
                alt="alexander"
              />
            </div>
            <div class="flex items-start justify-between">
              <div>
                <h3 class="font-bold">Alexander</h3>
                <span class="text-xs">Software engineer</span>
              </div>
              <div class="flex gap-[2px] items-center mt-1">
                <img
                  v-for="i in Number(5)"
                  class="size-[18px]"
                  src="../assets/star.png"
                  alt="star"
                />
              </div>
            </div>
            <p class="leading-relaxed mt-6">
              Lorem Ipsum is simply dummy text<br />
              of the printing and typesetting <br />
              industry. Lorem Ipsum has been the industry's standard dummy text.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.testimonial {
  min-height: 563px;
  background-image: url("../assets/testimonial.png");
}
.text-shadow {
  text-shadow: 1px 1px 2px black;
}
</style>
