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
    <div class="container awards">
      <h3>Awards</h3>
      <ul class="awards-list">
        <li>
          <img id="logo1" src="../assets/img/award-a.png" alt="logo award 1">
          <span>Winner Seo Master MAGT</span><br>
          <span>Smart Start Award 2017</span>
        </li>
        <li>
          <img id="logo2" src="../assets/img/award-b.png" alt="logo award 1">
          <span>Winner Seo Master MAGT</span><br>
          <span>Smart Start Award 2017</span>
        </li>
        <li>
          <img id="logo3" src="../assets/img/award-c.png" alt="logo award 1">
          <span>Winner Seo Master MAGT</span><br>
          <span>Smart Start Award 2017</span>
        </li>
        <li>
          <img  id="logo4" src="../assets/img/award-d.png" alt="logo award 1">
          <span>Winner Seo Master MAGT</span><br>
          <span>Smart Start Award 2017</span>
        </li>
      </ul>
    </div>
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
  background: rgb(244,244,246);
  background: linear-gradient(0deg, rgba(250,250,251,1) 0%, rgba(244,244,246,1) 100%);
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
    & img {
      border-radius: 12px;
    }
    & ul{
      padding: 70px 100px;
    }
    & li:not(li:last-child){
      margin-bottom: 100px;
    }
    & li {
      display: flex;
      gap: 30px;
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

    }
  }
}
.awards{
  text-align: center;
  padding-bottom: 120px;
  & h3{
    font-size: 30px;
    margin-bottom: 70px;
    
  }
  & ul{
    display: flex;
    justify-content: space-between;
    padding: 0 40px;
    & li{
      display: flex;
      flex-direction: column;
      align-items: center;
      & span{
        font-size: 20px;
      }
      & img{
        height: 100px;
       
        
      }
    }
  }
}
#logo3{
  filter: saturate(5.5);
    opacity: 0.7
}
#logo1{
  filter: invert(1);
}
#logo4{
  filter: hue-rotate(212deg); 
}
</style>