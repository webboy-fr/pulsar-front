<template>
  <h2>Membres</h2>
  <ul>
    <li v-for="member of members" :key="member.id">{{member.firstname}} {{member.lastname}}</li>
  </ul>
</template>

<script>
  export default {
    name: 'Members',
    data() {
      return {
        test: 'julien',
        members: []
      }
    },
    async created() {
      let data = await fetch('http://api.pulsar.local/members')
      this.members = await data.json();
    }

  }
</script>

<style scoped>

</style>