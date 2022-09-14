<template>
  <div class="jumbo">
    <div class="container">
      <div class="wrapper">
        <div class="col-left">
          <h1>Unlock Your Online Growth Potential</h1>
          <p>Online marketing to secure customer retention, leads, and sales. We focus on the bigger picture.</p>
          <button class="mybutton-regular empty">Our Services
            <font-awesome-icon icon="fa-solid fa-arrow-right" />
          </button>
        </div>
        <div class="col-right">
          <CardComponent/>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import CardComponent from './CardComponent.vue';

export default {
    name: "JumbrotronComponent",
    components: { CardComponent }
}
</script>
<style scoped lang="scss">
@import '../assets/style/index.scss';

.jumbo {
  height: 680px;
  background-image: url(https\:\/\/avada\.theme-fusion\.com\/marketing-consultant\/wp-content\/uploads\/sites\/142\/2020\/06\/marketing-intro\.jpg);
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;

  & .container {
    padding-top: 60px;

    & .wrapper {
      display: flex;

      & .col-left {
        width: 50%;
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        gap: 50px;

        & h1 {
          font-size: 4rem;
          color: white;
        }

        & p {
          font-size: 30px;
          font-weight: 500;
          color: white;
        }

      }

      & .col-right {
        width: 50%;
        

      }
    }
  }
}
</style>