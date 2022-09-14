<template>
  <main>
    <JumbotronComponent/>
    <SectionComponent/>
  </main>
</template>
<script>
import JumbotronComponent from './JumbotronComponent.vue';
import SectionComponent from './SectionComponent.vue';
export default {
    name: "MainComponent",
    components: { JumbotronComponent, SectionComponent }
}
</script>
<style scoped lang="scss">
main{
  margin-top:150px;

}

</style>