<template>
  <header>
    <nav class="container header-nav">
      <div>
        <img src="../assets/img/avada-marketing-logo.png" alt="logo avada">
      </div>
      <ul class="nav-list">
        <li>
          <a href="#">Home <font-awesome-icon icon="fa-solid fa-chevron-down" /></a>
        </li>
        <li>
          <a href="#">Services <font-awesome-icon icon="fa-solid fa-chevron-down" /></a>
        </li>
        <li>
          <a href="#">Why Us</a>
        </li>
        <li>
          <a href="#">Case Studies</a>
        </li>
        <li>
          <a href="#">About</a>
        </li>
        <li>
          <a href="#">Blog</a>
        </li>
      </ul>
      <div class="nav-3">
        <div class="phone-icon">
          <font-awesome-icon icon="fa-solid fa-phone" />
          <a class="p-number" href="#"> (555) 802-1234</a>

        </div>
        <button class="mybutton-regular empty-orange"> Free Quote</button>
      </div>
      <div class="sticky-widgets">
        <div class="widget">
          <div class="widg-icon">
            <font-awesome-icon icon="fa-solid fa-folder" />
          </div>
          Demos
        </div>
        
        <div class="widget">
          <span>39</span>
          On Sale

        </div>
      </div>
    </nav>
  </header>
</template>
<script>
export default {
  name: 'HeaderComponent'
}
</script>
<style scoped lang="scss">
@import '../assets/style/index.scss';
header{
  background-color: #fefefe;
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  z-index: 1000;
}
.header-nav{
  display: flex;
  justify-content: space-between;
  gap: 50px;
  align-items: center;
  font-size: 18px;
  font-weight: 600;
  & .nav-list{
    display: flex;
    gap: 40px;
    & li{
      position: relative;
      padding: 6px;
      
    }
    & li:hover{
      color: #f76210;
      
    }
    & li:hover::after{
      content: '';
      width: 100%;
      height: 4px;
      background-color: #f76210;
      display: block;
      position: absolute;
      bottom: -10px;
      left: 0;
      right: 0;

      
      
    }

  }
  & .nav-3{
    display: flex;
    gap: 40px;
    align-items: center;
    & .phone-icon{
      display: flex;
      align-items: center;
      color: #f76210;
      
    }
    & .p-number{
      color: black;
      margin-left: 10px;
    }
    button{
      margin-top: 30px;
      margin-bottom: 30px;
    }  
    
   
   
  }

}
.sticky-widgets{
  position: fixed;
  top: 200px;
  right: 50px;
  z-index: 1001;
  & .widget{
    width: 70px;
    height: 70px;
    padding: 6px;
    background-color: white;
    margin-bottom: 10px;
    font-size: 12px;
    border-radius: 10px;
    text-align: center;
    box-shadow: 2px 2px 20px  black;
    & .widg-icon{
      font-size: 30px;
      color: rgb(34, 32, 55);
    }
    & span{
      color: rgb(27, 182, 27);
      font-size: 36px;
      
    }
    & span::before{
      content: '$';
      display: block;
      font-size: 12px;
      position: absolute;

    }
  }
}

</style>