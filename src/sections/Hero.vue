<template>
  <section class="pb-44">
    <div class="bg relative">
      <div
        class="container bg-white p-10 rounded-[32px] absolute left-1/2 -translate-x-1/2 -bottom-[24%] shadow-lg"
      >
        <h1 class="text-[#008EC4] font-semibold text-[60px]">Good Morning!</h1>
        <p class="text-[32px]">
          Explore beautiful places in the world with Acenda
        </p>
        <div
          class="my-12 border border-[#D9D9D9] rounded-[72px] p-3 pl-[24px] divide-x divide-[#8C8C8C]/50 grid grid-cols-9"
        >
          <div class="col-span-2 flex items-center gap-3">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-8 stroke-[#8C8C8C]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Z"
              />
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M19.5 10.5c0 7.142-7.5 11.25-7.5 11.25S4.5 17.642 4.5 10.5a7.5 7.5 0 1 1 15 0Z"
              />
            </svg>
            <div>
              <h4 class="font-bold">Location</h4>
              <p class="text-[#8C8C8C]">Add destination</p>
            </div>
          </div>
          <div class="col-span-2 flex items-center gap-3 pl-3">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-8 stroke-[#8C8C8C]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5"
              />
            </svg>
            <div>
              <h4 class="font-bold">Check in</h4>
              <p class="text-[#8C8C8C]">Add dates</p>
            </div>
          </div>
          <div class="col-span-2 flex items-center gap-3 pl-3">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-8 stroke-[#8C8C8C]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5"
              />
            </svg>
            <div>
              <h4 class="font-bold">Check out</h4>
              <p class="text-[#8C8C8C]">Add dates</p>
            </div>
          </div>
          <div class="col-span-2 flex items-center gap-3 pl-3">
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="size-8 stroke-[#8C8C8C]"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M15 19.128a9.38 9.38 0 0 0 2.625.372 9.337 9.337 0 0 0 4.121-.952 4.125 4.125 0 0 0-7.533-2.493M15 19.128v-.003c0-1.113-.285-2.16-.786-3.07M15 19.128v.106A12.318 12.318 0 0 1 8.624 21c-2.331 0-4.512-.645-6.374-1.766l-.001-.109a6.375 6.375 0 0 1 11.964-3.07M12 6.375a3.375 3.375 0 1 1-6.75 0 3.375 3.375 0 0 1 6.75 0Zm8.25 2.25a2.625 2.625 0 1 1-5.25 0 2.625 2.625 0 0 1 5.25 0Z"
              />
            </svg>

            <div>
              <h4 class="font-bold">Guests</h4>
              <p class="text-[#8C8C8C]">Add guests</p>
            </div>
          </div>
          <div class="flex justify-end">
            <button
              type="button"
              class="col-span-1 bg-[#008EC4] flex justify-center items-center size-14 rounded-full text-white"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke-width="1.5"
                stroke="currentColor"
                class="size-6"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z"
                />
              </svg>
            </button>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style>
.bg {
  min-height: 736px;
  background-image: url("../assets/bg.png");
}
</style>
