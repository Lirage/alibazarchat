<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>
      <router-view />
    </q-page-container>
<q-footer bordered class="bg-white text-black">
  <div class="row items-center">
    <q-btn flat round color="primary" icon="add" class="col" size="md" />
    <q-btn flat round color="primary" icon="photo_camera" class="col" size="md"/>
    <q-input borderless v-model="text" class="col-8" placeholder="Написать сообщение..."/>
    <q-btn flat round color="primary" icon="send" class="col" size="md"/>

  </div>
</q-footer>
  </q-layout>
</template>

