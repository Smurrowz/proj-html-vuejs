<template>
  <main>
    <JumbotronComponent/>
    <SectionComponent/>
    <BottomSectionsComponent/>
  </main>
</template>
<script>
import JumbotronComponent from './JumbotronComponent.vue';
import SectionComponent from './SectionComponent.vue';
import BottomSectionsComponent from './BottomSectionsComponent.vue';
export default {
    name: "MainComponent",
    components: { JumbotronComponent, SectionComponent, BottomSectionsComponent }
}
</script>
<style scoped lang="scss">
main{
  margin-top:150px;

}

</style>