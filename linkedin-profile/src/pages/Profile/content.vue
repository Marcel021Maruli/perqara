<template>
 
    <div class="w-11/12 md:w-7/12 mx-5">
      <div class="rounded-md overflow-hidden bg-white mt-2 md:mt-0 md:bt-0">
        <div class="flex items-center justify-center pt-2.5 px-4">
          <div class="rounded-full overflow-hidden w-12 mr-2">
            <img
              src="https://media-exp1.licdn.com/dms/image/C5603AQEbFYZ9oBEW6w/profile-displayphoto-shrink_100_100/0/1631902344577?e=1648080000&v=beta&t=VXE7c7VEt3_DJC7_3TX_I0J5UO12PmSA62_pId3k4BQ"
              alt=""
            />
          </div>
          <input
            class="w-full border border-gray-400 rounded-3xl px-6 py-2.5 transition-all cursor-pointer focus:outline-none hover:bg-gray-200 placeholder:text-sm placeholder:font-medium placeholder:text-gray-500"
            placeholder="Start a post"
            type="text"
          />
        </div>
        <ul class="w-full flex items-center justify-around text-gray-500 my-1">
          <li>
            <a
              class="flex items-center px-0.5 md:px-2 h-12 rounded-md overflow-hidden transition-colors hover:bg-gray-100"
              href="#"
            >
              <span class="mr-2.5 text-xl">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#70b5f9"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M19 4H5a3 3 0 00-3 3v10a3 3 0 003 3h14a3 3 0 003-3V7a3 3 0 00-3-3zm1 13a1 1 0 01-.29.71L16 14l-2 2-6-6-4 4V7a1 1 0 011-1h14a1 1 0 011 1zm-2-7a2 2 0 11-2-2 2 2 0 012 2z"
                  ></path>
                </svg>
              </span>
              <span class="text-sm font-medium">Photo</span>
            </a>
          </li>
          <li>
            <a
              class="flex items-center px-0.5 md:px-2 h-12 rounded-md overflow-hidden transition-colors hover:bg-gray-100"
              href="#"
            >
              <span class="mr-2.5 text-xl">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#7fc15e"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M19 4H5a3 3 0 00-3 3v10a3 3 0 003 3h14a3 3 0 003-3V7a3 3 0 00-3-3zm-9 12V8l6 4z"
                  ></path>
                </svg>
              </span>
              <span class="text-sm font-medium">Video</span>
            </a>
          </li>
          <li>
            <a
              class="flex items-center px-0.5 md:px-2 h-12 rounded-md overflow-hidden transition-colors hover:bg-gray-100"
              href="#"
            >
              <span class="mr-2.5 text-xl">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#e7a33e"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M3 3v15a3 3 0 003 3h12a3 3 0 003-3V3zm13 1.75A1.25 1.25 0 1114.75 6 1.25 1.25 0 0116 4.75zm-8 0A1.25 1.25 0 116.75 6 1.25 1.25 0 018 4.75zM19 18a1 1 0 01-1 1H6a1 1 0 01-1-1V9h14zm-5.9-3a1 1 0 00-1-1H12a3.12 3.12 0 00-1 .2l-1-.2v-3h3.9v1H11v1.15a3.7 3.7 0 011.05-.15 1.89 1.89 0 012 1.78V15a1.92 1.92 0 01-1.84 2H12a1.88 1.88 0 01-2-1.75 1 1 0 010-.25h1a.89.89 0 001 1h.1a.94.94 0 001-.88z"
                  ></path>
                </svg>
              </span>
              <span class="text-sm font-medium">Event</span>
            </a>
          </li>
          <li>
            <a
              class="flex items-center px-0.5 md:px-2 h-12 rounded-md overflow-hidden transition-colors hover:bg-gray-100"
              href="#"
            >
              <span class="mr-2.5 text-xl">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#fc9295"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M21 3v2H3V3zm-6 6h6V7h-6zm0 4h6v-2h-6zm0 4h6v-2h-6zM3 21h18v-2H3zM13 7H3v10h10z"
                  ></path>
                </svg>
              </span>
              <span class="text-sm font-medium">Write Article</span>
            </a>
          </li>
        </ul>
      </div>
      <button class="flex w-full items-center my-2">
        <hr class="flex-1 bg-neutral-400 mr-2 h-0.5" />
        <div class="flex justify-end items-center">
          <span class="text-gray-500 text-xs font-base mr-1">Sort by:</span>
          <span class="text-xs font-medium">Top</span>
          <span>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 16 16"
              data-supported-dps="16x16"
              fill="#000000e6"
              class="mercado-match"
              width="16"
              height="16"
              focusable="false"
            >
              <path d="M8 11L3 6h10z" fill-rule="evenodd"></path>
            </svg>
          </span>
        </div>
      </button>
      <div class="rounded-md overflow-hidden bg-white">
        <div>
          <div class="flex justify-between pt-3 px-4">
            <a class="flex w-full" href="#">
              <div class="mr-2">
                <img
                  class="w-12"
                  src="https://media-exp1.licdn.com/dms/image/C4E0BAQGLKj3JHcof0w/company-logo_100_100/0/1589990867649?e=1651104000&v=beta&t=ozS3zZX8ZnEq75723s7qqHUlBC8CjxD5XfWAe3CpFPg"
                  alt=""
                />
              </div>
              <div>
                <span class="block font-medium text-sm">Daniel</span>
                <span class="block font-thin text-xs text-gray-500"
                  >Team Lead of Frontend Engineer at Perqara</span
                >
                <span class="flex items-center font-thin text-xs text-gray-500">
                  <span class="mr-1">6 Day •</span>
                  <span>
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 16 16"
                      data-supported-dps="16x16"
                      fill="#00000099"
                      class="mercado-match"
                      width="16"
                      height="16"
                      focusable="false"
                    >
                      <path
                        d="M8 1a7 7 0 107 7 7 7 0 00-7-7zM3 8a5 5 0 011-3l.55.55A1.5 1.5 0 015 6.62v1.07a.75.75 0 00.22.53l.56.56a.75.75 0 00.53.22H7v.69a.75.75 0 00.22.53l.56.56a.75.75 0 01.22.53V13a5 5 0 01-5-5zm6.24 4.83l2-2.46a.75.75 0 00.09-.8l-.58-1.16A.76.76 0 0010 8H7v-.19a.51.51 0 01.28-.45l.38-.19a.74.74 0 01.68 0L9 7.5l.38-.7a1 1 0 00.12-.48v-.85a.78.78 0 01.21-.53l1.07-1.09a5 5 0 01-1.54 9z"
                      ></path>
                    </svg>
                  </span>
                </span>
              </div>
            </a>
            <button class="flex">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 24 24"
                data-supported-dps="24x24"
                fill="#00000099"
                class="mercado-match"
                width="24"
                height="24"
                focusable="false"
              >
                <path
                  d="M14 12a2 2 0 11-2-2 2 2 0 012 2zM4 10a2 2 0 102 2 2 2 0 00-2-2zm16 0a2 2 0 102 2 2 2 0 00-2-2z"
                ></path>
              </svg>
            </button>
          </div>
          <span class="px-4 flex flex-wrap text-sm mt-2">
            <span class="px-2">
              Hi,
              <br />
              open For:
              <br />

              Senior Frontend Engineer
              <br />

              Requirements:
              <br />
              1. 3-5 years Experience implementation of web development
              <br />
              2. Have strong leadership
              <br />
              3. Proactive in communication
              <br />
              4. Strong Project Management knowledge.
              <br />
              5. Good in ENGLISH Communication
              <br />
              <br />

              Scope:
              <br />
              1. Start – immediately, 3 months durations
              <br />
              2. Location – Jakarta
              <br />
              3. The PM personal have a good and strong managerial project and
              have a good communication , coordination across the dept
              <br />
              4. Make daily task and report project
              <br />
              5. Working close and coordination
              <br />

              <br />

              <br />
              If you want to try apply this position, Please submit your
              curriculume vitae detail through, email: daniel@perqara.com
              <br />
            </span>
            <button
              class="font-medium text-sky-600 mt-3 mb-1.5 rounded-md py-0.5 px-2 transition-colors hover:bg-sky-100"
            ></button>
          </span>
        </div>
        <button>
          <div class="flex px-3 py-2">
            <img
              src="https://static-exp1.licdn.com/sc/h/8ekq8gho1ruaf8i7f86vd1ftt"
              alt=""
            />
            <span class="text-xs text-gray-400">58</span>
          </div>
        </button>
        <hr class="bg-gray-200 mx-2 mb-4" />
        <div>
          <h3 class="px-4 mb-2">Reactions</h3>
          <ul
            class="flex px-3 justify-start md:justify-between flex-wrap md:flex-nowrap"
          >
            <li>
              <a class="inline-block w-12 relative mr-2 md:mr-0" href="#">
                <img
                  class="rounded-full overflow-hidden"
                  src="https://picsum.photos/48/48?random=1"
                  alt=""
                />
                <img
                  class="absolute bottom-0 right-0"
                  src="https://static-exp1.licdn.com/sc/h/4c1dzspg0yqfip47a9y26tnx8"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a class="inline-block w-12 relative mr-2 md:mr-0" href="#">
                <img
                  class="rounded-full overflow-hidden"
                  src="https://picsum.photos/48/48?random=2"
                  alt=""
                />
                <img
                  class="absolute bottom-0 right-0"
                  src="https://static-exp1.licdn.com/sc/h/4c1dzspg0yqfip47a9y26tnx8"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a class="inline-block w-12 relative mr-2 md:mr-0" href="#">
                <img
                  class="rounded-full overflow-hidden"
                  src="https://picsum.photos/48/48?random=3"
                  alt=""
                />
                <img
                  class="absolute bottom-0 right-0"
                  src="https://static-exp1.licdn.com/sc/h/4c1dzspg0yqfip47a9y26tnx8"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a class="inline-block w-12 relative mr-2 md:mr-0" href="#">
                <img
                  class="rounded-full overflow-hidden"
                  src="https://picsum.photos/48/48?random=4"
                  alt=""
                />
                <img
                  class="absolute bottom-0 right-0"
                  src="https://static-exp1.licdn.com/sc/h/4c1dzspg0yqfip47a9y26tnx8"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a class="inline-block w-12 relative mr-2 md:mr-0" href="#">
                <img
                  class="rounded-full overflow-hidden"
                  src="https://picsum.photos/48/48?random=5"
                  alt=""
                />
                <img
                  class="absolute bottom-0 right-0"
                  src="https://static-exp1.licdn.com/sc/h/4c1dzspg0yqfip47a9y26tnx8"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a class="inline-block w-12 relative mr-2 md:mr-0" href="#">
                <img
                  class="rounded-full overflow-hidden"
                  src="https://picsum.photos/48/48?random=6"
                  alt=""
                />
                <img
                  class="absolute bottom-0 right-0"
                  src="https://static-exp1.licdn.com/sc/h/4c1dzspg0yqfip47a9y26tnx8"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a class="inline-block w-12 relative mr-2 md:mr-0" href="#">
                <img
                  class="rounded-full overflow-hidden"
                  src="https://picsum.photos/48/48?random=7"
                  alt=""
                />
                <img
                  class="absolute bottom-0 right-0"
                  src="https://static-exp1.licdn.com/sc/h/4c1dzspg0yqfip47a9y26tnx8"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a class="inline-block w-12 relative mr-2 md:mr-0" href="#">
                <img
                  class="rounded-full overflow-hidden"
                  src="https://picsum.photos/48/48?random=8"
                  alt=""
                />
                <img
                  class="absolute bottom-0 right-0"
                  src="https://static-exp1.licdn.com/sc/h/4c1dzspg0yqfip47a9y26tnx8"
                  alt=""
                />
              </a>
            </li>
            <li>
              <a
                class="inline-flex items-center justify-center border rounded-full p-2.5"
                href="#"
                >+52</a
              >
            </li>
          </ul>
        </div>
        <ul class="flex items-center justify-between px-4 mb-2">
          <li>
            <a
              class="flex py-3 px-0 md:px-5 items-center rounded-md transition-colors hover:bg-gray-200"
              href="#"
            >
              <span class="mr-1">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#00000099"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M19.46 11l-3.91-3.91a7 7 0 01-1.69-2.74l-.49-1.47A2.76 2.76 0 0010.76 1 2.75 2.75 0 008 3.74v1.12a9.19 9.19 0 00.46 2.85L8.89 9H4.12A2.12 2.12 0 002 11.12a2.16 2.16 0 00.92 1.76A2.11 2.11 0 002 14.62a2.14 2.14 0 001.28 2 2 2 0 00-.28 1 2.12 2.12 0 002 2.12v.14A2.12 2.12 0 007.12 22h7.49a8.08 8.08 0 003.58-.84l.31-.16H21V11zM19 19h-1l-.73.37a6.14 6.14 0 01-2.69.63H7.72a1 1 0 01-1-.72l-.25-.87-.85-.41A1 1 0 015 17l.17-1-.76-.74A1 1 0 014.27 14l.66-1.09-.73-1.1a.49.49 0 01.08-.7.48.48 0 01.34-.11h7.05l-1.31-3.92A7 7 0 0110 4.86V3.75a.77.77 0 01.75-.75.75.75 0 01.71.51L12 5a9 9 0 002.13 3.5l4.5 4.5H19z"
                  ></path>
                </svg>
              </span>
              <span class="font-medium text-sm text-gray-500">Like</span>
            </a>
          </li>
          <li>
            <a
              class="flex py-3 px-0 md:px-5 items-center rounded-md transition-colors hover:bg-gray-200"
              href="#"
            >
              <span class="mr-1">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#00000099"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M7 9h10v1H7zm0 4h7v-1H7zm16-2a6.78 6.78 0 01-2.84 5.61L12 22v-4H8A7 7 0 018 4h8a7 7 0 017 7zm-2 0a5 5 0 00-5-5H8a5 5 0 000 10h6v2.28L19 15a4.79 4.79 0 002-4z"
                  ></path>
                </svg>
              </span>
              <span class="font-medium text-sm text-gray-500"> Comment </span>
            </a>
          </li>
          <li>
            <a
              class="flex py-3 px-0 md:px-5 items-center rounded-md transition-colors hover:bg-gray-200"
              href="#"
            >
              <span class="mr-1">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#00000099"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M23 12l-4.61 7H16l4-6H8a3.92 3.92 0 00-4 3.84V17a4 4 0 00.19 1.24L5.12 21H3l-.73-2.22A6.4 6.4 0 012 16.94 6 6 0 018 11h12l-4-6h2.39z"
                  ></path>
                </svg>
              </span>
              <span class="font-medium text-sm text-gray-500"> Share </span>
            </a>
          </li>
          <li>
            <a
              class="flex py-3 px-0 md:px-5 items-center rounded-md transition-colors hover:bg-gray-200"
              href="#"
            >
              <span class="mr-1">
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#00000099"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M21 3L0 10l7.66 4.26L16 8l-6.26 8.34L14 24l7-21z"
                  ></path>
                </svg>
              </span>
              <span class="font-medium text-sm text-gray-500">Send</span>
            </a>
          </li>
        </ul>
        <div class="flex items-center px-4">
          <div class="rounded-full overflow-hidden mr-2">
            <img
              class="w-10"
              src="https://media-exp1.licdn.com/dms/image/C5603AQEbFYZ9oBEW6w/profile-displayphoto-shrink_100_100/0/1631902344577?e=1648080000&v=beta&t=VXE7c7VEt3_DJC7_3TX_I0J5UO12PmSA62_pId3k4BQ"
              alt=""
            />
          </div>
          <div class="w-full relative">
            <input
              class="border border-gray-100 pl-2 py-2 rounded-full focus:outline-none placeholder:font-normal placeholder:text-sm w-full focus:border-gray-300"
              placeholder="Add Comment..."
              type="text"
            />
            <span class="absolute right-0 top-0 flex items-center">
              <span
                class="inline-block rounded-full p-2 mr-2 cursor-pointer hover:bg-gray-200 transition-colors"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#00000099"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M8 10.5A1.5 1.5 0 119.5 12 1.5 1.5 0 018 10.5zm6.5 1.5a1.5 1.5 0 10-1.5-1.5 1.5 1.5 0 001.5 1.5zm7.5 0A10 10 0 1112 2a10 10 0 0110 10zm-2 0a8 8 0 10-8 8 8 8 0 008-8zm-8 4a6 6 0 01-4.24-1.76l-.71.76a7 7 0 009.89 0l-.71-.71A6 6 0 0112 16z"
                  ></path>
                </svg>
              </span>
              <span
                class="inline-block rounded-full p-2 cursor-pointer hover:bg-gray-200 transition-colors"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 24 24"
                  data-supported-dps="24x24"
                  fill="#00000099"
                  class="mercado-match"
                  width="24"
                  height="24"
                  focusable="false"
                >
                  <path
                    d="M19 4H5a3 3 0 00-3 3v10a3 3 0 003 3h14a3 3 0 003-3V7a3 3 0 00-3-3zm1 13a1 1 0 01-.29.71L16 14l-2 2-6-6-4 4V7a1 1 0 011-1h14a1 1 0 011 1zm-2-7a2 2 0 11-2-2 2 2 0 012 2z"
                  ></path>
                </svg>
              </span>
            </span>
          </div>
        </div>
      </div>
    </div>
</template>
