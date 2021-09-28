<template>
  <div>
    <!-- Section 1 -->
    <section class="px-2 pt-12 md:px-0">
      <div
        class="
          container
          items-center
          max-w-6xl
          px-5
          mx-auto
          space-y-6
          text-center
        "
      >
        <h1
          class="
            text-6xl
            font-extra
            bold
            tracking-tight
            text-left text-gray-900
            sm:text-5xl
            md:text-6xl md:text-center
          "
        >
          <span class="block text-blue-ina font-bold"
            >La mejor integración, con lo mejor
          </span>
        </h1>
        <p
          class="
            w-full
            mx-auto
            text-base text-left text-gray-500 text-2xl
            md:max-w-md md:max-w-3xl md:text-center
          "
        >
          Tecnología a tu servicio que te brindará seguridad y comfort
        </p>
        <div
          class="mx-auto flex flex-col justify-center md:flex-row md:space-x-4"
        >
          <a
            href="tel:+524421202717"
            class="
              w-40
              flex
              items-center
              px-6
              py-3
              mb-3
              text-xl text-white
              bg-blue-ina
              hover:text-bg-deep-purple-accent-400
              rounded-md
              md:mb-0
              hover:bg-blue-500
              md:w-auto
            "
          >
            Llámanos
            <font-awesome-icon :icon="['fas', 'phone']" class="ml-2" />
          </a>
        </div>
      </div>
      <div class="container items-center max-w-4xl px-5 mx-auto text-center">
        <nuxt-img src="/img/iot.png" />
      </div>
    </section>

    <div
      class="
        px-4
        py-24
        mx-auto
        sm:max-w-xl
        md:max-w-full
        lg:max-w-screen-xl
        md:px-24
        lg:px-8 lg:py-20
      "
    >
      <div class="grid gap-10 lg:grid-cols-2">
        <div class="flex flex-col justify-center md:pr-8 xl:pr-0 lg:max-w-lg">
          <div class="max-w-xl mb-6">
            <h2
              class="
                max-w-lg
                mb-6
                font-sans
                text-3xl
                font-medium
                tracking-tight
                text-gray-900
                font-bold
                sm:text-4xl sm:leading-none
              "
            >
              Integramos<br class="hidden md:block" />
              tu siguiente
              <span class="inline-block text-blue-ina"
                >casa, industria o residencia</span
              >
            </h2>
            <p class="text-base text-gray-700 md:text-lg">
              Gracias a nuestra experiencia con diferentes sistemas e
              instalaciones, te garantizamos un sistema robusto, hecho con las
              mejores prácticas al filo de la tecnología.
            </p>
          </div>
          <div>
            <NuxtLink
              to="/nosotros"
              aria-label=""
              class="
                inline-flex
                items-center
                font-semibold
                transition-colors
                duration-200
                text-blue-ina
                hover:text-blue-500
              "
            >
              Conoce más
              <svg
                class="inline-block w-3 ml-2"
                fill="currentColor"
                viewBox="0 0 12 12"
              >
                <path
                  d="M9.707,5.293l-5-5A1,1,0,0,0,3.293,1.707L7.586,6,3.293,10.293a1,1,0,1,0,1.414,1.414l5-5A1,1,0,0,0,9.707,5.293Z"
                ></path>
              </svg>
            </NuxtLink>
          </div>
        </div>
        <div class="flex items-center justify-center -mx-4 lg:pl-8">
          <div class="flex flex-col items-end px-3">
            <img
              class="
                object-cover
                mb-6
                rounded
                shadow-lg
                h-28
                sm:h-48
                xl:h-56
                w-28
                sm:w-48
                xl:w-56
              "
              src="https://images.pexels.com/photos/3184287/pexels-photo-3184287.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
              alt=""
            />
            <img
              class="
                object-cover
                w-20
                h-20
                rounded
                shadow-lg
                sm:h-32
                xl:h-40
                sm:w-32
                xl:w-40
              "
              src="https://images.pexels.com/photos/3182812/pexels-photo-3182812.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
              alt=""
            />
          </div>
          <div class="px-3">
            <img
              class="
                object-cover
                w-40
                h-40
                rounded
                shadow-lg
                sm:h-64
                xl:h-80
                sm:w-64
                xl:w-80
              "
              src="https://images.pexels.com/photos/3182739/pexels-photo-3182739.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;w=500"
              alt=""
            />
          </div>
        </div>
      </div>
    </div>

    <!-- Section 1 -->
    <section class="my-12">
      <div class="max-w-screen-xl px-4 py-12 mx-auto sm:px-6 lg:px-8">
        <div class="grid grid-cols-2 gap-8 md:grid-cols-6 lg:grid-cols-5">
          <div
            class="
              flex
              items-center
              justify-center
              col-span-1
              md:col-span-2
              lg:col-span-1
            "
          >
            <nuxt-img src="/svg/hikvision-logo.svg" />
          </div>
          <div
            class="
              flex
              items-center
              justify-center
              col-span-1
              md:col-span-2
              lg:col-span-1
            "
          >
            <nuxt-img class="w-1/2" src="/svg/came.svg" />
          </div>
          <div
            class="
              flex
              items-center
              justify-center
              col-span-1
              md:col-span-2
              lg:col-span-1
            "
          >
            <nuxt-img class="w-1/2" src="/svg/rbh.svg" />
          </div>
          <div
            class="
              flex
              items-center
              justify-center
              col-span-1
              md:col-span-3
              lg:col-span-1
            "
          >
            <svg
              id="svg70"
              enable-background="new 0 0 2489.7 441"
              viewBox="0 0 2489.7 441"
              version="1.1"
              sodipodi:docname="honeywell-logo.svg"
              inkscape:version="1.1.1 (3bf5ae0d25, 2021-09-20)"
              xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
              xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
              xmlns="http://www.w3.org/2000/svg"
              xmlns:svg="http://www.w3.org/2000/svg"
            >
              <defs id="defs74" />
              <sodipodi:namedview
                id="namedview72"
                pagecolor="#ffffff"
                bordercolor="#666666"
                borderopacity="1.0"
                inkscape:pageshadow="2"
                inkscape:pageopacity="0.0"
                inkscape:pagecheckerboard="0"
                showgrid="false"
                inkscape:zoom="0.18588641"
                inkscape:cx="1256.1435"
                inkscape:cy="255.5324"
                inkscape:window-width="1600"
                inkscape:window-height="835"
                inkscape:window-x="0"
                inkscape:window-y="32"
                inkscape:window-maximized="1"
                inkscape:current-layer="svg70"
              />
              <g id="g68" fill="#de1e34" style="fill: #2563eb; fill-opacity: 1">
                <path
                  id="path64"
                  d="m2256 336.6h94.6v-336.6h-94.6zm233.7-336.6v336.6h-94.6v-336.6zm-2288 130.7h-76.5v-130.7h-125.2v336.6h125.2v-166.9h76.5v166.9h125.2v-336.6h-125.2zm587.6-5.5-7.7-22.2h-102.9v233.7h102.9v-140.6c0-30.6 19.5-47.3 36.2-47.3 13.9 0 32 2.8 32 33.4v154.4h102.9v-151.6c0-84.9-95.2-118.2-163.4-59.8zm1057.1 113.3-48-135.6h-70.2l-48 141.2-50.1-141.2h-137.7l-49.4 118.9-69.5-118.9h-117.5l138.4 236.5-18.1 44.5c-6.3 13.9-21.3 14.6-24.2 1.4 0-23.9-19.4-43.3-43.3-43.3s-43.3 19.4-43.3 43.3c.2 25 25.2 57.7 74.6 55.6s70.2-43.1 77.2-60.5l114.4-276.6 82.4 232.8h75.1l45.9-134.2 47.3 134.2h70.9l80-233.7h-41zm-1342.2-147.5c-78.8 0-142.6 58.6-142.6 130.8 0 72.3 63.8 130.8 142.6 130.8s142.6-58.6 142.6-130.8-63.8-130.8-142.6-130.8zm35.5 192c0 19.6-15.9 35.5-35.5 35.5-19.6 0-35.5-15.9-35.5-35.5v-122.3c0-19.6 15.9-35.5 35.5-35.5s35.5 15.9 35.5 35.4z"
                  style="fill: #2563eb; fill-opacity: 1"
                />
                <path
                  id="path66"
                  d="m1267.4 240.6c.7-5.5 1.1-13.1 1.1-18.8 0-72.2-63.8-130.8-142.6-130.8s-142.6 58.6-142.6 130.8c0 72.3 63.8 130.8 142.6 130.8 54.1 0 101.2-27.7 125.4-68.4l-31.5-11.7c-19 29.1-53.9 48.6-93.9 48.6-19.6 0-35.5-18.5-35.5-38.1v-42.4zm-176.9-79.9c0-19.6 15.9-35.4 35.5-35.4s35.5 15.9 35.5 35.4v46.6h-70.9v-46.6zm1129.6 79.9c.8-5.5 1.2-13.1 1.2-18.8 0-72.2-63.8-130.8-142.6-130.8s-142.6 58.6-142.6 130.8c0 72.3 63.8 130.8 142.6 130.8 54.1 0 101.2-27.7 125.4-68.4l-31.5-11.7c-19 29.1-53.9 48.6-93.9 48.6-19.6 0-35.5-18.5-35.5-38.1v-42.4zm-176.9-79.9c0-19.6 15.9-35.4 35.5-35.4s35.5 15.9 35.5 35.4v46.6h-70.9z"
                  style="fill: #2563eb; fill-opacity: 1"
                />
              </g>
            </svg>
          </div>
          <div
            class="
              flex
              items-center
              justify-center
              col-span-2
              md:col-span-3
              lg:col-span-1
            "
          >
            <nuxt-img src="/svg/Insteon.png" />
          </div>
        </div>
      </div>
    </section>

    <section class="text-gray-600 body-font">
      <div class="container px-5 pt-24 md:pt-8 mx-auto">
        <div class="flex flex-col text-center w-full mb-12">
          <h1 class="text-4xl font-medium mb-4 text-gray-900 text-blue-ina">
            Los mejores productos, servicios e instalaciones
          </h1>
          <p class="lg:w-2/3 mx-auto leading-relaxed text-base">
            Te mantenemos al tanto de la tecnología y garantizamos un excelente
            funcionamiento gracias a nuestras buenas prácticas.
          </p>
        </div>
      </div>
    </section>

    <Content />

    <section>
      <div
        class="
          px-4
          py-16
          mx-auto
          sm:max-w-xl
          md:max-w-full
          lg:max-w-screen-xl
          md:px-24
          lg:px-8 lg:py-20
        "
      >
        <div class="grid gap-5 row-gap-8 lg:grid-cols-2">
          <div class="flex flex-col justify-center">
            <div class="max-w-xl mb-6">
              <h2
                class="
                  max-w-lg
                  mb-6
                  font-sans
                  text-3xl
                  font-bold
                  tracking-tight
                  text-gray-900
                  sm:text-4xl sm:leading-none
                "
              >
                <br class="hidden md:block" />
                Tranquilo, tenemos lo mejor para tu
                <span class="relative px-1">
                  <div
                    class="
                      absolute
                      inset-x-0
                      bottom-0
                      h-3
                      transform
                      -skew-x-12
                      bg-blue-100
                    "
                  ></div>
                  <span class="relative inline-block text-blue-ina"
                    >seguridad y confort</span
                  >
                </span>
              </h2>
              <p class="text-base text-gray-700 md:text-lg">
                Nosotros nos encargamos de hacer las instalaciones especiales o
                regulares que sean necesarias para que tú disfrutes más del
                tiempo y tranquiladad que nuestros servicios te brindarán.
              </p>
            </div>
            <div class="grid gap-5 row-gap-8 sm:grid-cols-2">
              <div class="bg-white border-l-4 shadow-sm border-blue-ina">
                <div class="h-full p-5 border border-l-0 rounded-r">
                  <h6 class="mb-2 font-semibold leading-5">
                    Seguridad, la más alta
                  </h6>
                  <p class="text-sm text-gray-900">
                    La seguridad es algo muy serio para nosotros, por ello te
                    ofreceremos la mejor solución bajo el criterio de expertos.
                  </p>
                </div>
              </div>
              <div class="bg-white border-l-4 shadow-sm border-blue-ina">
                <div class="h-full p-5 border border-l-0 rounded-r">
                  <h6 class="mb-2 font-semibold leading-5">
                    Confort, en casa y oficina
                  </h6>
                  <p class="text-sm text-gray-900">
                    Aumente su comodidad en casa e incremente su productividad
                    en la oficina con una de las soluciones que tenemos para tí.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div>
            <img
              class="object-cover w-full h-56 rounded shadow-lg sm:h-96"
              src="https://images.pexels.com/photos/927022/pexels-photo-927022.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=3&amp;h=750&amp;w=1260"
              alt=""
            />
          </div>
        </div>
      </div>
    </section>
    <MexMap />
  </div>
</template>
