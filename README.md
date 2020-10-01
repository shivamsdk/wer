# wer
!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta=name"viewport" content="width=device=width, initail-scale=1.0">
  <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
  <title>Titus</title>
</head>
<body>

    <header class="here is a gift for you">
        <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
          <a class="flex title-font font-medium items-center text-gray-900 mb-4 md:mb-0">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-indigo-500 rounded-full" viewBox="0 0 24 24">
              <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
            </svg>
            <span class="ml-3 text-xl">tailblocks</span>
          </a>
          <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-gray-400	flex flex-wrap items-center text-base justify-center">
            <a class="mr-5 hover:text-gray-900">First Link</a>
            <a class="mr-5 hover:text-gray-900">Second Link</a>
            <a class="mr-5 hover:text-gray-900">third Link</a>
            <a class="mr-5 hover:text-gray-900">Fourth Link</a>
          </nav>
          <button class="inline-flex items-center bg-gray-200 border-0 py-1 px-3 focus:outline-none hover:bg-gray-300 rounded text-base mt-4 md:mt-0">Button
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </button>
        </div>
      </header>

      <section class="text-gray-700 body-font">
        <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
          <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
            <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-gray-900">Before they sold out
              <br class="hidden lg:inline-block">readymade gluten
            </h1>
            <p class="mb-8 leading-relaxed">Copper mug try-hard pitchfork pour-over freegan heirloom neutra air plant cold-pressed tacos poke beard tote bag. Heirloom echo park mlkshk tote bag selvage hot chicken authentic tumeric truffaut hexagon try-hard chambray.</p>
            <div class="flex justify-center">
              <button class="inline-flex text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded text-lg">Button</button>
              <button class="ml-4 inline-flex text-gray-700 bg-gray-200 border-0 py-2 px-6 focus:outline-none hover:bg-gray-300 rounded text-lg">pay now</button>
            </div>
          </div>
          <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
            <img class="object-cover object-center rounded" alt="hero" src="https://source.unsplash.com/720x600/?coding">
          </div>
        </div>
      </section>

      <section class="text-gray-700 body-font">
        <div class="container px-5 py-24 mx-auto">
          <div class="flex flex-col text-center w-full mb-20">
            <h1 class="sm:text-4xl text-3xl font-medium title-font mb-2 text-gray-900">Pricing</h1>
            <p class="lg:w-2/3 mx-auto leading-relaxed text-base">Banh mi cornhole echo park skateboard authentic crucifix neutra tilde lyft biodiesel artisan direct trade mumblecore 3 wolf moon twee</p>
          </div>
          <div class="lg:w-2/3 w-full mx-auto overflow-auto">
            <table class="table-auto w-full text-left whitespace-no-wrap">
              <thead>
                <tr>
                  <th class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-200 rounded-tl rounded-bl">Plan</th>
                  <th class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-200">Speed</th>
                  <th class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-200">Storage</th>
                  <th class="px-4 py-3 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-200">Price</th>
                  <th class="w-10 title-font tracking-wider font-medium text-gray-900 text-sm bg-gray-200 rounded-tr rounded-br"></th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="px-4 py-3">Start</td>
                  <td class="px-4 py-3">50</td>
                  <td class="px-4 py-3">15</td>
                  <td class="px-4 py-3 text-lg text-gray-900">200</td>
                  <td class="w-10 text-center">
                    <input name="plan" type="radio">
                  </td>
                </tr>
                <tr>
                  <td class="border-t-2 border-gray-200 px-4 py-3">Pro</td>
                  <td class="border-t-2 border-gray-200 px-4 py-3">250</td>
                  <td class="border-t-2 border-gray-200 px-4 py-3">250</td>
                  <td class="border-t-2 border-gray-200 px-4 py-3 text-lg text-gray-900">400</td>
                  <td class="border-t-2 border-gray-200 w-10 text-center">
                    <input name="plan" type="radio">
                  </td>
                </tr>
                <tr>
                  <td class="border-t-2 border-gray-200 px-4 py-3">Business</td>
                  <td class="border-t-2 border-gray-200 px-4 py-3">360</td>
                  <td class="border-t-2 border-gray-200 px-4 py-3">400</td>
                  <td class="border-t-2 border-gray-200 px-4 py-3 text-lg text-gray-900">500</td>
                  <td class="border-t-2 border-gray-200 w-10 text-center">
                    <input name="best website " type="radio">
                  </td>
                </tr>
                <tr>
                  <td class="border-t-2 border-b-2 border-gray-200 px-4 py-3">Exclusive</td>
                  <td class="border-t-2 border-b-2 border-gray-200 px-4 py-3">480</td>
                  <td class="border-t-2 border-b-2 border-gray-200 px-4 py-3">one time </td>
                  <td class="border-t-2 border-b-2 border-gray-200 px-4 py-3 text-lg text-gray-900">720</td>
                  <td class="border-t-2 border-b-2 border-gray-200 w-10 text-center">
                    <input name="plan" type="radio">
                  </td>
                </tr>
              </tbody>
            </table>
          </div>
          <div class="flex pl-4 mt-4 lg:w-2/3 w-full mx-auto">
            <a class="text-indigo-500 inline-flex items-center md:mb-2 lg:mb-0">Learn More
              <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                <path d="M5 12h14M12 5l7 7-7 7"></path>
              </svg>
            </a>
            <button class="flex ml-auto text-white bg-indigo-500 border-0 py-2 px-6 focus:outline-none hover:bg-indigo-600 rounded">pay now</Button>
          </div>
        </div>
      </section>

      <section class="text-gray-700 body-font">
        <div class="container px-5 py-24 mx-auto">
          <div class="flex flex-wrap -m-4 text-center">
            <div class="p-4 sm:w-1/4 w-1/2">
              <h2 class="title-font font-medium sm:text-4xl text-3xl text-gray-900">2.7K</h2>
              <p class="leading-relaxed">users</p>
            </div>
            <div class="p-4 sm:w-1/4 w-1/2">
              <h2 class="title-font font-medium sm:text-4xl text-3xl text-gray-900">1.8K</h2>
              <p class="leading-relaxed">likes</p>
            </div>
            <div class="p-4 sm:w-1/4 w-1/2">
              <h2 class="title-font font-medium sm:text-4xl text-3xl text-gray-900">35</h2>
              <p class="leading-relaxed">website</p>
            </div>
            <div class="p-4 sm:w-1/4 w-1/2">
              <h2 class="title-font font-medium sm:text-4xl text-3xl text-gray-900">40</h2>
              <p class="leading-relaxed">website</p>
            </div>
          </div>
        </div>
      </section>
