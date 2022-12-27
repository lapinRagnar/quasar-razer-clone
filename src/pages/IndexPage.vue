<template>

  <q-page>

    <q-toolbar class="bg-grey text-white flex flex-center bar_de_pub">
      <div>
        Toutes les commandes d'un montant supérieur à 59€ bénéficient d'une livraison gratuite en France.
      </div>
    </q-toolbar>


    <ImageUneColonne
      v-for="(image, i) in MesImagesUneColonne"
      :key="i"
      :source="image.source"
      :grandTitre="image.grandTitre"
      :sousTitre="image.sousTitre"
      :titreBouton1="image.titreBouton1"
      :titreBouton2="image.titreBouton2"
      class="q-mb-md"
    ></ImageUneColonne>

    <div class="row flex flex-center" >

      <ImageDeuxColonnes
        :source="image.source"
        :grandTitre="image.grandTitre"
        :sousTitre="image.sousTitre"
        :titreBouton1="image.titreBouton1"
        :titreBouton2="image.titreBouton2"
        class="q-pa-md q-mb-md col-6"
        v-for="(image, i) in MesImagesDeuxColonnes" :key="i"
      ></ImageDeuxColonnes>

    </div>

  </q-page>

</template>

<script setup>
  import ImageUneColonne from '../components/ImageUneColonne.vue'
  import ImageDeuxColonnes from '../components/ImageDeuxColonnes.vue'

  const MesImagesUneColonne = [
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
  const MesImagesDeuxColonnes = [
    {
      source: 'holiday-gift-guide-2022-b-954x580-desktop.jpeg',
      grandTitre: 'BIENVENUE DANS LA SAISON GAGNANTE',
      sousTitre: 'EXCLUSIVITE DE JEUX POUR LA SAISON DE FÊTES',
      titreBouton1: 'Acheter Maintenant',
    },
    {
      source: 'razer-naga-v2-pro-950x580-desktop.jpeg',
      grandTitre: 'RAZER NAGA V2 PRO',
      sousTitre: 'S\'ADAPTER ET SE DECHAINER.',
      titreBouton1: 'En Savoir Plus',
      titreBouton2: 'Acheter',
    },
    {
      source: 'deathstalkerprotkl-950x580-desktop.jpeg',
      grandTitre: 'RAZER DEATHSTALKER V2 PRO TENKEYLESS',
      sousTitre: 'ERGONOMIE ULTRA-COMPACTE.HAUTE PERFORMANCE SANS FILS.',
      titreBouton1: 'En Savoir Plus',
      titreBouton2: 'Acheter',
    },
    {
      source: 'razer-enki-pro-koenigsegg-williams-esports-950x580-desktop.jpeg',
      grandTitre: 'RAZER ENKI PRO',
      sousTitre: 'LE CONFORT ULTIME TOUTE LA JOURNEE.',
      titreBouton1: 'Koenigsegg Edition',
      titreBouton2: 'Williams Esports Edition',
    },
    {
      source: 'razer-quartz-mercury-white-homepage-b-950x580-desktop.jpeg',
      grandTitre: 'RAZER QUARTZ, MERCURY & WHITE',
      sousTitre: 'AUDACIEUX.FRAIS.EPURE.',
      titreBouton1: 'Acheter Quartz',
      titreBouton2: 'Acheter Mercure et blanc',
    },
    {
      source: 'razerstore-reward-acquisition-b-950x580-desktop.jpeg',
      grandTitre: 'RAZERSTORE REWARDS',
      sousTitre: 'INSCRIVEZ-VOUS POUR BENEFICIER D\'AVANTAGES',
      titreBouton1: 'Adhérer Maintenant',
      titreBouton2: '',
    },
  ]

</script>

<style lang="scss" scoped>

  .q-toolbar{
    min-height: 30px !important;
  }


</style>


