<template>
  <div class="bg-blue-lighter  py-16">
    <div class="container-lg  flex  flex-wrap">
      <h2 class="w-full  text-5xl  leading-tight  tracking-wide">
        Latest work
      </h2>

      <p class="text-sm  text-grey-dark  py-0  md:px-32  mb-10">
        Note: Most, if not all of these projects have been done while working in an agency and a team so full credit cannot be taken. Contact me so we can talk about what I worked on exactly.
      </p>

      <div class="w-1/3  px-4">
        <a href="#" class="work-item">
          <div class="work-item__content  absolute">
            <h4 class="text-white  text-3xl  leading-tight  tracking-wide">Hermes</h4>
            <h5 class="text-grey-light">McCann Central</h5>
          </div>
        </a>
      </div>

      <div class="w-1/3  px-4">
        <a href="#" class="work-item">
          <div class="work-item__content  absolute">
            <h4 class="text-white  text-3xl  leading-tight  tracking-wide">JCB</h4>
            <h5 class="text-grey-light">McCann Central</h5>
          </div>
        </a>
      </div>

      <div class="w-1/3  px-4">
        <a href="#" class="work-item">
          <div class="work-item__content  absolute">
            <h4 class="text-white  text-3xl  leading-tight  tracking-wide">Crown Paints</h4>
            <h5 class="text-grey-light">McCann Central</h5>
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
@tailwind preflight;

.work-item {
  @apply .relative .block;
  width: 100%;
  height: 0;
  padding-bottom: 100%;

  &__content {
    top: 50%;
    left: 50%;
    z-index: 4;

    transform: translate(-50%, -50%);
  }

  &:after {
    content: '';
    @apply .absolute .pin .opacity-50 .bg-blue;
    z-index: 3;
  }
}

@tailwind utilities;
</style>
