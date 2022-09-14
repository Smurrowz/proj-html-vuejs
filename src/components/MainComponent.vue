<template>
  <main>
    <JumbotronComponent/>
  </main>
</template>
<script>
import JumbotronComponent from './JumbotronComponent.vue';
export default {
    name: "MainComponent",
    components: { JumbotronComponent }
}
</script>
<style scoped lang="scss">
main{
  margin-top:150px;

}

</style>