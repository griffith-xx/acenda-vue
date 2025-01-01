<template>
  <section>
    <div class="explore">
      <div class="container">
        <h1
          class="uppercase font-bold text-[104px] text-white pt-[110px] pb-[70px] text-shadow"
        >
          explore maldives
        </h1>

        <div class="border-t border-white pt-12 grid grid-cols-7">
          <div class="col-span-3">
            <p
              class="text-xl tracking-wide leading-relaxed text-white text-shadow"
            >
              Lorem Ipsum is simply dummy text of the<br />
              printing and typesetting industry. Lorem<br />
              Ipsum has been the industry's standard<br />
              dummy text ever since the 1500s.
            </p>

            <button
              type="button"
              class="bg-white text-black w-[168px] h-[48px] flex justify-center items-center gap-2 border border-[#D8D8D8] rounded-[40px] pl-6 pr-4 py-3 mt-[42px]"
            >
              <span class="font-bold"> See All </span>
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-5"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M13.5 4.5 21 12m0 0-7.5 7.5M21 12H3"
                />
              </svg>
            </button>
          </div>
          <div class="grid grid-cols-3 gap-5 col-span-4">
            <div class="w-full flex flex-col gap-5">
              <img
                class="w-full object-cover h-[240px] rounded-2xl"
                src="../assets/azure-haven-2.png"
                alt="azure-haven"
              />
              <h3 class="font-bold text-lg text-white">Azure Haven</h3>
            </div>
            <div class="w-full flex flex-col gap-5">
              <img
                class="w-full object-cover h-[240px] rounded-2xl"
                src="../assets/sanctuary-2.png"
                alt="sanctuary"
              />
              <h3 class="font-bold text-lg text-white">Serene Sanctuary</h3>
            </div>
            <div class="w-full flex flex-col gap-5">
              <img
                class="w-full object-cover h-[240px] rounded-2xl"
                src="../assets/vista.png"
                alt="vista"
              />
              <h3 class="font-bold text-lg text-white">Verdant Vista</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.explore {
  min-height: 720px;
  background-image: url("../assets/maldives.png");
}
.text-shadow {
  text-shadow: 1px 1px 2px black;
}
</style>
