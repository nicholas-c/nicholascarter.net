<template>
  <section class="intro ">
    <div class="h-screen  flex  items-center  relative">
      <div class="container-sm">
        <h1 class="text-5xl  font-thin  text-white  tracking-wide">
          Hi, I'm Nick. I build frontend websites and applications.
        </h1>

        <a class="text-xl  font-thin  text-grey-lighter  absolute  pin-bottom">
          Learn more about what I do<br />
          <svg class="fill-current  w-10  h-10" width="1792" height="1792" viewBox="0 0 1792 1792" xmlns="http://www.w3.org/2000/svg"><path d="M1395 736q0 13-10 23l-466 466q-10 10-23 10t-23-10l-466-466q-10-10-10-23t10-23l50-50q10-10 23-10t23 10l393 393 393-393q10-10 23-10t23 10l50 50q10 10 10 23z"/></svg>
        </a>
      </div>
    </div>
  </section>
</template>

<style scoped>
.intro {
  background: #003973;
  background: linear-gradient(45deg, #E5E5BE, #003973);
}

.pin-bottom {
  bottom: 1rem;
  left: 50%;

  transform: translateX(-50%);
}
</style>
