<template>
    <q-page class="flex flex-center column">
      <q-img src="../../../src/assets/instadev-logo.svg"></q-img>
      <q-input v-model="text" label="Standard" />
      <q-input v-model="text" label="Standard" />
      <a ref="">Forgot password?</a>
      <q-btn color="primary" label="Primary" />
      <div class="flex row">
        <q-img src="../../../src/assets/facebook.svg"></q-img>
        <a ref="">Log in with FaceBook?</a>
      </div>
      <div class="full-width">
        <q-separator color="orange" inset>
          or
        </q-separator>
      </div>
      <div>
        Dont't have an account?<a href=""> Sign up.</a>
      </div>
      <q-separator />
      Instagram or Facebook
    </q-page>
  </template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'SignIn',
  data() {
    return {
      text: '',
    };
  },
});
</script>
