<script>
export default {
  data() {
    return {
      name: "Cristina",
      lastname: "Giacobbe",
    }
  }

}

</script>

<template>
  <div>
    <label for="name">First Name</label>
    <input type="text" v-model="name">

    <label for="lastname">LastName</label>
    <input type="text" v-model="lastname">

    <p>Ciao {{ name }} {{ lastname }}</p>
  </div>
</template>

<style scoped></style>