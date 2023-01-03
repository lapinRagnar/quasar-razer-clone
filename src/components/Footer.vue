<template>

<q-toolbar class="le_footer text-white">

  <div class="row q-mt-xl conteneur">

    <div class="col-2">
      <div class="text-caption q-ml-md">Boutique</div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">RazerStores</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">RazerCafes</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Nos Boutiques</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Programme d'achat</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Education</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Exclusivités</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">RazerStores Rewards</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Newsletter</q-btn>
      </div>

    </div>

    <div class="col-2">
      <div class="text-caption q-ml-md">Explorer</div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Technologie</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Chromas RGB</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Concepts</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Esports</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Collaborations</q-btn>
      </div>
    </div>

    <div class="col-2">
      <div class="text-caption q-ml-md">Support</div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Obtenir de l'aide</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Enregistrement et garantie</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">RazerStore Support</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">RazerCare</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Gérer mon Razer ID</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Vidéo d'assistance</q-btn>
      </div>
    </div>

    <div class="col-2">
      <div class="text-caption q-ml-md">Compagny</div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">A propos de</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Carières</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Espace Presse</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">zVentures</q-btn>
      </div>
      <div class="souligner_sur_hover">
        <q-btn no-caps flat class="text-caption text-grey">Contactez-nous</q-btn>
      </div>

    </div>


    <div class="col-2 conteneur-icon-footer">
      <div class="text-green">FOR GAMERS.BY GAMERS.</div>
      <div>
        <q-avatar size="30px" font-size="30px" text-color="green" icon="facebook"/>
        <q-avatar size="30px" font-size="30px" text-color="green" icon="fa-brands fa-instagram" />
        <q-avatar size="30px" font-size="30px" text-color="green" icon="fa-brands fa-twitter" />
      </div>
    </div>

  </div>

  <q-separator class="separer q-mt-xl q-mb-sm" color="orange" dark="false" size="1px" style="width: 300px;" />

  <div class="flex content-between">

    <div class="text-caption text-grey">Copyright © 2022 Razer Inc. All rights reserved.</div>
    <div class="text-caption text-grey">
      Informations Légales
    </div>
    <div class="text-caption text-grey">
      Politique De Confidentialité
    </div>
    <div class="text-caption text-grey">
      Politique d'utilisation des Cookies
    </div>
    <div class="text-caption text-grey">
      France  |  Changer de pays >
    </div>

  </div>

</q-toolbar>

</template>


<script setup>
</script>

<style lang="scss">

  .conteneur {
    align-items: flex-start;
    justify-content: center;
    width: 100%;
  }

  .conteneur-icon-footer {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
  }

  .le_footer {
    background-color: #222;
    display: flex;
    flex-direction: column;
  }

  .separer {
    color: orangered !important;
  }

  .text-separator, .bg-separator, .text-dark-separator, .bg-dark-separator {
    color: orangered !important;
  }

  hr.q-separator.q-separator--horizontal.bg-orange.q-separator--dark.separer {
    color: red !important;
  }
</style>
