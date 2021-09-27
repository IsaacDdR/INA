<template>
  <div>
    <div
      class="relative flex flex-col-reverse py-16 lg:pt-0 lg:flex-col lg:pb-0"
    >
      <div
        class="
          inset-y-0
          top-0
          right-0
          z-0
          w-full
          max-w-xl
          px-4
          mx-auto
          md:px-0
          lg:pr-0 lg:mb-0 lg:mx-0 lg:w-7/12 lg:max-w-full lg:absolute
          xl:px-0
        "
      >
        <svg
          class="
            absolute
            left-0
            hidden
            h-full
            text-blue-100
            transform
            -translate-x-1/2
            lg:block
          "
          viewBox="0 0 100 100"
          fill="currentColor"
          preserveAspectRatio="none slice"
        >
          <path d="M50 0H100L50 100H0L50 0Z"></path>
        </svg>
        <img
          class="
            object-cover
            w-full
            h-56
            rounded
            shadow-lg
            lg:rounded-none lg:shadow-none
            md:h-96
            lg:h-full
          "
          src="https://images.pexels.com/photos/3184291/pexels-photo-3184291.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;h=750&amp;w=1260"
          alt=""
        />
      </div>
      <div
        class="
          relative
          flex flex-col
          items-start
          w-full
          max-w-xl
          px-4
          mx-auto
          md:px-0
          lg:px-8 lg:max-w-screen-xl
        "
      >
        <div class="mb-16 lg:my-40 lg:max-w-lg lg:pr-5">
          <h2
            class="
              mb-5
              font-sans
              text-3xl
              font-bold
              tracking-tight
              text-gray-900
              sm:text-4xl sm:leading-none
            "
          >
            Creamos entornos<br class="hidden md:block" />

            <span class="inline-block text-blue-ina">seguros y prácticos</span>
          </h2>
          <p class="pr-5 mb-5 text-base text-gray-700 md:text-lg">
            Sed ut perspiciatis unde omnis iste natus error sit voluptatem
            accusantium doloremque laudantium, totam rem aperiam, eaque ipsa
            quae. explicabo.
          </p>
          <div class="flex items-center">
            <a
              href="/"
              class="
                inline-flex
                items-center
                justify-center
                h-12
                px-6
                mr-6
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
            >
              Llámanos
              <font-awesome-icon :icon="['fas', 'phone']" class="ml-2" />
            </a>
          </div>
        </div>
      </div>
    </div>
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
      <div
        class="max-w-xl mb-10 md:mx-auto sm:text-center lg:max-w-2xl md:mb-12"
      >
        <div></div>
        <h2
          class="
            max-w-lg
            mb-6
            font-sans
            text-3xl
            font-bold
            leading-none
            tracking-tight
            text-gray-900
            sm:text-4xl
            md:mx-auto
          "
        >
          <span class="relative inline-block">
            <svg
              viewBox="0 0 52 24"
              fill="currentColor"
              class="
                absolute
                top-0
                left-0
                z-0
                hidden
                w-32
                -mt-8
                -ml-20
                text-blue-gray-100
                lg:w-32 lg:-ml-28 lg:-mt-10
                sm:block
              "
            >
              <defs>
                <pattern
                  id="f51618fb-0edb-4bcb-b35a-ffc770941286"
                  x="0"
                  y="0"
                  width=".135"
                  height=".30"
                >
                  <circle cx="1" cy="1" r=".7"></circle>
                </pattern>
              </defs>
              <rect
                fill="url(#f51618fb-0edb-4bcb-b35a-ffc770941286)"
                width="52"
                height="24"
              ></rect>
            </svg>
            <span class="relative font-bold">Procesamos, planeamos</span>
          </span>
          y <span class="text-blue-ina font-bold">actuamos</span>
        </h2>
        <p class="text-base text-gray-700 md:text-lg">
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque rem aperiam, eaque ipsa quae.
        </p>
      </div>
      <div class="grid gap-8 row-gap-0 lg:grid-cols-3">
        <div class="relative text-center">
          <div
            class="
              flex
              items-center
              justify-center
              w-16
              h-16
              mx-auto
              mb-4
              rounded-full
              sm:w-20 sm:h-20
              text-blue-ina
              bg-blue-100
            "
          >
            <font-awesome-icon class="text-2xl" :icon="['fas', 'phone']" />
          </div>
          <h6 class="mb-2 text-2xl font-extrabold">Step 1</h6>
          <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
            Contáctanos por cualquiera de nuestros medios, explícanos tus
            necesidades te escucharemos y te ofreceremos una solución
          </p>
          <a
            href="/"
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
            >Learn more</a
          >
          <div
            class="
              top-0
              right-0
              flex
              items-center
              justify-center
              h-24
              lg:-mr-8 lg:absolute
            "
          >
            <svg
              class="w-8 text-gray-700 transform rotate-90 lg:rotate-0"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              viewBox="0 0 24 24"
            >
              <line
                fill="none"
                stroke-miterlimit="10"
                x1="2"
                y1="12"
                x2="22"
                y2="12"
              ></line>
              <polyline
                fill="none"
                stroke-miterlimit="10"
                points="15,5 22,12 15,19 "
              ></polyline>
            </svg>
          </div>
        </div>
        <div class="relative text-center">
          <div
            class="
              flex
              items-center
              justify-center
              w-16
              h-16
              mx-auto
              mb-4
              rounded-full
              bg-blue-100
              sm:w-20 sm:h-20
            "
          >
            <svg
              class="w-12 h-12 text-blue-ina sm:w-16 sm:h-16"
              stroke="currentColor"
              viewBox="0 0 52 52"
            >
              <polygon
                stroke-width="3"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"
                points="29 13 14 29 25 29 23 39 38 23 27 23"
              ></polygon>
            </svg>
          </div>
          <h6 class="mb-2 text-2xl font-extrabold">Step 2</h6>
          <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
            They urge you to put down your sword and come join the winners. In
            22 years the only 'winners'
          </p>
          <a
            href="/"
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
            >Learn more</a
          >
          <div
            class="
              top-0
              right-0
              flex
              items-center
              justify-center
              h-24
              lg:-mr-8 lg:absolute
            "
          >
            <svg
              class="w-8 text-gray-700 transform rotate-90 lg:rotate-0"
              stroke="currentColor"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              viewBox="0 0 24 24"
            >
              <line
                fill="none"
                stroke-miterlimit="10"
                x1="2"
                y1="12"
                x2="22"
                y2="12"
              ></line>
              <polyline
                fill="none"
                stroke-miterlimit="10"
                points="15,5 22,12 15,19 "
              ></polyline>
            </svg>
          </div>
        </div>
        <div class="relative text-center">
          <div
            class="
              flex
              items-center
              justify-center
              w-16
              h-16
              mx-auto
              mb-4
              rounded-full
              bg-blue-100
              sm:w-20 sm:h-20
            "
          >
            <svg
              class="w-12 h-12 text-blue-ina sm:w-16 sm:h-16"
              stroke="currentColor"
              viewBox="0 0 52 52"
            >
              <polygon
                stroke-width="3"
                stroke-linecap="round"
                stroke-linejoin="round"
                fill="none"
                points="29 13 14 29 25 29 23 39 38 23 27 23"
              ></polygon>
            </svg>
          </div>
          <h6 class="mb-2 text-2xl font-extrabold">Step 3</h6>
          <p class="max-w-md mb-3 text-sm text-gray-900 sm:mx-auto">
            Tell them I hate them. Is the Space Pope reptilian!? Tell her she
            looks thin. Hello, little man
          </p>
          <a
            href="/"
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
            >Learn more</a
          >
        </div>
      </div>
    </div>

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
              Innovative analytics<br class="hidden md:block" />
              that you
              <span class="inline-block text-blue-ina">will love</span>
            </h2>
            <p class="text-base text-gray-700 md:text-lg">
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem
              accusantium doloremque laudantium, totam rem aperiam, eaque ipsa
              quae. explicabo.
            </p>
          </div>
          <a
            href="/"
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
            Learn more
            <svg
              class="inline-block w-3 ml-2"
              fill="currentColor"
              viewBox="0 0 12 12"
            >
              <path
                d="M9.707,5.293l-5-5A1,1,0,0,0,3.293,1.707L7.586,6,3.293,10.293a1,1,0,1,0,1.414,1.414l5-5A1,1,0,0,0,9.707,5.293Z"
              ></path>
            </svg>
          </a>
        </div>
        <div class="relative">
          <svg
            class="absolute w-full text-blue-100"
            fill="currentColor"
            viewBox="0 0 600 392"
          >
            <rect x="0" y="211" width="75" height="181" rx="8"></rect>
            <rect x="525" y="260" width="75" height="132" rx="8"></rect>
            <rect x="105" y="83" width="75" height="309" rx="8"></rect>
            <rect x="210" y="155" width="75" height="237" rx="8"></rect>
            <rect x="420" y="129" width="75" height="263" rx="8"></rect>
            <rect x="315" y="0" width="75" height="392" rx="8"></rect>
          </svg>
          <svg
            class="relative w-full text-blue-ina"
            fill="currentColor"
            viewBox="0 0 600 392"
          >
            <rect x="0" y="311" width="75" height="81" rx="8"></rect>
            <rect x="525" y="351" width="75" height="41" rx="8"></rect>
            <rect x="105" y="176" width="75" height="216" rx="8"></rect>
            <rect x="210" y="237" width="75" height="155" rx="8"></rect>
            <rect x="420" y="205" width="75" height="187" rx="8"></rect>
            <rect x="315" y="83" width="75" height="309" rx="8"></rect>
          </svg>
        </div>
      </div>
    </div>
  </div>
</template>
