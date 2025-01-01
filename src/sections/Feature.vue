<template>
  <section class="py-20 bg-[#F7F7F7]">
    <div class="container">
      <div class="flex justify-between items-center">
        <h1 class="font-bold text-[40px] text-start">Feature News</h1>
        <div class="flex gap-3">
          <button
            class="size-12 rounded-lg p-2 flex justify-center items-center border border-[#D8D8D8]"
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
            class="size-12 rounded-lg p-2 flex justify-center items-center border border-[#D8D8D8]"
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
      <div class="mt-[50px] grid grid-cols-3 gap-8">
        <div class="shadow-lg rounded-[32px] overflow-hidden">
          <img
            src="../assets/1.png"
            alt="Delicious restaurant at Hanalei Bay"
          />
          <div class="p-8 bg-white">
            <div class="flex gap-2 mb-4 text-[#1A1A1A]">
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
                  d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5"
                />
              </svg>
              <span> February 20, 2024 </span>
            </div>
            <h3 class="font-bold text-2xl mb-6">
              Delicious restaurant at Hanalei Bay
            </h3>
            <p class="leading-relaxed">
              Lorem Ipsum is simply dummy text <br />
              of the printing and typeset industry.<br />
              Lorem Ipsum has been lorem ...
            </p>
            <div class="mt-6 flex items-center gap-3">
              <button
                class="size-[26px] rounded-full border border-[#008395] flex items-center justify-center"
                type="button"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  class="size-[20px] fill-[#008395]"
                >
                  <path
                    fill-rule="evenodd"
                    d="M8.22 5.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.75.75 0 0 1-1.06-1.06L11.94 10 8.22 6.28a.75.75 0 0 1 0-1.06Z"
                    clip-rule="evenodd"
                  />
                </svg>
              </button>
              <span class="font-bold text-[#008395]"> See more </span>
            </div>
          </div>
        </div>
        <div class="shadow-lg rounded-[32px] overflow-hidden">
          <img
            src="../assets/2.png"
            alt="Top 10 most beautiful check-in spots in Ph ..."
          />
          <div class="p-8 bg-white">
            <div class="flex gap-2 mb-4 text-[#1A1A1A]">
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
                  d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5"
                />
              </svg>
              <span> February 20, 2024 </span>
            </div>
            <h3 class="font-bold text-2xl mb-6">
              Top 10 most beautiful check-in spots in Ph ...
            </h3>
            <p class="leading-relaxed">
              Lorem Ipsum is simply dummy text <br />
              of the printing and typeset industry.<br />
              Lorem Ipsum has been lorem ...
            </p>
            <div class="mt-6 flex items-center gap-3">
              <button
                class="size-[26px] rounded-full border border-[#008395] flex items-center justify-center"
                type="button"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  class="size-[20px] fill-[#008395]"
                >
                  <path
                    fill-rule="evenodd"
                    d="M8.22 5.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.75.75 0 0 1-1.06-1.06L11.94 10 8.22 6.28a.75.75 0 0 1 0-1.06Z"
                    clip-rule="evenodd"
                  />
                </svg>
              </button>
              <span class="font-bold text-[#008395]"> See more </span>
            </div>
          </div>
        </div>
        <div class="shadow-lg rounded-[32px] overflow-hidden">
          <img
            src="../assets/3.png"
            alt="Top 5 newest services at Navagio Beach"
          />
          <div class="p-8 bg-white">
            <div class="flex gap-2 mb-4 text-[#1A1A1A]">
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
                  d="M6.75 3v2.25M17.25 3v2.25M3 18.75V7.5a2.25 2.25 0 0 1 2.25-2.25h13.5A2.25 2.25 0 0 1 21 7.5v11.25m-18 0A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75m-18 0v-7.5A2.25 2.25 0 0 1 5.25 9h13.5A2.25 2.25 0 0 1 21 11.25v7.5"
                />
              </svg>
              <span> February 20, 2024 </span>
            </div>
            <h3 class="font-bold text-2xl mb-6">
              Top 5 newest services at Navagio Beach
            </h3>
            <p class="leading-relaxed">
              Lorem Ipsum is simply dummy text <br />
              of the printing and typeset industry.<br />
              Lorem Ipsum has been lorem ...
            </p>
            <div class="mt-6 flex items-center gap-3">
              <button
                class="size-[26px] rounded-full border border-[#008395] flex items-center justify-center"
                type="button"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  class="size-[20px] fill-[#008395]"
                >
                  <path
                    fill-rule="evenodd"
                    d="M8.22 5.22a.75.75 0 0 1 1.06 0l4.25 4.25a.75.75 0 0 1 0 1.06l-4.25 4.25a.75.75 0 0 1-1.06-1.06L11.94 10 8.22 6.28a.75.75 0 0 1 0-1.06Z"
                    clip-rule="evenodd"
                  />
                </svg>
              </button>
              <span class="font-bold text-[#008395]"> See more </span>
            </div>
          </div>
        </div>
      </div>
      <div class="mt-[50px] flex justify-center items-center gap-2">
        <div class="size-[10px] bg-[#333333] rounded-full" />
        <div class="size-[10px] bg-[#1A1A1A]/20 rounded-full" />
        <div class="size-[10px] bg-[#1A1A1A]/20 rounded-full" />
      </div>
    </div>
  </section>
</template>
