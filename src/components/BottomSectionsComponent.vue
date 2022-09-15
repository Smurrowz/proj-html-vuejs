<template>
  <div class="bg-light">
    <section class="container">
      <div class="wrapper">
        <div class="col-left">
          <h2>We Boost Our Clients' Bottom Line by Optimizing Their Growth Potential.</h2>
          <p>
            Quisque aliquet, libero consequat elementum convallis, erat risus imperdiet pellentesque sem neque eget.
          </p>
          <button class="mybutton-regular orange">Why Work with Us</button>
        </div>
        <div class="col-right">
          <img src="../assets/img/we-boost-our-clients-1200x1098.jpg" alt="immagine team">
        </div>
      </div>
      <div class="wrapper">
        <div class="col-left flex-ut">
          <div>
            <h3>We Build Relationships</h3>
            <span>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Neque est libero excepturi sunt ipsum
              accusantium aliquam ratione, natus nesciunt eius alias odit ullam quia. Numquam eaque iusto rerum nemo
              modi. </span>
          </div>
          <div>
            <h3>Proprietary Processes</h3>
            <span><span>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Neque est libero excepturi sunt ipsum
                accusantium aliquam ratione, natus nesciunt eius alias odit ullam quia. Numquam eaque iusto rerum nemo
                modi. </span></span>

          </div>
        </div>
        <div class="col-right">
          <ul>
            <li>
              <div class="li-icon">
                <font-awesome-icon icon="fa-solid fa-square-rss" />
              </div>
              <div class="li-text">
                <h4>Accountability</h4>
                <span>Curabitur ac leo nunc vestibulum</span>
              </div>
            </li>
            <li>
              <div class="li-icon">
                <font-awesome-icon icon="fa-solid fa-square-plus" />
              </div>
              <div class="li-text">
                <h4>Transparency</h4>
                <span>Curabitur ac leo nunc vestibulum</span>
              </div>
            </li>
            <li>
              <div class="li-icon">
                <font-awesome-icon icon="fa-solid fa-square-poll-vertical" />
              </div>
              <div class="li-text">
                <h4>Investment</h4>
                <span>Curabitur ac leo nunc vestibulum</span>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </section>
    <section class="container">

    </section>
  </div>
</template>
<script>
export default {
  name: 'BottomSectionsComponent'
}
</script>
<style scoped lang="scss">
@import '../assets/style/index.scss';

.bg-light {
  background-color: #F8F8F9;
  padding-top: 130px;
}

.wrapper {
  display: flex;

  & .col-left {
    width: 50%;
    padding: 70px 100px;

    & h3 {
      font-size: 30px;
      margin-bottom: 30px;
    }

    & h2 {
      font-size: 54px;
    }

    & p {
      font-size: 30px;
      padding: 40px 0;
    }
  }

  & .col-left.flex-ut {
    flex-direction: column;
    display: flex;
    gap: 80px;
  }

  & .col-right {
    width: 50%;
    & ul{
      padding: 70px 100px;
    }
    & li {
      display: flex;
      gap: 30px;
      margin-bottom: 100px;
      align-items: center;
      & .li-text{
        display: flex;
        flex-direction: column;
        gap: 10px;
        & h4{
          font-size: 24px;
        }
      }

      & .li-icon {
        border: 4px solid #f76210;
        border-radius: 10px;
        height: 60px;
        width: 60px;
        justify-content: center;
        color: #f76210;
        display: flex;
        align-items: center;
        font-size: 30px;
      }

      & img {
        border-radius: 20px;
      }
    }
  }
}
</style>