<script lang="ts">
import { defineComponent } from "vue-demi";
import BasicForm from "../components/BasicForm.vue";

export default defineComponent({
    setup() {
    },
    components: { BasicForm }
})
</script>


<template>

  <div class="about">
    <h1>This is an about page</h1>
    <div>
    <BasicForm/>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
