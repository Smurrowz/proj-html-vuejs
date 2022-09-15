<template>
  <footer>
    <div class="container">
      <div class="wrapper">
        <div class="col-40">
          <h3>
            Grow Your Online Business Strategically, and Improve Customer Retention.
          </h3>
          <ul class="social-links">
            <li>
              <a href="#"><font-awesome-icon icon="fa-brands fa-facebook-f" /></a>
            </li>
            <li>
              <a href="#"><font-awesome-icon icon="fa-brands fa-twitter" /></a>
            </li>
            <li>
              <a href="#"><font-awesome-icon icon="fa-brands fa-instagram" /></a>
            </li>
            <li>
              <a href="#"><font-awesome-icon icon="fa-brands fa-youtube" /></a>
            </li>
            <li>
              <a href="#"><font-awesome-icon icon="fa-brands fa-linkedin-in" /></a>
            </li>
            <li>
              <a href="#"><font-awesome-icon icon="fa-brands fa-tiktok" /></a>
            </li>
          </ul>
        </div>
        <div class="col-20">
          <h4>Services</h4>
          <ul>
            <li>
              <a href="#">Marketing Plan</a>
            </li>
            <li>
              <a href="#">Sales Development</a>
            </li>
            <li>
              <a href="#">Digital Marketing</a>
            </li>
            <li>
              <a href="#">Pricing</a>
            </li>
            <li>
              <a href="#">Why Us</a>
            </li>
            <li>
              <a href="#">Case Studies</a>
            </li>
          </ul>
        </div>
        <div class="col-20">
          <h4>Resources</h4>
          <ul>
            <li>
              <a href="#">Learning Center</a>
            </li>
            <li>
              <a href="#">Video Tutorials</a>
            </li>
            <li>
              <a href="#">Customers</a>
            </li>
            <li>
              <a href="#">Blog</a>
            </li>
          </ul>
        </div>
        <div class="col-20">
          <h4>Company</h4>
          <ul>
            <li>
              <a href="#">Who We Are</a>
            </li>
            <li>
              <a href="#">Contact Us</a>
            </li>
            <li>
              <a href="#">Careers</a>
            </li>
            
          </ul>
        </div>
      </div>
      <div class="wrapper">
          <div class="col-40">
            <p>© 2020 • Avada Consultant • Powered by WordPress</p>
          </div>
          <div class="col-20">
            Call Us (555) 802-1234
          </div>
          <div class="col-20">
            
          </div>
          <div class="col-20">
            info@yourcompany.com
          </div>

      </div>
    </div>
    <div class="widget">
      <div class="widget-text">
        <img src="../assets/img/marketing-expert-cta.png" alt="immagine chat support">
        <div class="widget-delete">
          <font-awesome-icon icon="fa-solid fa-x" />
        </div>
        <p>
          This is a free HubSpot live chat. You can create your own chat flows and engage your customers with Avada & HubSpot!
        </p>
      </div>
      <a class="widget-icon" href="#"><font-awesome-icon icon="fa-brands fa-rocketchat" /></a>
    </div>
  </footer>
</template>
<script>
export default {
  name: 'FooterComponent'
}
</script>
<style scoped lang="scss">
  @import '../assets/style/index.scss';
footer{
  padding: 75px;
  & .wrapper{
    display: flex;
    flex-wrap: wrap;
    margin-bottom: 50px;
    & .col-40{
      width: 40%;
      padding: 0 40px;
      & h3{
        font-size: 32px;
        margin-bottom: 20px;
      }
      & .social-links{
        display: flex;
        justify-content: flex-start;
        gap: 25px ;
        
      }
    }
    & .col-20{
      width: 20%;
      & h4, a{
        font-size: 20px;
        line-height: 2.5rem;
      }
    }
  }
}
.widget{
  position: fixed;
  bottom: 20px;
  right: 20px;
  z-index: 1000;
  width: 200px;
  display: flex;
  flex-direction: column;
  & .widget-text{
    box-shadow: 0px 0px 10px 2px rgb(157, 155, 155);
    background-color: white;
    border-radius: 5px;
    padding: 30px 10px 10px 10px;
    position: relative;
    
    & .widget-delete{
      position: absolute;
      top: 10px;
      right: 10px;
    }
    & img{
      border-radius: 50%;
      max-width: 50px;
      position: absolute;
      top: -25px;
      left: 50%;
      transform: translateX(-50%);
      
      
    }
  }
  & .widget-icon{
    color:#f76210 ;
    font-size: 40px;
    align-self: flex-end;
    

  }
  
}
</style>