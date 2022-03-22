<template>
  <div class="document-background text-gray-300 h-screen font-poppins">
    <header class="flex flex-row justify-between items-center px-12 py-4">
      <div class="font-bold text-4xl">
        Markai
      </div>
      <ul class="flex flex-row gap-12 text-lg flex-center">
        <li class="cursor-pointer">Feature</li>
        <li class="cursor-pointer">Products</li>
        <li>Company</li>
        <li>Pricing</li>
        <li>Support</li>
      </ul>

      <ul class="flex flex-row gap-4 text-lg items-center">
        <li>Login</li>
        <li>
          <button class="border border-gray-400 px-4 py-1 rounded-full">
            Register
          </button>
        </li>
      </ul>

    </header>

    <section class="w-full flex flex-row justify-center">
      <div class="flex flex-col gap-4 w-1/3 text-center mt-36 mb-12">
        <p class="text-xl">Let Ai help you</p>

        <h1 class="text-4xl uppercase font-bold text-transparent bg-clip-text bg-gradient-to-r from-indigo-500 via-purple-500 to-pink-500">Marketing Team</h1>

        <p class="text-gray-400 text-lg">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas purus odio tempor rutrum condimentum viverra ornare. Gravida tellus ut venenatis.</p>

        <div class="flex flex-row justify-center">
          <button class="flex flex-row gap-2 w-4/12 justify-center items-center border border-gray-200 rounded-full px-4 py-2">
            <span>Let's go</span>
            <svg width="25" height="24" viewBox="0 0 62 24" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M61.0607 13.0607C61.6465 12.4749 61.6465 11.5251 61.0607 10.9393L51.5147 1.3934C50.9289 0.807611 49.9792 0.807611 49.3934 1.3934C48.8076 1.97919 48.8076 2.92893 49.3934 3.51472L57.8787 12L49.3934 20.4853C48.8076 21.0711 48.8076 22.0208 49.3934 22.6066C49.9792 23.1924 50.9289 23.1924 51.5147 22.6066L61.0607 13.0607ZM0 13.5H60V10.5H0V13.5Z" fill="url(#paint0_linear_2_8014)"/>
              <defs>
                <linearGradient id="paint0_linear_2_8014" x1="0" y1="13" x2="60" y2="13" gradientUnits="userSpaceOnUse">
                  <stop stop-color="#00F0FF"/>
                  <stop offset="0.46875" stop-color="#5773FF"/>
                  <stop offset="1" stop-color="#FF007A"/>
                </linearGradient>
              </defs>
            </svg>
          </button>
        </div>

        <div class="flex flex-row justify-center mt-8">
          <svg width="37" height="37" viewBox="0 0 87 37" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M1 2L43.5 35L86 2" stroke="white" stroke-width="3"/>
          </svg>
        </div>

      </div>
    </section>
  </div>
</template>

<script>
import Hero from '~/components/Hero.vue';
import Testimonials from '~/components/Testimonials.vue';
import CallAction from '~/components/CallAction.vue';

export default {
  components: {
    Hero,
    Testimonials,
    CallAction
  },
  head: {
    title: 'Starter - Level up your website.',
    meta: [ // SEO Tags
      {
        hid: 'description',
        name: 'description',
        content: 'My starter home page'
      }
    ]
  },
  data: () => ({
    testimonials: [
      {
        id: 1,
        name: 'James Durant',
        jobTitle: 'Owner, Steak House',
        message: 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium'
      },
      {
        id: 2,
        name: 'Christopher Buddy',
        jobTitle: 'CEO, HouseDesign Ltd.',
        message: 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium'
      },
      {
        id: 3,
        name: 'Alphonse Todd',
        jobTitle: 'CTO, MarketplaceDesign Inc.',
        message: 'Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium'
      }
    ]
  })
}
</script>
