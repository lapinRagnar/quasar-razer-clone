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
            size="10px"
            icon="fa-solid fa-magnifying-glass"
          />

          <q-btn dense icon="mdi-cart-minus">
            <q-badge rounded color="green" floating>4</q-badge>
          </q-btn>



      </q-toolbar>


    </q-header>



    <q-page-container>
      <router-view />
    </q-page-container>



  </q-layout>

</template>

<script setup>

</script>

<style lang="scss">

  .navigation_haut{
    border-bottom: 3px solid green!important;
    padding-left: 120px;
    padding-right: 120px;
  }

  .le_footer {
    background-color: #222;
  }

  .souligner_sur_hover {
    text-decoration: none !important;
  }




</style>
