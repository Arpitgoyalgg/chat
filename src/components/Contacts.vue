<template>
  <div class="contacts">
    <i class="fas fa-bars fa-2x">
    </i>
    <h2>Contacts</h2>
    <SingleContact></SingleContact>
    <div class="contact">
      <div class="pic stark">
      </div>
      <div class="name">Tony Stark</div>
      <div class="message">Uh, he's from space, he came here to steal a necklace from a wizard.</div>
    </div>
    <div class="contact">
      <div class="pic banner">
      </div>
      <div class="badge">1</div>
      <div class="name">Bruce Banner</div>
      <div class="message">There's an Ant-Man *and* a Spider-Man?</div>
    </div>
    <div class="contact">
      <div class="pic thor">
      </div>
      <div class="name">Thor Odinson</div>
      <div class="badge">3</div>
      <div class="message">I like this one</div>
    </div>
    <div class="contact">
      <div class="pic danvers">
      </div>
      <div class="badge">2</div>
      <div class="name">Carol Danvers</div>
      <div class="message">Hey Peter Parker, you got something for me?</div>
    </div>
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