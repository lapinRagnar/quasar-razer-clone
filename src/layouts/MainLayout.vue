<template>
  <q-layout view="lHh Lpr lFf">

    <q-header>

      <q-toolbar class="navigation_haut bg-black text-white row justify-around text-grey" style="height: 60px;">


        <q-avatar>
          <img src="https://assets2.razerzone.com/images/phoenix/razer-ths-logo.svg">
        </q-avatar>


          <q-btn>
            PC
          </q-btn>

          <q-btn
            no-caps
          >
            Console
          </q-btn>

          <q-btn
            no-caps
          >
            Mobile
          </q-btn>

          <q-btn
            no-caps
          >
            Style de Vie
          </q-btn>

          <q-btn
            no-caps
          >
            Services
          </q-btn>

          <q-btn
            no-caps
          >
            Communauté
          </q-btn>

          <q-btn
            no-caps
          >
            Support
          </q-btn>

          <q-btn
            no-caps
          >
            Store
          </q-btn>




          <q-btn
            class="q-mr-lg"
            size="10px"
            icon="fa-solid fa-magnifying-glass"
          />

          <q-btn dense icon="mdi-cart-minus">
            <q-badge rounded color="green" floating>4</q-badge>
          </q-btn>



      </q-toolbar>

      <q-bar dark class=" bg-grey-8 text-white">
        <div class="col text-center text-grey-5">
          Toutes les commandes d'un montant supérieur à 59€ bénéficient d'une livraison gratuite en France.
        </div>
      </q-bar>

    </q-header>



    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer elevated class="bg-grey-8 text-white">
      <q-toolbar>
        <q-toolbar-title>
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg">
          </q-avatar>
          <div>Title</div>
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>

  </q-layout>

</template>

<script setup>

</script>

<style lang="scss">

  .navigation_haut{
    border-bottom: 1px solid green!important;
    padding-left: 120px;
    padding-right: 120px;
  }


</style>
