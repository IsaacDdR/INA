<template>
  <div
    class="
      relative
      px-4
      pb-16
      mx-auto
      sm:max-w-xl
      md:max-w-full
      lg:max-w-screen-xl
      md:px-24
      lg:px-8 lg:py-20
    "
  >
    <div
      class="
        absolute
        inset-x-0
        top-0
        items-center
        justify-center
        hidden
        overflow-hidden
        md:flex md:inset-y-0
      "
    >
      <svg viewBox="0 0 88 88" class="w-full max-w-screen-xl text-blue-100">
        <circle fill="currentColor" cx="44" cy="44" r="15.5"></circle>
        <circle
          fill-opacity="0.2"
          fill="currentColor"
          cx="44"
          cy="44"
          r="44"
        ></circle>
        <circle
          fill-opacity="0.2"
          fill="currentColor"
          cx="44"
          cy="44"
          r="37.5"
        ></circle>
        <circle
          fill-opacity="0.3"
          fill="currentColor"
          cx="44"
          cy="44"
          r="29.5"
        ></circle>
        <circle
          fill-opacity="0.3"
          fill="currentColor"
          cx="44"
          cy="44"
          r="22.5"
        ></circle>
      </svg>
    </div>
    <div class="relative grid gap-5 sm:grid-cols-2 lg:grid-cols-4">
      <div
        class="
          flex flex-col
          justify-between
          overflow-hidden
          text-left
          transition-shadow
          duration-200
          bg-white
          rounded
          shadow-xl
          group
          hover:shadow-2xl
        "
      >
        <div class="p-5">
          <div
            class="
              flex
              items-center
              justify-center
              w-10
              h-10
              mb-4
              rounded-full
              bg-blue-50
              text-blue-ina
            "
          >
            <font-awesome-icon :icon="['fas', 'camera']" />
          </div>
          <p class="mb-2 font-bold">Sistema de CCTV</p>
          <p class="text-sm leading-5 text-gray-900">
            Mantenga su perìmetro e interiores vigilados aunque no este en
            sitio.
          </p>
        </div>
        <div
          class="
            w-full
            h-1
            ml-auto
            duration-300
            origin-left
            transform
            scale-x-0
            bg-blue-ina
            group-hover:scale-x-100
          "
        ></div>
      </div>
      <div
        class="
          flex flex-col
          justify-between
          overflow-hidden
          text-left
          transition-shadow
          duration-200
          bg-white
          rounded
          shadow-xl
          group
          hover:shadow-2xl
        "
      >
        <div class="p-5">
          <div
            class="
              flex
              items-center
              justify-center
              w-10
              h-10
              mb-4
              rounded-full
              bg-blue-50
              text-blue-ina
            "
          >
            <font-awesome-icon :icon="['fas', 'network-wired']" />
          </div>
          <p class="mb-2 font-bold">Cableado estructurado</p>
          <p class="text-sm leading-5 text-gray-900">
            Oragnizamos tu red para una mayor eficiencia en su mantenimiento y
            mejor imagen.
          </p>
        </div>
        <div
          class="
            w-full
            h-1
            ml-auto
            duration-300
            origin-left
            transform
            scale-x-0
            bg-blue-ina
            group-hover:scale-x-100
          "
        ></div>
      </div>
      <div
        class="
          flex flex-col
          justify-between
          overflow-hidden
          text-left
          transition-shadow
          duration-200
          bg-white
          rounded
          shadow-xl
          group
          hover:shadow-2xl
        "
      >
        <div class="p-5">
          <div
            class="
              flex
              items-center
              justify-center
              w-10
              h-10
              mb-4
              rounded-full
              bg-blue-50
              text-blue-ina
            "
          >
            <font-awesome-icon :icon="['fas', 'fire']" />
          </div>
          <p class="mb-2 font-bold">Detección de fuegos</p>
          <p class="text-sm leading-5 text-gray-900">
            Detecte a tiempo en su residencia, edificio o comercio fuego y
            prevea daños.
          </p>
        </div>
        <div
          class="
            w-full
            h-1
            ml-auto
            duration-300
            origin-left
            transform
            scale-x-0
            bg-blue-ina
            group-hover:scale-x-100
          "
        ></div>
      </div>
      <div
        class="
          flex flex-col
          justify-between
          overflow-hidden
          text-left
          transition-shadow
          duration-200
          bg-white
          rounded
          shadow-xl
          group
          hover:shadow-2xl
        "
      >
        <div class="p-5">
          <div
            class="
              flex
              items-center
              justify-center
              w-10
              h-10
              mb-4
              rounded-full
              bg-blue-50
              text-blue-ina
            "
          >
            <font-awesome-icon :icon="['fas', 'border-style']" />
          </div>
          <p class="mb-2 font-bold">Protección perimetral</p>
          <p class="text-sm leading-5 text-gray-900">
            Mantenga el perímetro de su casa, edificio o negocio protegido con
            cercas eléctricas, cables sensoriales perimetrales subterráneos y
            aéreos.
          </p>
        </div>
        <div
          class="
            w-full
            h-1
            ml-auto
            duration-300
            origin-left
            transform
            scale-x-0
            bg-blue-ina
            group-hover:scale-x-100
          "
        ></div>
      </div>
      <div
        class="
          flex flex-col
          justify-between
          overflow-hidden
          text-left
          transition-shadow
          duration-200
          bg-white
          rounded
          shadow-xl
          group
          hover:shadow-2xl
        "
      >
        <div class="p-5">
          <div
            class="
              flex
              items-center
              justify-center
              w-10
              h-10
              mb-4
              rounded-full
              bg-blue-50
              text-blue-ina
            "
          >
            <font-awesome-icon :icon="['fas', 'walking']" />
          </div>
          <p class="mb-2 font-bold">Control de acceso peatonal</p>
          <p class="text-sm leading-5 text-gray-900">
            Controle y gestione su residencia, negocio o edificio con barreras
            vehiculares, puertas automatizadas e instalaciones especiales.
          </p>
        </div>
        <div
          class="
            w-full
            h-1
            ml-auto
            duration-300
            origin-left
            transform
            scale-x-0
            bg-blue-ina
            group-hover:scale-x-100
          "
        ></div>
      </div>
      <div
        class="
          flex flex-col
          justify-between
          overflow-hidden
          text-left
          transition-shadow
          duration-200
          bg-white
          rounded
          shadow-xl
          group
          hover:shadow-2xl
        "
      >
        <div class="p-5">
          <div
            class="
              flex
              items-center
              justify-center
              w-10
              h-10
              mb-4
              rounded-full
              bg-blue-50
              text-blue-ina
            "
          >
            <font-awesome-icon :icon="['fas', 'car']" />
          </div>
          <p class="mb-2 font-bold">Control de acesso vehicular</p>
          <p class="text-sm leading-5 text-gray-900">
            Manten el flujo y el control de tus vehículos en tu industria,
            negocio y residencia al igual que mejorar los tiempos de espera.
          </p>
        </div>
        <div
          class="
            w-full
            h-1
            ml-auto
            duration-300
            origin-left
            transform
            scale-x-0
            bg-blue-ina
            group-hover:scale-x-100
          "
        ></div>
      </div>
      <div
        class="
          flex flex-col
          justify-between
          overflow-hidden
          text-left
          transition-shadow
          duration-200
          bg-white
          rounded
          shadow-xl
          group
          hover:shadow-2xl
        "
      >
        <div class="p-5">
          <div
            class="
              flex
              items-center
              justify-center
              w-10
              h-10
              mb-4
              rounded-full
              bg-blue-50
              text-blue-ina
            "
          >
            <font-awesome-icon :icon="['fas', 'fingerprint']" />
          </div>
          <p class="mb-2 font-bold">Control de acceso biométrico</p>
          <p class="text-sm leading-5 text-gray-900">
            Controle el acceso con datos biométricos en su casa, negocio,
            fraccionamiento y más.
          </p>
        </div>
        <div
          class="
            w-full
            h-1
            ml-auto
            duration-300
            origin-left
            transform
            scale-x-0
            bg-blue-ina
            group-hover:scale-x-100
          "
        ></div>
      </div>
      <div
        class="
          flex flex-col
          justify-between
          overflow-hidden
          text-left
          transition-shadow
          duration-200
          bg-white
          rounded
          shadow-xl
          group
          hover:shadow-2xl
        "
      >
        <div class="p-5">
          <div
            class="
              flex
              items-center
              justify-center
              w-10
              h-10
              mb-4
              rounded-full
              bg-blue-50
              text-blue-ina
            "
          >
            <font-awesome-icon :icon="['fas', 'home']" />
          </div>
          <p class="mb-2 font-bold">Casas Inteligentes</p>
          <p class="text-sm leading-5 text-gray-900">
            Agregue audio, iluminación, vídeo, alamrmas, cerraduras, puertas
            atomatizadas y más.
          </p>
        </div>
        <div
          class="
            w-full
            h-1
            ml-auto
            duration-300
            origin-left
            transform
            scale-x-0
            bg-blue-ina
            group-hover:scale-x-100
          "
        ></div>
      </div>
    </div>
  </div>
</template>
