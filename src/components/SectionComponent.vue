<template>
  <div>
    <section class="container">
      <div class="wrapper">
        <div class="col">
          <img src="../assets/img/awareness-removebg-preview.png" alt="img brand awareness">
        </div>
        <div class="col col-mg">
          <div>
            <div class="d-flex">
              <div class="rounded blue">
                <font-awesome-icon icon="fa-solid fa-seedling" />
              </div>
              <span>Business Growth</span>
            </div>
          </div>
          <h2>Increase Brand Awareness</h2>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eaque officiis veritatis molestias, doloremque ducimus aspernatur quam quod praesentium, tempora eos nesciunt ea facere non temporibus corrupti harum illo quos impedit.
          </p>
          <button class="mybutton-regular orange">Get a Consultation</button>
        </div>
      </div>
    </section>
    <section class="container">
      <div class="wrapper reverse-r">
        <div class="col">
          <img src="../assets/img/training-removebg-preview.png" alt="img brand awareness">
        </div>
        <div class="col col-mg">
          <div>
            <div class="d-flex">
              <div class="rounded gold">
                <font-awesome-icon icon="fa-solid fa-circle-dot" />
              </div>
              <span>Investors in People</span>
            </div>
          </div>
          <h2>In-House Sales Training</h2>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eaque officiis veritatis molestias, doloremque ducimus aspernatur quam quod praesentium, tempora eos nesciunt ea facere non temporibus corrupti harum illo quos impedit.
          </p>
          <button class="mybutton-regular orange">Get a Consultation</button>
        </div>
      </div>
    </section>
    <section class="container">
      <div class="wrapper">
        <div class="col">
          <img src="../assets/img/harness-removebg-preview.png" alt="img brand awareness">
        </div>
        <div class="col col-mg">
          <div>
            <div class="d-flex">
              <div class="rounded green">
                <font-awesome-icon icon="fa-solid fa-arrows-to-dot" />
              </div>
              <span>Social Media Analysis</span>
            </div>
          </div>
          <h2>Harness Your Social Proof</h2>
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eaque officiis veritatis molestias, doloremque ducimus aspernatur quam quod praesentium, tempora eos nesciunt ea facere non temporibus corrupti harum illo quos impedit.
          </p>
          <button class="mybutton-regular orange">Get a Consultation</button>
        </div>
      </div>
    </section>
    

  </div>
</template>
<script>
export default {
  name: 'SectionComponent'
}
</script>
<style scoped lang="scss">
  @import '../assets/style/index.scss';
  section{
    padding-top: 140px;
    padding-bottom: 140px;
    & .reverse-r{
      flex-direction: row-reverse;
    }
    & .wrapper{
      display: flex;
      flex-wrap: wrap;

      & .col{
        width: 50%;
        display: flex;
        flex-direction: column;
        gap: 45px;
        align-items: flex-start;
        & img{
          height: 100%;
        }
      }
      & .col-mg{
        padding-right: 70px;
        padding-left: 70px;
        & .d-flex{
          display: flex;
          gap: 20px;
          align-items: center;
          font-weight: 500;
          & .rounded{
    
            color: white;
            line-height: 40px;
            width: 40px;
            text-align: center;
            border-radius: 50%;
          }
          & .rounded.blue{
            background-color: #455eee;
          }
          & .rounded.gold{
            background-color: gold;
          }
          & .rounded.green{
            background-color: #43D888;
          }
        }
        & h2{
          font-size: 54px;
        }
        & p{
          font-size: 24px;
        }
        & span{
          font-size: 20px;
        }
      }
      
    }
  }

</style>