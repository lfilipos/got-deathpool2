<template>
  <div>
    <h1>Entry Form</h1>
    Dead or alive
    <ul>
      <li v-for="character in characters">{{character.name}}</li>
    </ul>
  </div>
</template>

<script>
  import CharacterData from '../assets/Characters'

  export default {
    name: 'EntryForm',
    data () {
      return {
        characters: CharacterData.characters
      }
    },
  }
</script>

<style scoped>

</style>
