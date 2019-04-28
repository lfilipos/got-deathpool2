<template>
  <div id="secure">
    <h1>Secure Area</h1>
    <entry-form></entry-form>
  </div>
</template>

<script>
  import EntryForm from '../components/EntryForm'

  export default {
    name: 'Secure',
    components: {
      EntryForm
    },
    data() {
      return {};
    }
  }
</script>

<style scoped>
  #secure {
    background-color: #FFFFFF;
    border: 1px solid #CCCCCC;
    padding: 20px;
    margin-top: 10px;
  }
</style>
