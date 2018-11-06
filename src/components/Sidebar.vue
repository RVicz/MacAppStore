<template>
    <div class="bg-grey-darkest w-56 text-white border-r border-absblack fixed min-h-screen pt-8">
        <div class="search-container text-center p-4 relative border-grey-light clickable">
            <input type="text" placeholder="Search" class="bg-grey-darker text-grey-light text-xs w-full p-2 pl-8 border-grey-dark rounded ">

            <div class="absolute pin-t py-5 px-2 text-grey-light">
                <svg fill="currentColor" version="1.1" id="Capa_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="16" height="16" viewBox="0 0 53.627 53.627" style="enable-background:new 0 0 53.627 53.627;" xml:space="preserve">
                    <path d="M53.627,49.385L37.795,33.553C40.423,30.046,42,25.709,42,21C42,9.42,32.58,0,21,0S0,9.42,0,21s9.42,21,21,21
                        c4.709,0,9.046-1.577,12.553-4.205l15.832,15.832L53.627,49.385z M2,21C2,10.523,10.523,2,21,2s19,8.523,19,19s-8.523,19-19,19
                        S2,31.477,2,21z M35.567,36.093c0.178-0.172,0.353-0.347,0.525-0.525c0.146-0.151,0.304-0.29,0.445-0.445l14.262,14.262
                        l-1.415,1.415L35.123,36.537C35.278,36.396,35.416,36.238,35.567,36.093z"/>
                </svg>
            </div>
        </div>

        <div class="sidebar-icons clickable">
            <div class="sidebar-icon flex items-center px-4 py-2 text-grey cursor-pointer bg-grey-darker hover:bg-grey-darker">
                <svg class="mr-3" width="24px" height="24px" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><path d="M1728 647q0 22-26 48l-363 354 86 500q1 7 1 20 0 21-10.5 35.5t-30.5 14.5q-19 0-40-12l-449-236-449 236q-22 12-40 12-21 0-31.5-14.5t-10.5-35.5q0-6 2-20l86-500-364-354q-25-27-25-48 0-37 56-46l502-73 225-455q19-41 49-41t49 41l225 455 502 73q56 9 56 46z" fill="currentColor"/></svg>
                <div class="text-white">Discover</div>
            </div>

            <div class="sidebar-icon flex items-center px-4 py-2 text-grey cursor-pointer hover:bg-grey-darker">
                <svg class="mr-3" width="24px" height="24px" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><path d="M1615 0q70 0 122.5 46.5t52.5 116.5q0 63-45 151-332 629-465 752-97 91-218 91-126 0-216.5-92.5t-90.5-219.5q0-128 92-212l638-579q59-54 130-54zm-909 1034q39 76 106.5 130t150.5 76l1 71q4 213-129.5 347t-348.5 134q-123 0-218-46.5t-152.5-127.5-86.5-183-29-220q7 5 41 30t62 44.5 59 36.5 46 17q41 0 55-37 25-66 57.5-112.5t69.5-76 88-47.5 103-25.5 125-10.5z" fill="currentColor"/></svg>
                <div class="text-white">Create</div>
            </div>

            <div class="sidebar-icon flex items-center px-4 py-2 text-grey cursor-pointer hover:bg-grey-darker">
                <svg class="mr-3" width="24px" height="24px" fill="currentColor" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><path d="M1764 11q33 24 27 64l-256 1536q-5 29-32 45-14 8-31 8-11 0-24-5l-453-185-242 295q-18 23-49 23-13 0-22-4-19-7-30.5-23.5t-11.5-36.5v-349l864-1059-1069 925-395-162q-37-14-40-55-2-40 32-59l1664-960q15-9 32-9 20 0 36 11z"/></svg>
                <div class="text-white">Work</div>
            </div>

            <div class="sidebar-icon flex items-center px-4 py-2 text-grey cursor-pointer hover:bg-grey-darker">
                <svg class="mr-3" width="24px" height="24px" fill="currentColor" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><path d="M1504 448q0-40-28-68t-68-28-68 28-28 68 28 68 68 28 68-28 28-68zm224-288q0 249-75.5 430.5t-253.5 360.5q-81 80-195 176l-20 379q-2 16-16 26l-384 224q-7 4-16 4-12 0-23-9l-64-64q-13-14-8-32l85-276-281-281-276 85q-3 1-9 1-14 0-23-9l-64-64q-17-19-5-39l224-384q10-14 26-16l379-20q96-114 176-195 188-187 358-258t431-71q14 0 24 9.5t10 22.5z"/></svg>
                <div class="text-white">Play</div>
            </div>

            <div class="sidebar-icon flex items-center px-4 py-2 text-grey cursor-pointer hover:bg-grey-darker">
                <svg class="mr-3" width="24px" height="24px" fill="currentColor" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><path d="M448 1472q0-26-19-45t-45-19-45 19-19 45 19 45 45 19 45-19 19-45zm644-420l-682 682q-37 37-90 37-52 0-91-37l-106-108q-38-36-38-90 0-53 38-91l681-681q39 98 114.5 173.5t173.5 114.5zm634-435q0 39-23 106-47 134-164.5 217.5t-258.5 83.5q-185 0-316.5-131.5t-131.5-316.5 131.5-316.5 316.5-131.5q58 0 121.5 16.5t107.5 46.5q16 11 16 28t-16 28l-293 169v224l193 107q5-3 79-48.5t135.5-81 70.5-35.5q15 0 23.5 10t8.5 25z"/></svg>
                <div class="text-white">Develop</div>
            </div>

            <div class="sidebar-icon flex items-center px-4 py-2 text-grey cursor-pointer hover:bg-grey-darker">
                <svg  class="mr-3" width="24px" height="24px" fill="currentColor" viewBox="0 0 2048 1792" xmlns="http://www.w3.org/2000/svg"><path d="M512 448q0-53-37.5-90.5t-90.5-37.5-90.5 37.5-37.5 90.5 37.5 90.5 90.5 37.5 90.5-37.5 37.5-90.5zm1067 576q0 53-37 90l-491 492q-39 37-91 37-53 0-90-37l-715-716q-38-37-64.5-101t-26.5-117v-416q0-52 38-90t90-38h416q53 0 117 26.5t102 64.5l715 714q37 39 37 91zm384 0q0 53-37 90l-491 492q-39 37-91 37-36 0-59-14t-53-45l470-470q37-37 37-90 0-52-37-91l-715-714q-38-38-102-64.5t-117-26.5h224q53 0 117 26.5t102 64.5l715 714q37 39 37 91z"/></svg>
                <div class="text-white">Categories</div>
            </div>

            <div class="sidebar-icon flex items-center px-4 py-2 text-grey cursor-pointer hover:bg-grey-darker">
                <svg class="mr-3" width="24px" height="24px" fill="currentColor" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><path d="M1344 1344q0-26-19-45t-45-19-45 19-19 45 19 45 45 19 45-19 19-45zm256 0q0-26-19-45t-45-19-45 19-19 45 19 45 45 19 45-19 19-45zm128-224v320q0 40-28 68t-68 28h-1472q-40 0-68-28t-28-68v-320q0-40 28-68t68-28h465l135 136q58 56 136 56t136-56l136-136h464q40 0 68 28t28 68zm-325-569q17 41-14 70l-448 448q-18 19-45 19t-45-19l-448-448q-31-29-14-70 17-39 59-39h256v-448q0-26 19-45t45-19h256q26 0 45 19t19 45v448h256q42 0 59 39z"/></svg>
                <div class="text-white">Updates</div>
            </div> <!-- end sidebar-icon -->
        </div> <!-- end sidebar-icons -->

        <div class="absolute pin-b w-full pb-4">
            <div class="sidebar-icon flex items-center px-8 py-2 text-grey cursor-pointer hover:bg-grey-darker clickable">
                <svg class="mr-3" width="24px" height="24px" fill="currentColor" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><path d="M1523 1339q-22-155-87.5-257.5t-184.5-118.5q-67 74-159.5 115.5t-195.5 41.5-195.5-41.5-159.5-115.5q-119 16-184.5 118.5t-87.5 257.5q106 150 271 237.5t356 87.5 356-87.5 271-237.5zm-243-699q0-159-112.5-271.5t-271.5-112.5-271.5 112.5-112.5 271.5 112.5 271.5 271.5 112.5 271.5-112.5 112.5-271.5zm512 256q0 182-71 347.5t-190.5 286-285.5 191.5-349 71q-182 0-348-71t-286-191-191-286-71-348 71-348 191-286 286-191 348-71 348 71 286 191 191 286 71 348z"/></svg>
                <div class="text-white">Reuel Victor</div>
            </div>
        </div>

    </div>
</template>