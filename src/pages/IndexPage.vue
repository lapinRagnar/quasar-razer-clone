<template>

  <q-page>

    <q-toolbar class="bg-grey text-white flex flex-center bar_de_pub">
      <div>
        Toutes les commandes d'un montant supérieur à 59€ bénéficient d'une livraison gratuite en France.
      </div>
    </q-toolbar>


    <ImageUneColonne
      v-for="(image, i) in MesImages"
      :key="i"
      :source="image.source"
      :grandTitre="image.grandTitre"
      :sousTitre="image.sousTitre"
      :titreBouton1="image.titreBouton1"
      :titreBouton2="image.titreBouton2"
      class="q-mb-md"
    ></ImageUneColonne>



  </q-page>

</template>

<script setup>
  import ImageUneColonne from '../components/ImageUneColonne.vue'

  const MesImages = [
    {
      source: 'blade-14-2022-thumbnail.jpeg',
      grandTitre: 'RAZER BLADE 14',
      sousTitre: 'TOUTE NOUVELLE VERSION. JOUER AU TOP',
      titreBouton1: 'En Savoir Plus',
      titreBouton2: 'Acheter',
    },
    {
      source: 'razer-blade-15-homepage-desktop-2022-oled.jpeg',
      grandTitre: 'RAZER BLADE 15',
      sousTitre: 'PUISSANCE.PERFORMANCE.PERFECTION.',
      titreBouton1: 'En Savoir Plus',
      titreBouton2: 'Acheter',
    },
    {
      source: 'razer-kraken-kitty-v2-pro--homepage-desktop.jpeg',
      grandTitre: 'RAZER KRAKEN KITTY V2 PRO',
      sousTitre: 'VOUS ÊTES FELINS POUR L\'AUTRE.',
      titreBouton1: 'En Savoir Plus',
      titreBouton2: 'Acheter',
    },
  ]

</script>

<style lang="scss" scoped>

  .q-toolbar{
    min-height: 30px !important;
  }


</style>


