<template>

  <q-img
    :src="source"
    :ratio="16/9"
    fit="cover"
    height="600px"
    class="flex flex-center"
  >

    <div class="row bg-transparent full-width">
      <div class="text-center text-grey-1 text-h4 text-weight-bolder col-12 full-width q-mt-lg">{{grandTitre}}</div>
      <div class="text-grey text-center col-12 text-h6 q-my-xs"> {{ sousTitre }}</div>
      <div class="flex full-width flex-center text-subtitle1">

        <q-btn class="hover-underline-animation q-mr-xl text-grey-3" flat >
          <div>{{titreBouton1}}</div>
          <q-icon size="15px" class="text-green q-ml-xs" name="fa-solid fa-chevron-right" />
        </q-btn>

        <q-btn class="hover-underline-animation text-grey-3" flat>
          <div>{{titreBouton2}}</div>
          <q-icon size="15px" class="text-green q-ml-xs" name="fa-solid fa-chevron-right" />
        </q-btn>

      </div>
    </div>

  </q-img>

</template>

<script setup>
  defineProps({
    source: String,
    grandTitre: String,
    sousTitre: String,
    titreBouton1: String,
    titreBouton2: String,
  })
</script>

<style lang="scss">

  .q-btn--flat {
    display: inline-block !important;
    position: relative !important;
  }

  .q-btn--flat::after {
    content: '' !important;
    position: absolute !important;
    width: 100% !important;
    transform: scaleX(0) !important;
    height: 2px !important;
    bottom: 0 !important;
    left: 0 !important;
    background-color: green !important;
    transform-origin: bottom right !important;
    transition: transform 0.25s ease-out !important;
  }

  .q-btn--flat:hover::after {
    transform: scaleX(1) !important;
    transform-origin: bottom left !important;
  }
</style>
