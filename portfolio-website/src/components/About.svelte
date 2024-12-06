<script>
  let benefits = [
    {
      metric: "10x",
      name: "a self taught developer",
      description:
        "I taught myself to code using free online resources and absolutely fell in love with the creativity and problem solving that is involved in developing and engineering innovative new online experiences. Starting of with JavaScript, HTML & CSS and evolving my knowledge base to include JavaScript frameworks, backend programming, design, cloud services and much much more.",
    },
    {
      name: "a product design & UX finatic",
      description:
        "Carefully crafting and designing amazing user experiences allows me to express and experiment with every morsel of creativity I have. I love the challenge of learning new design concepts and enabling users with amazing online experiences.",
    },
    {
      name: "an excellent communicator",
      description:
        "Communication is key and it's a paramount value of mine. I believe in transparency and constructive communication above all else. This helps me develop deep relationships and ensures my effectiveness and productivity in any work space with any team.",
    },
  ];
</script>

<section
  id="about"
  class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
>
  <div
    class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
  >
    <h6 class="text-large sm:text-xl md:text-2xl">Want to know more?</h6>
    <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
      A bit <span class="poppins text-violet-400">about</span> me.
    </h3>
  </div>
  <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
    I am . . .
  </p>
  <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
    {#each benefits as benefit, index}
      <div class="flex gap-6 sm:gap-8">
        <p
          class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
        >
          0{index + 1}
        </p>
        <div class="flex flex-col gap-6 sm:gap-8">
          <h3 class="text-2xl sm:text-3xl md:text-5xl">
            {benefit.name}
          </h3>
          <p>{benefit.description}</p>
        </div>
      </div>
    {/each}
  </div>
</section>
