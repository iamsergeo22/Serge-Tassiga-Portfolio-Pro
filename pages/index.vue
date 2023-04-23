<template>
  <div>
    <div class="lg:px-12 lg:mx-12 flex lg:flex-row flex-col justify-around container py-12 text-white">
      <div class="lg:w-full text-center sm:text-left">
        <div>
          <p class=" text-xl text-gray-200">Hello Friend, I am</p>
        </div>
        <div>
          <h1 class="text-white font-extrabold	 lg:text-6xl text-4xl mt-2 lg:w-3/4">Serge Anan TASSIGA</h1>
        </div>
        <p class="text-gray-200 text-xl font-200">a passionate frontend developer focused on creating interactive,
          accessible, and responsive websites.</p>

        <div class="flex gap-3 lg:w-1/2">
          <a href="#projects" class="
            flex
            justify-center
            items-center
            w-1/2
            mt-4
            mb-6
            sm:mb-0
            text-2xl
            border border-indigo-200
            dark:border-ternary-dark
            py-3
            sm:py-3
            shadow-lg
            rounded-lg
            bg-white
            hover:bg-indigo-700
            text-black
            duration-500
          " aria-label="Download Resume">
            <span class="text-sm sm:text-lg font-general-medium duration-100">See my Work</span></a>
          <a href="/RW_CV_Togo_SergeAnan_TASSIGA.pdf" class="
            flex
            justify-center
            items-center
            w-1/2
            mt-4
            mb-6
            sm:mb-0
            text-2xl
            border border-indigo-200
            dark:border-ternary-dark
            py-3
            sm:py-3
            shadow-lg
            rounded-lg
            bg-transparent
            hover:bg-indigo-700
            text-white
            hover:text-white
            duration-500
          " target="blank" aria-label="Download Resume">
            <span class="text-sm sm:text-lg font-general-medium duration-100">View Resume</span></a>
        </div>
      </div>
      <div class="sm:w-full">
        <img src="../assets/img/header.svg" alt="img" class=" shadow-white shadow-lg cursor-pointer" />
      </div>


    </div> <!-- end hero -->

    <div class="overflow-x-hidden">
      <div class="container text-xl pb-4 border-t text-xl border-gray-500 border-b  relative" id="about">
        <h1 class="text-white font-extrabold lg:text-4xl text-4xl mt-2 text-center">About Me</h1>

        <p class="text-gray-200 text-md italic mt-2 text-center font-100">You will find a little intro about me and the
          skills and technologies I use daily.</p>


        <div class="lg:px-12 flex lg:flex-row flex-col justify-between gap-8 lg:py-12 text-white">
          <div class="text-xl sm:text-xl text-justify lg:w-1/2">
            <h1 class="text-white font-extrabold lg:text-2xl text-4xl mt-2 text-left mb-4">Want to know me?</h1>
            I'm a <strong>Frontend Developer</strong> whose whole interest is building interactive, accessible, and
            responsive websites.
            My project section contains some beautiful websites I've built.

            I'm currently open to Job opportunities where I can contribute to your business and make your users happy.
            Contact me if you're interested in having a taste of my skills.

            <a href="#contact"  class="
            flex
            justify-center
            items-center
            w-1/4
            mt-4
            mb-6
            sm:mb-0
            text-3xl
            border border-indigo-200
            dark:border-ternary-dark
            py-2
            font-extrabold
            sm:py-3
            shadow-lg
            rounded-lg
            bg-white
            hover:bg-indigo-700
            text-black
            duration-500
          " aria-label="Download Resume">
            <span class="text-sm sm:text-lg font-general-medium duration-100">Contact Me</span></a>
          </div>

          <div>
            <h1 class="text-white font-extrabold lg:text-2xl text-4xl mt-2 text-left mb-4">Skills and Technologies</h1>


            <div class="text-sm sm:text-md text-justify grid grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-3">
              <span class="rounded bg-gray-800 p-2 text-center lg:w-1/2 font-extrabold shadow-2xl">HTML</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-1/2 font-extrabold shadow-2xl">CSS</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-full font-extrabold shadow-2xl">Tailwindcss</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-full font-extrabold shadow-2xl">Styled-components</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-full font-extrabold shadow-2xl">Javascript</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-1/2 font-extrabold shadow-2xl">Vue</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-1/2 font-extrabold shadow-2xl">Nuxtjs</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-1/2 font-extrabold shadow-2xl">Git</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-1/2 font-extrabold shadow-2xl">GitHub</span>
              <span class="rounded bg-gray-800 p-2 text-center lg:w-full font-extrabold shadow-2xl">WordPress</span>

            </div>
          </div>
        </div>
        <!-- <div class="responsive-container">
          <iframe class="responsive-iframe w-full h-full top-0 left-0 border-0" src="https://www.youtube.com/embed/uHo6o1TNQeE" style="border:0;" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div> -->
      </div> <!-- end get-to-know me -->
    </div>


    <div class="overflow-x-hidden">
      <div class="container mx-auto border-t border-gray-500 border-b  relative" id="projects">
        <h1 class="text-white font-extrabold lg:text-4xl text-4xl mt-2 text-center">Projects</h1>

        <p class="text-gray-200 text-md italic mt-2 text-center font-100">These are some of the projects I built to practice and get better at the technologies mentioned above.</p>


        <div class="absolute right-0" style="top: 50px; transform: translate(100%) rotate(180deg)">
          <svg width="170px" height="170px">
            <use xlink:href="#dots-triangle" /></svg>
        </div>

        <Portfolio></Portfolio>


      </div> <!-- end projects -->
    </div>



    <div class="overflow-x-hidden">
      <div class="bg-black text-black pt-16" id="contact">
        <div class="mx-auto text-xl pb-4">
          
         <contact></contact>
          
        </div>    
      </div> <!-- end contact-me -->
    </div>



  </div>
</template>
<script>
import Contact from '../components/Contact.vue'
export default {
  components: { Contact },
  data() {
    return {
      title: 'Serge Anan TASSIGA - Frontend Developer',
    }
  }
}

</script>

<style>

</style>
