<template>
  <q-layout view="lHh Lpr lFf">
    <q-page-container>
      <router-view />
    </q-page-container>
<q-footer bordered class="bg-white text-black">
  <div class="row items-center q-px-xs" style="height: 50px">
    <div class="col-3 row q-gutter-x-xs">
        <q-btn flat color="primary" icon="add" class="bg-grey-1 col-5"  />
        <q-btn flat color="primary" icon="photo_camera" class="bg-grey-1 col-5"/>
    </div>

    <div class="col-9">
      <q-input rounded outlined v-model="text"  dense placeholder="Написать сообщение...">
        <template v-slot:after>
          <q-btn flat round color="primary" icon="send" class="col" size="md"/>
        </template>

      </q-input>

    </div>


  </div>
</q-footer>
  </q-layout>
</template>
<script>
export default {
  data(){
    return{
      text: ''
    }
  }
}
</script>

