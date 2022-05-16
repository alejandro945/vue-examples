<script lang="ts">
import { defineComponent } from "vue"
import {person} from '@/types/person'
  export default defineComponent( {
  data() {
    return {
      author: {
        name: 'John Doe',
        books: [
          'Vue 2 - Advanced Guide',
          'Vue 3 - Basic Guide',
          'Vue 4 - The Mystery'
        ]
      }
    }
  }
})
</script>

<template>
    <section>
        <input label="Name">
           {{author.name}}
        <input>

        
    </section>
</template>

