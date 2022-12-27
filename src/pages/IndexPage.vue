<template>

  <q-page>

    <q-toolbar class="bg-grey text-white flex flex-center bar_de_pub">
      <div>
        Toutes les commandes d'un montant supérieur à 59€ bénéficient d'une livraison gratuite en France.
      </div>
    </q-toolbar>

    <q-img
      src="blade-14-2022-thumbnail.jpeg"
      :ratio="16/9"
      fit="cover"
      height="600px"
      class="flex flex-center"
    >

      <div class="row bg-transparent full-width">
        <div class="text-center text-grey-1 text-h2 text-weight-bolder col-12 full-width q-mt-lg">RAZER BLADE</div>
        <div class="text-grey text-center col-12 text-h5 q-my-xs">TOUTE NOUVELLE VERSION. JOUER AU TOP.</div>
        <div class="flex full-width flex-center text-h6">

          <q-btn class="hover-underline-animation q-mr-xl text-grey-3" flat >
            <div>En Savoir Plus</div>
            <q-icon size="15px" class="text-green q-ml-xs" name="fa-solid fa-chevron-right" />
          </q-btn>

          <q-btn class="hover-underline-animation text-grey-3" flat>
            <div>Acheter</div>
            <q-icon size="15px" class="text-green q-ml-xs" name="fa-solid fa-chevron-right" />
          </q-btn>

        </div>
      </div>

    </q-img>



  </q-page>

</template>

<script setup>

</script>

<style lang="scss" scoped>

  .q-toolbar{
    min-height: 30px !important;
  }

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


