<template>
  <q-page>

    <q-header class="bg-white text-black q-py-xs">
      <q-toolbar class="row q-pa-none">
        <q-btn flat color="black" icon="arrow_back" size="lg" class="col-2 "></q-btn>
        <q-btn flat color="primary" text-color="black" size="lg" no-caps class="col-8" align="start">
          <div align="start">
            <div class="text-bold text-subtitle1">Арс
              <q-icon size="sm" name="expand_more"></q-icon>
            </div>
            <div class="text-caption text-grey-6">Был в сети 2ч. назад</div>
          </div>
        </q-btn>
      </q-toolbar>
    </q-header>

    <DANA/>

    <!-- Это блок чата   -->
    <q-scroll-area class="q-pa-md column absolute-bottom fit" >
      <q-chat-message
        label="8 августа 2020"
      />
      <q-chat-message
        :text="['340 рублей за килограмм ?kbjfgdhsvvvvvvvvdfvbujsvfds uhbovfujibldfv dauhgbija vsduijbhl']"
        sent
        stamp="21:50"
        class="fixed-position-stamp-sent doljnoPomoch "
      />

      <q-chat-message
        avatar="https://cdn.quasar.dev/img/avatar2.jpg"
        :text="['Да']"
        stamp="21:50"

        class="fixed-position-stamp-answer doljnoPomoch"
      />
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
      <q-chat-message :text="['Пизда']" class="doljnoPomoch" sent></q-chat-message>
    </q-scroll-area>
    <!-- Конец блока чата -->

  </q-page>
</template>

<script>
import DANA from '../components/VesovieKonfeti';

export default {
  name: 'PageIndex',
  components: {
    DANA
  },
  data() {
    return {
      text: 'хуй'
    }
  }
}
</script>
