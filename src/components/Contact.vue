<template>
  <section id="contact" class="py-5">
    <div class="container">
      <h2 class="text-center">Contact Me</h2>
      <p class="text-start py-2">
        If you would like to discuss a project or have any questions, please
        feel free to contact me using the form below or via email at
        consultancy@nubelithcompany.cl. I look forward to hearing from you!
      </p>
      <hr />

      <div class="form-row">
        <div class="form-group col-md-6">
          <label for="name">Name</label>
          <input type="text" class="form-control" id="name" placeholder="Your Name" />
        </div>
        <div class="form-group col-md-6">
          <label for="email">Email</label>
          <input type="email" class="form-control" id="email" placeholder="Your Email" />
        </div>
      </div>
      <div class="form-group">
        <label for="message">Message</label>
        <textarea class="form-control" id="message" rows="4" placeholder="Your Message"></textarea>
      </div>
      <v-btn style="margin-top: 5px;" @click="send()" class="btn btn-primary">
        Send
      </v-btn>

    </div>
  </section>
  <v-dialog v-model="onDialog" width="50%">
    <v-card height="80px" class="d-flex justify-center align-center">
      <div class="d-flex justify-center align-center">
        Thank you for your message
      </div>
    </v-card>
  </v-dialog>
</template>

<script lang="ts" setup>

import { ref } from 'vue';
let onDialog = ref(false)
function send() {

  onDialog.value = true

}


</script>