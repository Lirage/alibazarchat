<template>
  <div class="q-pa-none z-max bg-white" style="position: -webkit-sticky;position: sticky;">
    <q-toolbar class="q-card--bordered q-pa-none items-center justify-between row q-pr-md" @click="test">
        <div class="col-1">

        </div>
        <div class="column items-start col-7" >
          <div>Весовые конфеты сникерс</div>
          <div class="text-blue-5">340 Р</div>
        </div>

        <div style="max-height: 32px;max-width: 42px">
          <img class="fit rounded-borders" src="https://25.img.avito.st/image/1/9DhL1LayWNFldYjSL9P8ab53WNfrdVo"
                 />
        </div>
    </q-toolbar>
  </div>
</template>

<script>
export default {
  name: "VesovieKonfeti",
  methods:{
    test(){
      this.$router.push('/test');
    }
  }
}
</script>

