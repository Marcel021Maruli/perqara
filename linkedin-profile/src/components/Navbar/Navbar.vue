<template>
  <header class="bg-white	w-full flex justify-center min-h-[52px] sticky top-0 z-50">
        <div class="w-full md:w-[1128px] flex justify-center">
            <div class="w-full flex items-center justify-between">
                <div class="flex justify-center md:justify-start items-center w-2/12 xl:w-5/12">
                    <a class="mr-1.5" href="#">
                        <svg style="color: #0a66c2;" xmlns="http://www.w3.org/2000/svg" width="34" height="34" viewBox="0 0 34 34">
                            <title>
                              LinkedIn
                            </title>
                      
                            <g>
                              <path d="M34,2.5v29A2.5,2.5,0,0,1,31.5,34H2.5A2.5,2.5,0,0,1,0,31.5V2.5A2.5,2.5,0,0,1,2.5,0h29A2.5,2.5,0,0,1,34,2.5ZM10,13H5V29h5Zm.45-5.5A2.88,2.88,0,0,0,7.59,4.6H7.5a2.9,2.9,0,0,0,0,5.8h0a2.88,2.88,0,0,0,2.95-2.81ZM29,19.28c0-4.81-3.06-6.68-6.1-6.68a5.7,5.7,0,0,0-5.06,2.58H17.7V13H13V29h5V20.49a3.32,3.32,0,0,1,3-3.58h.19c1.59,0,2.77,1,2.77,3.52V29h5Z" fill="currentColor"></path>
                            </g>
                          </svg>
                    </a>
                <label class="hidden xl:block" for="input">
                    <div class="relative">
                        <div class="absolute text-gray-500 top-2.5 left-4">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" data-supported-dps="16x16" fill="#00000099" class="mercado-match" width="16" height="16" focusable="false">
                                <path d="M14.56 12.44L11.3 9.18a5.51 5.51 0 10-2.12 2.12l3.26 3.26a1.5 1.5 0 102.12-2.12zM3 6.5A3.5 3.5 0 116.5 10 3.5 3.5 0 013 6.5z"></path>
                              </svg>
                        </div>
                        <div class="w-94">
                            <input id="input" placeholder="Search" class=" bg-gray-100 h-9 py-1 pl-12 w-64 font-thin text-black rounded-md focus:outline-none focus:w-96 transition-all" type="text">
                        </div>
                    </div>
                </label>
                </div>
                <ul class="flex items-center justify-between w-10/12 xl:w-7/12">
                    <li class="border-0 md:border-b-2 md:border-black w-20">
                        <a href="#" class="flex flex-col items-center text-black">
                            <div class="text-xl"><i class="fas fa-home"></i></div>
                            <span class="text-xs mt-0.5 mb-1 hidden md:block">Home</span>
                        </a>
                    </li>
                    <li class="w-20	">
                        <a href="#" class="flex flex-col items-center text-gray-500 hover:text-black transition-all">
                            <div class="text-xl"><i class="fas fa-user-friends"></i></div>
                            <span class="text-xs mt-0.5 hidden md:block">My Network</span>
                        </a>
                    </li>
                    <li class="w-20">
                        <a href="#" class="flex flex-col items-center text-gray-500 hover:text-black transition-all">
                            <div class="text-xl"><i class="fas fa-briefcase"></i></div>
                            <span class="text-xs mt-0.5 hidden md:block">Jobs</span>
                        </a>
                    </li>
                    <li class="w-20">
                        <a href="#" class="flex flex-col items-center text-gray-500 hover:text-black transition-all">
                            <div class="text-xl"><i class="fas fa-comment-dots"></i></div>
                            <span class="text-xs mt-0.5 hidden md:block">Messaging</span>
                        </a>
                    </li>
                    <li class="w-20">
                        <a href="#" class="flex flex-col items-center text-gray-500 hover:text-black transition-all">
                            <div class="text-xl"><i class="fas fa-bell"></i></div>
                            <span class="text-xs mt-0.5 hidden md:block">Notifications</span>
                        </a>
                    </li>
                    <li class="border-0 md:border-r-2 w-20">
                        <a href="#" class="flex flex-col items-center text-gray-500 mr-1 hover:text-black transition-all">
                            <img class="w-6 rounded-full" src="https://media-exp2.licdn.com/dms/image/C5603AQG9aLNCzjPV9g/profile-displayphoto-shrink_100_100/0/1650810713709?e=1662595200&v=beta&t=J02QfD06AgawE1sjC6m-pgdkQGTRjJFIWTsaPqcRyqg" alt="">
                            <span class="text-xs mt-0.5 items-center hidden md:flex">Me
                                <i class="fas fa-sort-down ml-1"></i>
                            </span>
                        </a>
                    </li>
                    <li class="w-20 hidden sm:block">
                        <a class="flex flex-col text-gray-500 hover:text-black items-center" href="#">
                            <i class="fas fa-th"></i>
                            <span class="text-xs mt-0.5 hidden md:block">Work
                                    <i class="fas fa-sort-down"></i>
                            </span>
                        </a>
                    </li>
                    <li class="w-32 hidden sm:block">
                        <a class="flex justify-center flex-col items-center text-xs text-orange-900 hover:underline" href="#">
                            <div>Get Hired Faster,</div>
                            <div>Try Premium Free</div>
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </header>
</template>

<style scoped>


</style>
