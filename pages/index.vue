<template>
  <div class="container" >
    <div >
      <logo />
      <div class="mt-10 title text-3xl sm:text-4xl md:text-5xl lg:text-5xl xl:text-6xl 
       transition duration-500 ease-in-out text-black-500 hover:text-orange-400 transform hover:-translate-y-1 hover:scale-110">
        COMING SOON2
      </div>
     
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
  @apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  color: #231f20;
  letter-spacing: 1px;
}

</style>
