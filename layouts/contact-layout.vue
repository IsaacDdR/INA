<template>
  <div class="bg-blue-50">
    <div
      class="
        relative
        z-10
        px-4
        py-5
        mx-auto
        sm:max-w-xl
        md:max-w-full
        lg:max-w-screen-xl
        md:px-24
        lg:px-8
      "
    >
      <div class="relative flex items-center justify-between">
        <a
          href="/"
          aria-label="Company"
          title="Company"
          class="inline-flex items-center"
        >
          <img
            src="https://res.cloudinary.com/inacloudimage/image/upload/v1620604867/icon_g9bc09.png"
            class="w-16 md:mr-4 mb-2"
          />

          <span class="ml-2 font-bold tracking-wide text-gray-800 uppercase"
            >Integración y Automatización</span
          >
        </a>
        <ul class="flex items-center hidden space-x-8 lg:flex">
          <li>
            <NuxtLink
              to="/nosotros"
              aria-label="Our product"
              title="Our product"
              class="
                font-medium
                tracking-wide
                text-gray-700
                transition-colors
                duration-200
                hover:text-deep-purple-accent-400
              "
              >Nosotros</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/servicios"
              aria-label="Our product"
              title="Our product"
              class="
                font-medium
                tracking-wide
                text-gray-700
                transition-colors
                duration-200
                hover:text-deep-purple-accent-400
              "
              >Servicios</NuxtLink
            >
          </li>
          <NuxtLink
            to="/contacto"
            aria-label="Our product"
            title="Our product"
            class="
              font-medium
              tracking-wide
              text-gray-700
              transition-colors
              duration-200
              hover:text-deep-purple-accent-400
            "
            >Contacto</NuxtLink
          >
          <!--Blog 
          <li>
            <NuxtLink
              to="/blog"
              aria-label="Product pricing"
              title="Product pricing"
              class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400"
              >Blog</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/contacto"
              aria-label="Contacto"
              title="Contacto"
              class="
                font-medium
                tracking-wide
                text-gray-700
                transition-colors
                duration-200
                hover:text-deep-purple-accent-400
              "
              >Contacto</NuxtLink
            >
          </li>
          -->
        </ul>
        <ul class="flex items-center hidden space-x-8 lg:flex">
          <li>
            <a
              href="https://api.whatsapp.com/send?phone=524421202717&text=%C2%A1Hola!%20Deseo%20m%C3%A1s%20informaci%C3%B3n%20acerca%20de%20los%20productos%20y%20servicios%20de%20%22INA%20integraci%C3%B3n.%20y%20automatizaci%C3%B3n%22"
              class="
                inline-flex
                items-center
                justify-center
                h-12
                px-6
                font-medium
                tracking-wide
                text-white
                transition
                duration-200
                rounded
                shadow-md
                bg-blue-ina
                hover:bg-blue-500
                focus:shadow-outline focus:outline-none
              "
              aria-label="Sign up"
              title="Sign up"
            >
              Whatsapp
            </a>
          </li>
        </ul>
        <!-- Mobile menu -->
        <div class="lg:hidden">
          <button
            aria-label="Open Menu"
            title="Open Menu"
            class="
              p-2
              -mr-1
              transition
              duration-200
              rounded
              focus:outline-none focus:shadow-outline
              hover:bg-deep-purple-50
              focus:bg-deep-purple-50
            "
            @click="showMenu"
          >
            <svg class="w-5 text-gray-600" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                d="M23,13H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,13,23,13z"
              ></path>
              <path
                fill="currentColor"
                d="M23,6H1C0.4,6,0,5.6,0,5s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,6,23,6z"
              ></path>
              <path
                fill="currentColor"
                d="M23,20H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,20,23,20z"
              ></path>
            </svg>
          </button>
          <!-- Mobile menu dropdown -->
          <div
            v-if="show"
            class="
              absolute
              top-0
              left-0
              w-full
              bg-blue-50
              rounded-lg
              shadow-lg
              border-blue-ina border-4
              bg-blue-50
            "
          >
            <div class="p-5 border rounded shadow-sm">
              <div class="flex items-center justify-between mb-4">
                <div>
                  <NuxtLink
                    to="/"
                    aria-label="INA"
                    title="INA"
                    class="inline-flex items-center"
                  >
                    <nuxt-img class="w-20" src="/icon.png" />

                    <span
                      class="
                        ml-2
                        text-xl
                        font-bold
                        tracking-wide
                        text-gray-800
                        uppercase
                      "
                      >INA Integración y Automatización</span
                    >
                  </NuxtLink>
                </div>
                <div>
                  <button
                    aria-label="Close Menu"
                    title="Close Menu"
                    class="
                      p-2
                      -mt-2
                      -mr-2
                      transition
                      duration-200
                      rounded
                      hover:bg-gray-200
                      focus:bg-gray-200 focus:outline-none focus:shadow-outline
                    "
                    @click="showMenu"
                  >
                    <svg class="w-5 text-gray-600" viewBox="0 0 24 24">
                      <path
                        fill="currentColor"
                        d="M19.7,4.3c-0.4-0.4-1-0.4-1.4,0L12,10.6L5.7,4.3c-0.4-0.4-1-0.4-1.4,0s-0.4,1,0,1.4l6.3,6.3l-6.3,6.3 c-0.4,0.4-0.4,1,0,1.4C4.5,19.9,4.7,20,5,20s0.5-0.1,0.7-0.3l6.3-6.3l6.3,6.3c0.2,0.2,0.5,0.3,0.7,0.3s0.5-0.1,0.7-0.3 c0.4-0.4,0.4-1,0-1.4L13.4,12l6.3-6.3C20.1,5.3,20.1,4.7,19.7,4.3z"
                      ></path>
                    </svg>
                  </button>
                </div>
              </div>
              <nav>
                <ul class="text-center space-y-4">
                  <li>
                    <NuxtLink
                      to="/nosotros"
                      aria-label="Our product"
                      title="Our product"
                      class="
                        font-medium
                        text-xl
                        tracking-wide
                        text-blue-ina
                        transition-colors
                        duration-200
                        hover:text-deep-purple-accent-400
                      "
                      >Nosotros</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/servicios"
                      aria-label="Our product"
                      title="Our product"
                      class="
                        text-xl
                        font-medium
                        tracking-wide
                        text-blue-ina
                        transition-colors
                        duration-200
                        hover:text-deep-purple-accent-400
                      "
                      >Servicios</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/contacto"
                      aria-label="Our product"
                      title="Our product"
                      class="
                        text-xl
                        font-medium
                        tracking-wide
                        text-blue-ina
                        transition-colors
                        duration-200
                        hover:text-deep-purple-accent-400
                      "
                      >Contacto</NuxtLink
                    >
                  </li>
                  <li>
                    <section class="text-gray-600 body-font relative">
                      <div
                        class="
                          container
                          pt-4
                          pb-4
                          mx-auto
                          flex
                          sm:flex-nowrap
                          flex-wrap
                        "
                      >
                        <div
                          class="
                            md:w-full
                            bg-gray-300
                            rounded-lg
                            overflow-hidden
                            sm:mr-10
                            p-10
                            flex
                            items-end
                            justify-start
                            relative
                          "
                        >
                          <iframe
                            class="absolute inset-0"
                            style="filter: contrast(1.2) opacity(0.4)"
                            title="map"
                            marginheight="0"
                            marginwidth="0"
                            scrolling="no"
                            src="https://maps.google.com/maps?width=100%&height=600&hl=en&q=%C4%B0zmir+(My%20Business%20Name)&ie=UTF8&t=&z=14&iwloc=B&output=embed"
                            width="100%"
                            height="100%"
                            frameborder="0"
                          ></iframe>
                          <div
                            class="
                              bg-white
                              relative
                              flex flex-wrap
                              py-6
                              rounded
                              shadow-md
                            "
                          >
                            <div class="lg:w-1/2 px-6">
                              <h2
                                class="
                                  title-font
                                  font-semibold
                                  text-gray-900
                                  tracking-widest
                                  text-xs
                                "
                              >
                                DIRECCIÓN
                              </h2>
                              <p class="mt-1">
                                Photo booth tattooed prism, portland taiyaki
                                hoodie neutra typewriter
                              </p>
                            </div>
                            <div class="lg:w-1/2 px-6 mt-4 lg:mt-0">
                              <h2
                                class="
                                  title-font
                                  font-semibold
                                  text-gray-900
                                  tracking-widest
                                  text-xs
                                "
                              >
                                EMAIL
                              </h2>
                              <a class="text-blue-ina leading-relaxed"
                                >example@email.com</a
                              >
                              <h2
                                class="
                                  title-font
                                  font-semibold
                                  text-gray-900
                                  tracking-widest
                                  text-xs
                                  mt-4
                                "
                              >
                                TELÉFONO
                              </h2>
                              <p class="leading-relaxed">123-456-7890</p>
                            </div>
                          </div>
                        </div>
                      </div>
                    </section>
                  </li>
                  <!--
                  <li>
                    <NuxtLink
                      to="/blog"
                      aria-label="Product pricing"
                      title="Product pricing"
                      class="font-medium tracking-wide text-gray-700 transition-colors duration-200 hover:text-deep-purple-accent-400"
                      >Blog</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/contacto"
                      aria-label="About us"
                      title="About us"
                      class="
                        font-medium
                        tracking-wide
                        text-gray-700
                        transition-colors
                        duration-200
                        hover:text-deep-purple-accent-400
                      "
                      @click="showMenu"
                      >Contacto</NuxtLink
                    >
                  </li>
                  -->
                  <li>
                    <a
                      href="https://api.whatsapp.com/send?phone=524421202717&text=%C2%A1Hola!%20Deseo%20m%C3%A1s%20informaci%C3%B3n%20acerca%20de%20los%20productos%20y%20servicios%20de%20%22INA%20integraci%C3%B3n.%20y%20automatizaci%C3%B3n%22"
                      class="
                        inline-flex
                        items-center
                        justify-center
                        w-full
                        h-12
                        px-6
                        font-medium
                        tracking-wide
                        text-white
                        transition
                        duration-200
                        rounded
                        shadow-md
                        bg-blue-ina
                        hover:bg-blue-500
                        focus:shadow-outline focus:outline-none
                      "
                      aria-label="Sign up"
                      title="Sign up"
                    >
                      Whatsapp
                    </a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
          <!--Mobile menu end -->
        </div>
      </div>
    </div>
    <Nuxt />
    <div
      class="
        px-4
        mx-auto
        sm:max-w-xl
        md:max-w-full
        lg:max-w-screen-xl
        md:px-24
        lg:px-8
      "
    >
      <div class="grid gap-10 row-gap-6 mb-8 sm:grid-cols-2 lg:grid-cols-4">
        <div class="sm:col-span-2">
          <div class="mt-6 lg:max-w-sm">
            <p class="text-sm text-gray-800">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam.
            </p>
            <p class="mt-4 text-sm text-gray-800">
              Eaque ipsa quae ab illo inventore veritatis et quasi architecto
              beatae vitae dicta sunt explicabo.
            </p>
          </div>
        </div>
        <div class="space-y-2 text-sm">
          <p class="text-base font-bold tracking-wide text-gray-900">
            Contacts
          </p>
          <div class="flex">
            <p class="mr-1 text-gray-800">Teléfono:</p>
            <a
              href="tel:850-123-5021"
              aria-label="Our phone"
              title="Our phone"
              class="
                transition-colors
                duration-300
                text-blue-ina
                hover:text-blue-500
              "
              >850-123-5021</a
            >
          </div>
          <div class="flex">
            <p class="mr-1 text-gray-800">Email:</p>
            <a
              href="mailto:info@lorem.mail"
              aria-label="Our email"
              title="Our email"
              class="
                transition-colors
                duration-300
                text-blue-ina
                hover:text-blue-500
              "
              >info@lorem.mail</a
            >
          </div>
          <div class="flex">
            <p class="mr-1 text-gray-800">Dirección:</p>
            <a
              href="https://www.google.com/maps"
              target="_blank"
              rel="noopener noreferrer"
              aria-label="Our address"
              title="Our address"
              class="
                transition-colors
                duration-300
                text-blue-ina
                hover:text-blue-500
              "
            >
              312 Lovely Street, NY
            </a>
          </div>
        </div>
        <div>
          <span class="text-base font-bold tracking-wide text-gray-900"
            >Social</span
          >
          <div class="flex items-center mt-1 space-x-3">
            <a
              href="/"
              class="
                text-blue-ina
                transition-colors
                duration-300
                hover:text-blue-ina
              "
            >
              <svg viewBox="0 0 24 24" fill="currentColor" class="h-5">
                <path
                  d="M24,4.6c-0.9,0.4-1.8,0.7-2.8,0.8c1-0.6,1.8-1.6,2.2-2.7c-1,0.6-2,1-3.1,1.2c-0.9-1-2.2-1.6-3.6-1.6 c-2.7,0-4.9,2.2-4.9,4.9c0,0.4,0,0.8,0.1,1.1C7.7,8.1,4.1,6.1,1.7,3.1C1.2,3.9,1,4.7,1,5.6c0,1.7,0.9,3.2,2.2,4.1 C2.4,9.7,1.6,9.5,1,9.1c0,0,0,0,0,0.1c0,2.4,1.7,4.4,3.9,4.8c-0.4,0.1-0.8,0.2-1.3,0.2c-0.3,0-0.6,0-0.9-0.1c0.6,2,2.4,3.4,4.6,3.4 c-1.7,1.3-3.8,2.1-6.1,2.1c-0.4,0-0.8,0-1.2-0.1c2.2,1.4,4.8,2.2,7.5,2.2c9.1,0,14-7.5,14-14c0-0.2,0-0.4,0-0.6 C22.5,6.4,23.3,5.5,24,4.6z"
                ></path>
              </svg>
            </a>
            <a
              href="/"
              class="
                text-blue-ina
                transition-colors
                duration-300
                hover:text-blue-ina
              "
            >
              <svg viewBox="0 0 30 30" fill="currentColor" class="h-6">
                <circle cx="15" cy="15" r="4"></circle>
                <path
                  d="M19.999,3h-10C6.14,3,3,6.141,3,10.001v10C3,23.86,6.141,27,10.001,27h10C23.86,27,27,23.859,27,19.999v-10   C27,6.14,23.859,3,19.999,3z M15,21c-3.309,0-6-2.691-6-6s2.691-6,6-6s6,2.691,6,6S18.309,21,15,21z M22,9c-0.552,0-1-0.448-1-1   c0-0.552,0.448-1,1-1s1,0.448,1,1C23,8.552,22.552,9,22,9z"
                ></path>
              </svg>
            </a>
            <a
              href="/"
              class="
                text-blue-ina
                transition-colors
                duration-300
                hover:text-blue-ina
              "
            >
              <svg viewBox="0 0 24 24" fill="currentColor" class="h-5">
                <path
                  d="M22,0H2C0.895,0,0,0.895,0,2v20c0,1.105,0.895,2,2,2h11v-9h-3v-4h3V8.413c0-3.1,1.893-4.788,4.659-4.788 c1.325,0,2.463,0.099,2.795,0.143v3.24l-1.918,0.001c-1.504,0-1.795,0.715-1.795,1.763V11h4.44l-1,4h-3.44v9H22c1.105,0,2-0.895,2-2 V2C24,0.895,23.105,0,22,0z"
                ></path>
              </svg>
            </a>
          </div>

          <p class="mt-4 text-sm text-gray-500">
            Bacon ipsum dolor amet short ribs pig sausage prosciutto chicken
            spare ribs salami.
          </p>
        </div>
      </div>
      <section class="text-gray-600 body-font relative">
        <div class="container px-5 py-8 mx-auto flex sm:flex-nowrap flex-wrap">
          <div
            class="
              md:w-full
              bg-gray-300
              rounded-lg
              overflow-hidden
              sm:mr-10
              p-10
              flex
              items-end
              justify-start
              relative
            "
          >
            <iframe
              class="absolute inset-0"
              style="filter: contrast(1.2) opacity(0.4)"
              title="map"
              marginheight="0"
              marginwidth="0"
              scrolling="no"
              src="https://maps.google.com/maps?width=100%&height=600&hl=en&q=%C4%B0zmir+(My%20Business%20Name)&ie=UTF8&t=&z=14&iwloc=B&output=embed"
              width="100%"
              height="100%"
              frameborder="0"
            ></iframe>
            <div
              class="bg-white relative flex flex-wrap py-6 rounded shadow-md"
            >
              <div class="lg:w-1/2 px-6">
                <h2
                  class="
                    title-font
                    font-semibold
                    text-gray-900
                    tracking-widest
                    text-xs
                  "
                >
                  DIRECCIÓN
                </h2>
                <p class="mt-1">
                  Photo booth tattooed prism, portland taiyaki hoodie neutra
                  typewriter
                </p>
              </div>
              <div class="lg:w-1/2 px-6 mt-4 lg:mt-0">
                <h2
                  class="
                    title-font
                    font-semibold
                    text-gray-900
                    tracking-widest
                    text-xs
                  "
                >
                  EMAIL
                </h2>
                <a class="text-blue-ina leading-relaxed">example@email.com</a>
                <h2
                  class="
                    title-font
                    font-semibold
                    text-gray-900
                    tracking-widest
                    text-xs
                    mt-4
                  "
                >
                  TELÉFONO
                </h2>
                <p class="leading-relaxed">123-456-7890</p>
              </div>
            </div>
          </div>
        </div>
      </section>
      <div
        class="
          flex flex-col-reverse
          justify-between
          pt-5
          pb-10
          border-t
          lg:flex-row
        "
      >
        <p class="text-sm text-gray-600">
          © Copyright 2020 Lorem Inc. All rights reserved.
        </p>
        <ul
          class="
            flex flex-col
            mb-3
            space-y-2
            lg:mb-0
            sm:space-y-0 sm:space-x-5 sm:flex-row
          "
        >
          <li>
            <a
              href="/"
              class="
                text-sm text-gray-600
                transition-colors
                duration-300
                hover:text-deep-purple-accent-400
              "
              >F.A.Q</a
            >
          </li>
          <li>
            <a
              href="/"
              class="
                text-sm text-gray-600
                transition-colors
                duration-300
                hover:text-deep-purple-accent-400
              "
              >Privacy Policy</a
            >
          </li>
          <li>
            <a
              href="/"
              class="
                text-sm text-gray-600
                transition-colors
                duration-300
                hover:text-deep-purple-accent-400
              "
              >Terms &amp; Conditions</a
            >
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      show: false,
    }
  },
  watch: {
    $route() {
      this.show = false
    },
  },
  methods: {
    showMenu() {
      this.show = !this.show
    },
  },
}
</script>
