<template>
  <div class="row">
    <app-quote v-for="quote in quotes">
      {{ quote }}
    </app-quote>
  </div>
</template>

<script type="text/javascript">
  import Quote from './Quote.vue';

  export default {
    props: ['quotes'],
    components: {
      appQuote: Quote
    }
  }
</script>

<style type="text/css">
  
</style>