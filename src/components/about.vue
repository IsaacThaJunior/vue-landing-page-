<template>
  <div class="flex justify-center bg-white/90 pb-16 md:pb-0">
    <section class="pb-24 px-4 md:px-8 pt-20">
      <div class="text-center mb-14 md:mb-28">
        <h2 class="heading-secondary font-bold inline-block text-4xl md:text-5xl uppercase transition-all">
          Explore the world with us!
        </h2>
      </div>

      <div class="flex flex-col md:flex-row">
        <div class="w-full md:w-1/2 mb-12">
          <h3 class="text-2xl md:text-2xl font-bold uppercase mb-4 text-slate-600">
            Youre going to fall in love with nature
          </h3>
          <p class="text-lg mb-8 text-emerald-700">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolor
            nulla beatae ipsum sed veniam magni fugit incidunt ducimus,
            aspernatur quasi nesciunt. Laudantium inventore reprehenderit
            cumque. Dicta quo quisquam esse voluptatum.
          </p>

          <h3 class="text-2xl md:text-2xl font-bold uppercase mb-4 text-slate-600">
            Live adventures like you never have before
          </h3>
          <p class="text-lg mb-8 text-emerald-700">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem
            delectus eligendi eos? Natus, velit dolor obcaecati eligendi cumque
            iste consequatur qui deserunt error tempore.
          </p>

          <a
            href="#"
            class="btn-text text-lg inline-block text-gray-700 no-underline border-b border-gray-700 p-2 transition-all hover:bg-green-500 hover:text-gray-800 hover:shadow-lg hover:-translate-y-2 active:shadow-md active:translate-y-0"
            >Learn more &rarr;</a
          >
        </div>
        <div class="md:w-1/2 md:pl-12">
          <div class="relative flex">
            <img
              src="../assets/vicor1.jpg"
              alt="Photo 1"
              class="w-5/12 shadow-lg absolute z-10 transition-all duration-300 outline-offset-8  hover:scale-110  hover:-translate-y-2 hover:shadow-md hover:z-20 left-0 md:left-12 md:-top-8"
            />

            <img
              src="../assets/victor2.jpg"
              alt="Photo 2"
              class="w-5/12 shadow-lg absolute md:z-10 transition-all duration-300 outline-offset-8  hover:scale-110  hover:-translate-y-2 hover:shadow-md z-30 hover:z-20 md:right-28 md:top-8 left-1/4"
            />

            <img
              src="../assets/victor3.jpg"
              alt="Photo 3"
              class="w-5/12 shadow-lg absolute z-10 transition-all duration-300 outline-offset-8  hover:scale-110  hover:-translate-y-2 hover:shadow-md hover:z-20 md:top-20 right-14"
            />
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>

.heading-secondary {
  background-image: linear-gradient(to right, #7ed56f, #28b485);
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
}
</style>
