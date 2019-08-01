<template>
  <q-layout view="hHr lpR fFf">

    <q-header elevated class="bg-primary text-white">
      <q-toolbar class="q-pa-none">
        <q-toolbar-title class="text-bold" style="flex-grow:0;flex-basis:auto;">
          <q-avatar>
            <img src="">
          </q-avatar>
          Сага
        </q-toolbar-title>

        <q-tabs
          dense
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
