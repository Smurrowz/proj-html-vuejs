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
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eaque officiis veritatis molestias, doloremque
            ducimus aspernatur quam quod praesentium, tempora eos nesciunt ea facere non temporibus corrupti harum illo
            quos impedit.
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
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eaque officiis veritatis molestias, doloremque
            ducimus aspernatur quam quod praesentium, tempora eos nesciunt ea facere non temporibus corrupti harum illo
            quos impedit.
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
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eaque officiis veritatis molestias, doloremque
            ducimus aspernatur quam quod praesentium, tempora eos nesciunt ea facere non temporibus corrupti harum illo
            quos impedit.
          </p>
          <button class="mybutton-regular orange">Get a Consultation</button>
        </div>
      </div>
    </section>
    <section class="container partners">
      <h2>Some Brands We Work With</h2>
      <p>Quisque aliquet, libero consequat elementum convallis.</p>
      <ul>
        <li>
          <a href="#">
            <img src="../assets/img/abstract.png" alt="logo abstract">
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/img/cglobal.png" alt="logo cglobal">
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/img/next.png" alt="logo next">
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/img/hemisferio.png" alt="logo emisferio">
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/img/spaces.png" alt="logo spaces">
          </a>
        </li>
        <li>
          <a href="#">
            <img src="../assets/img/digitalbox.png" alt="logo digitalbox">
          </a>
        </li>
      </ul>

      <div class="navb">
        <div class="employee">
          <img src="../assets/img/marketing-expert-cta.png" alt="immagine marketing expert">
          <div class="employee-info">
            <h4>Sandy Reiff</h4>
            <span>Marketing Consultant Expert</span>
          </div>
        </div>
        <a href="#">Drive Leads and Sales with Avada</a>
        <button class="mybutton-regular empty-orange">
          <font-awesome-icon icon="fa-solid fa-phone" /> (555) 802-1234
        </button>
      </div>

    </section>
    <section class="container orgs">
      <h2>Trusted by Leading Organisations</h2>
      <div class="wrapper">
        <div class="col33">
          <div class="img-content">
            <img src="../assets/img/case-studies-1-1200x1349.jpg" alt="immagine studies 1">
            <div class="overlay"></div>
          </div>
          <p>How Spaces attracted five million visitors by improving the content</p>
          <h3>200%</h3>
          <span>Higher revenue from digital</span>
        </div>
        <div class="col33">
          <div class="img-content">
            <img src="../assets/img/case-studies-4-1200x1349.jpg" alt="immagine studies 2">
            <div class="overlay"></div>
          </div>
          <p>Creativity helped Hemisferio to increase their brand reach vertically</p>
          <h3>10x</h3>
          <span>Sales increase with the same ad spend</span>
        </div>
        <div class="col33">
          <div class="img-content">
            <img src="../assets/img/case-studies-6-1200x1349.jpg" alt="immagine studies 3">
            <div class="overlay"></div>
          </div>
          <p>How DigitalBox used AI-powered data insight to boost sales</p>
          <h3>3-year</h3>
          <span>Partnership with Avada Consultant</span>
        </div>
      </div>
      <button class="mybutton-regular orange">Read More Case Studies</button>
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

section {
  padding-top: 140px;
  padding-bottom: 140px;

  & .reverse-r {
    flex-direction: row-reverse;
  }

  & .wrapper {
    display: flex;
    flex-wrap: wrap;

    & .col {
      width: 50%;
      display: flex;
      flex-direction: column;
      gap: 45px;
      align-items: flex-start;

      & img {
        height: 100%;
      }
    }

    & .col-mg {
      padding-right: 70px;
      padding-left: 70px;

      & .d-flex {
        display: flex;
        gap: 20px;
        align-items: center;
        font-weight: 500;

        & .rounded {

          color: white;
          height: 40px;
          width: 40px;
          display: flex;
          justify-content: center;
          align-items: center;
          border-radius: 50%;
        }

        & .rounded.blue {
          background-color: #455eee;
        }

        & .rounded.gold {
          background-color: gold;
        }

        & .rounded.green {
          background-color: #43D888;
        }
      }

      & h2 {
        font-size: 54px;
      }

      & p {
        font-size: 24px;
      }

      & span {
        font-size: 20px;
      }
    }

  }
}

.partners {
  text-align: center;

  & h2 {
    font-size: 54px;
    margin-bottom: 40px;
  }

  & p {
    font-size: 24px;
    margin-bottom: 65px;
  }

  & ul {
    display: flex;
    justify-content: space-between;
    padding: 0 35px;
    margin-bottom: 180px;

  }

  & .navb {
    display: flex;
    padding: 16px 50px;
    justify-content: space-between;
    align-items: center;
    border-radius: 12px;
    box-shadow: 0px 10px 30px 5px rgb(168, 165, 165);

    & a {
      font-size: 26px;
      font-weight: 500;
    }

    & .employee {
      display: flex;
      gap: 25px;
      align-items: center;

      & img {
        border-radius: 50%;
        max-width: 60px;
      }

      & .employee-info {
        & p {
          font-size: 14px;
        }

        & h4 {
          font-size: 20px;
        }
      }
    }
  }
}

.orgs {
  text-align: center;

  .wrapper {
    display: flex;
    flex-wrap: wrap;

    & .col33 {
      flex-basis: 0;
      flex-grow: 1;
      margin: 80px 20px 80px 20px;

      & .img-content {
        position: relative;
        &:hover{
          .overlay{
            opacity: 0.7;
          }
        }
        & .overlay {
          position: absolute;
          top: 0;
          left: 0;
          height: 100%;
          width: 100%;
          cursor: pointer;
          background: linear-gradient(180deg, rgb(255, 255, 255, 0) 0%, rgba(247,98,16,1) 100%);
          opacity: 0;
          transition: all .3s ease;
          
        }
      }

    }
  }


  & p {
    font-size: 32px;
    margin-top: 30px;
    margin-bottom: 30px;
  }

  & h3 {
    font-size: 54px;
    margin-top: 30px;
    margin-bottom: 20px;
  }

  & span {
    font-size: 20px;
    color: grey;
  }
}
</style>