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
          <img id="logo4" src="../assets/img/award-d.png" alt="logo award 1">
          <span>Winner Seo Master MAGT</span><br>
          <span>Smart Start Award 2017</span>
        </li>
      </ul>
    </div>
    <div class="bg-white">
      <div class="container wrap">
        <div class="col">
          <img src="../assets/img/large-testimonial-1200x1166.jpg" alt="immagine testimonial">
        </div>
        <div class="col">
          <blockquote>" The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online
            and offline. We have experienced year on year growth due to their progressive approach."</blockquote>
          <address class="author">Kate Schadler</address>
          <address class="author-role">Marketing Consultant - Abstract</address>
        </div>
      </div>
    </div>
    <section>
      <div class="container marketing">
        <div class="wrapper">
          <div class="col jcsb">
            <div class="col-50">
              <h2>Marketing Resources: Insider Advice on How to Increase Online Sales</h2>

            </div>
            <div class="col-50-2">
              <button class="mybutton-regular orange">Explore All Resources</button>
              
            </div>
          </div>
          <div class="col">
            <div class="col33">
              <div class="img-content">
                <img src="../assets/img/blog-posts-6-1200x800.jpg" alt="immagine blog 1">
                <div class="overlay"></div>
              </div>
              <p>Marketing Tips And Tricks For Your Website</p>
              
            </div>
            <div class="col33">
              <div class="img-content">
                <img src="../assets/img/blog-posts-5-1200x800.jpg" alt="immagine blog 2">
                <div class="overlay"></div>
              </div>
              <p>How to Write Stunning Blog Post Titles</p>
             
            </div>
            <div class="col33">
              <div class="img-content">
                <img src="../assets/img/blog-posts-4-1200x800.jpg" alt="immagine blog 3">
                <div class="overlay"></div>
              </div>
              <p>Techniques to Reduce Facebook Ads Spend</p>
             
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="bg-black">
      <div class="container">
        <div class="wrapper">
          <div class="col-left">
            <div>
              <h1>Let’s Make Things Happen</h1>
              <p>Curabitur ac leo nunc. Vestibulum et mauris vel ante finibus maximus nec ut leo. Integer consectetur.</p>

            </div>
            <blockquote>
              “The team at Avada Marketing Consultant is fabulous. They helped us unlock our potential online and offline. We have experienced year on year growth due to their progressive approach.”
            </blockquote>
            <address class="author">George Anderson</address>
            <address class="author-role">DigitalBox Ceo</address>
          </div>
          <div class="col">
            <CardComponent/>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
import CardComponent from './CardComponent.vue';
export default {
    name: "BottomSectionsComponent",
    components: { CardComponent }
}
</script>
<style scoped lang="scss">
@import '../assets/style/index.scss';

.bg-light {
  background: rgb(244, 244, 246);
  background: linear-gradient(0deg, rgba(250, 250, 251, 1) 0%, rgba(244, 244, 246, 1) 100%);
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

    & ul {
      padding: 70px 100px;
    }

    & li:not(li:last-child) {
      margin-bottom: 100px;
    }

    & li {
      display: flex;
      gap: 30px;
      align-items: center;

      & .li-text {
        display: flex;
        flex-direction: column;
        gap: 10px;

        & h4 {
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

.awards {
  text-align: center;
  padding-bottom: 120px;

  & h3 {
    font-size: 30px;
    margin-bottom: 70px;

  }

  & ul {
    display: flex;
    justify-content: space-between;
    padding: 0 40px;

    & li {
      display: flex;
      flex-direction: column;
      align-items: center;

      & span {
        font-size: 20px;
      }

      & img {
        height: 100px;


      }
    }
  }
}

#logo3 {
  filter: saturate(5.5);
  opacity: 0.7
}

#logo1 {
  filter: invert(1);
}

#logo4 {
  filter: hue-rotate(212deg);
}

.bg-white {
  background-color: white;

  & .wrap {
    display: flex;
    align-items: center;
    padding: 70px 0;

    & .col {
      display: flex;
      flex-direction: column;
      padding: 50px;
      width: 50%;

      & img {
        border-radius: 20px;
      }

      & blockquote {
        font-size: 32px;
        font-weight: 500;
        max-width: 70%;
        margin-bottom: 10px;
      }

      & .author {
        font-size: 20px;
        font-style: normal;
        margin-bottom: 15px;
      }

      & .author-role {
        font-style: normal;
        font-size: 14px;
        margin-bottom: 20px;
      }
    }
  }
}

.marketing{
  padding: 150px 0 50px;
  & .wrapper{
    display: flex;
    flex-wrap: wrap;
    & .jcsb{
      display: flex;
      justify-content: space-between;
      .col-50{
        width: 50%;
      }
      .col-50-2{
        align-items: flex-end;
        display: flex;
      }
    }
    & .col{
      flex-basis: 100%;
      display: flex;
      & .col33 {
      flex-basis: 0;
      flex-grow: 1;
      margin: 80px 20px 80px 20px;
      & p{
        font-size: 32px;
        font-weight: 500;
        padding-top: 25px;
      }

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
  }
}
.bg-black{
  background-color: black;
  padding: 75px 0;
  & .col{
    width: 50%;
  }
  & .col-left{
    color: white;
    width: 50%;
    
    & h1{
      font-size: 72px;
    }
    & p{
      font-size: 30px;
      
    }
    & p:after{
      display: block;
      content: '';
      width: 20%;
      height: 1px;
      background-color: grey;
      margin-top: 20px;
    }
    & blockquote{
      font-size: 22px;
      font-style: italic;
      margin-top: 10px;
      margin-bottom:20px ;
    }
    & .author {
        font-size: 20px;
        font-style: normal;
        margin-bottom: 15px;
      }

      & .author-role {
        font-style: normal;
        font-size: 14px;
        margin-bottom: 20px;
      }
  }
  
}
</style>