<template>
  <div class="contacts">
    <i class="fas fa-bars fa-2x">
    </i>
    <h2>Contacts</h2>
    <SingleContact></SingleContact>
  </div>
</template>

<script>
import SingleContact from "@/components/SingleContact";
export default {
  name: "Contacts",
  components: {SingleContact}
}
</script>

<style scoped>

</style>