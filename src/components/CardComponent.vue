<template>
  <div class="card">
            <div class="card-top">
              <img class="card-img" src="../assets/img/marketing-consultant-expert.jpg" alt="immagine Richard Madsen">
              <h4>Richard Madsen</h4>
              <span class="role">Marketing Consultant Expert</span>
              <div class="a-number">
                <font-awesome-icon icon="fa-solid fa-phone" />
                <a href="#"> (555) 802-1234</a>

              </div>
              <div class="card-bottom">
                <input type="text" name="" id="" placeholder="Your Name*">
                <input type="email" name="" id="" placeholder="Your Email*">
                <input type="number" name="" id="" placeholder="Your Number*">
                <button class="mybutton-regular orange" type="submit">Get a Callback</button>
                <span class="msg-warning">by submitting my data i agree to be contacted</span>
              </div>
            </div>
          </div>
</template>
<script>
  export default {
    name: 'CardComponent'
  }
</script>
<style scoped lang="scss">
  @import '../assets/style/index.scss';
  .card{
          padding: 24px;
          border-radius: 12px;
          background-color: white;
          margin-right: 15%;
          margin-left: 15%;
          border: 1px solid rgb(238, 238, 238);
          box-shadow: 0px 20px 20px rgb(195, 192, 192) ;
          & .card-top{
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
            & .card-img {
              border-radius: 50%;
              max-width: 80px;
            }
            & .a-number{
              color: #f76210 ;
              font-size: 18px;
              margin-bottom: 20px;
            }
            & h4{
              font-size: 26px;
              margin-bottom: 10px;
            }
            & .role{
              color: grey;
              font-size: 19px;
              margin-bottom: 10px;
            }
          }
          & .card-bottom{
            display: flex;
            flex-direction: column;
            gap: 1rem;
            width: 100%;
            & .msg-warning{
              font-size: 12px ;
              color: grey;
            }
            & input{
              border-radius: 10px;
              line-height: 60px;
              padding: 0px 20px ;
              font-size: 18px;
              background-image:url(../assets/img/image.png) ;
              background-repeat: no-repeat;
              background-position: 98% 50%;
            }
          }

        }
</style>