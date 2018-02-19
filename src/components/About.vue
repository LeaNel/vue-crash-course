<template>
  <div class="about">
      <h1>Hello there {{their_name}}, This is the about page</h1>
      <p>Lorem itsum dolor met</p>
  </div>
</template>

<script>
export default {
    name: 'About',
    data() {
        return {
            their_name : this.$route.params.name
        }
    }
  
}
</script>

