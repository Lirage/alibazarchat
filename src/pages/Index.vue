<template>
  <q-page class="flex column">
<q-header class="bg-white text-black items-center">
  <q-toolbar class="row q-pa-none ">
  <q-btn flat color="black" icon="arrow_back" size="lg" class="col-2 "></q-btn>
  <q-btn  flat color="primary" text-color="black" size="lg" no-caps class="col-8" align="start">
    <div align="start">
    <div class="text-bold text-subtitle1">Арс<q-icon size="sm" name="expand_more"></q-icon></div>
    <div class="text-caption text-grey-6">Был в сети 2ч. назад</div>
    </div>
  </q-btn>
  </q-toolbar>
</q-header>
    <div class="q-pa-none fixed-top z-max bg-white" style="margin-top:50px">
      <q-toolbar class="q-card--bordered q-pa-none items-center">
      <q-btn class="full-width q-pa-none" no-caps flat >
        <div align="start" class="row col-7" >
        <div>Весовые конфеты сникерс</div>
        <div class="text-blue-5 column col-10">340 Р</div>
        </div>
        <q-img src="https://im0-tub-ru.yandex.net/i?id=ba97ccabeae31c2755e9361306ad5a31&ref=rim&n=33&w=267&h=150"
               sizes="(max-width: 400px) 400w,
              (min-width: 400px) and (max-width: 800px) 800w,
              (min-width: 800px) and (max-width: 1200px) 1200w,
              (min-width: 1200px) 1600w"
               style="height: 50px; max-width: 100px">
        </q-img>
      </q-btn>
      </q-toolbar>
    </div>
    <div class="q-pa-md column col justify-end">
      <q-chat-message
        label="8 августа 2020"
      />
        <q-chat-message
          :text="['340 рублей за килограмм ?kbjfgdhsvvvvvvvvdfvbujsvfdsuhbovfujibldfvsdauhgbijavsduijbhl']"
          sent
          stamp="21:50"
          class="fixed-position-stamp-sent message-width"
        />
        <q-chat-message
          avatar="https://cdn.quasar.dev/img/avatar2.jpg"
          :text="['Да']"
          stamp="21:50"

          class="fixed-position-stamp-answer"
        />
      <q-chat-message :text="['Пизда']" sent>

      </q-chat-message>
      </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex'
}
</script>
