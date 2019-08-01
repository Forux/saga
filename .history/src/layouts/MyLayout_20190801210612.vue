<template>
  <q-layout view="hHr lpR fFf">

    <q-header elevated class="bg-primary text-white">
      <q-toolbar class="q-py-none items-stretch ">
        <q-toolbar-title class="text-bold self-center q-mr-xl" style="flex-grow:0;flex-basis:auto;">
          <img src="">
          Сага
        </q-toolbar-title>

        <q-tabs
          dense
          inline-label
          align="left"
          active-color="white"
          indicator-color="white">
          <q-route-tab to="/" label="Page One" />
          <q-route-tab to="/page2" label="Page Two" />
          <q-route-tab to="/page3" label="Page Three" />
        </q-tabs>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script>
export default {
  data () {
    return {
    }
  }
}
</script>
