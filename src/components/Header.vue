<template>
  <header>
      <nav>
          <img src="../assets/images/light-logo.png" alt="">
          <div class="nav-right">
              <ul>
                  <li><a href="#">Home <i class="fas fa-chevron-down"></i></a></li>
                  <li><a href="#">Pages <i class="fas fa-chevron-down"></i></a></li>
                  <li><a href="#">Courses <i class="fas fa-chevron-down"></i></a></li>
                  <li><a href="#">Features <i class="fas fa-chevron-down"></i></a></li>
                  <li><a href="#">Blog <i class="fas fa-chevron-down"></i></a></li>
                  <li><a href="#">Shop <i class="fas fa-chevron-down"></i></a></li>
                  <li><a href="#">cart <i class="fas fa-chevron-down"></i></a></li>
                  <li><a href="#">profile <i class="fas fa-chevron-down"></i></a></li>
              </ul>
              <div class="input-field">
                  <i class="fas fa-search"></i>
                  <input type="text" placeholder="Search">
              </div>
              
          </div>
      </nav>
      <div class="hero-text">
          <h1>Learn at your own pace!</h1>
          <h4>Get teamed up of the same will</h4>
          <button>Get started for free</button>
      </div>
      <div class="hero-content">
          <div class="images">
              <img src="../assets/images/home-6-hero-left-person.png" alt="">
          </div>
          
          <div class="youtube-screen">
              <img src="../assets/images/icon-youtube-play.png" alt="">
          </div>

          <div class="images">
              <img src="../assets/images/home-6-hero-right-person-195x300.png" alt="">
          </div>
          
      </div>
  </header>
</template>

<script>
export default {
name: 'Header'
}
</script>

<style lang="scss">
header {
    background-color: #202052;
    font-family: 'Poppins', sans-serif;
    color: white;
    height: 90vh;
    background-image: url('../assets/images/Component 1.png');
    background-position: center;
    background-size: cover;
}
nav {
    display: flex;
    justify-items: space-between;
    align-items: center;
    width: 80%;
    height: 100px;
    margin: 0 auto;
    img {
        height: 25px;
    };
    .nav-right{
        width: 100%;
        text-align: end;
        ul {
             list-style: none;
             display: inline-block;
             li {
                display: inline-block;
                padding: .5rem;
                font-size: 12px;
                a {
                    color: white;
                    text-decoration: none;
                }
             };
             input {
                  padding: 12px 20px;
             }
        }
    }    
}
.input-field {
     position: relative;
     display: inline-block;
    i {
        position: absolute;
         top:50%;
         right: 0%;
         color: #27ab96;
         padding: 1rem;
         transform: translateY(-50%);
     }
}

.hero-text {
    width: 50%;
    margin: 3rem auto;
    text-align: center;
    h1 {
        font-weight: 600;
        font-size: 30px;
        text-transform: capitalize;
        letter-spacing: .1rem;
    };
    h4 {
        font-weight: 400;
        color: #bcbcbc;
        padding: .5rem 0 2rem 0;
    };
    button:hover {
        background-color: white;
        color: #27ab94;
    }
}
.hero-content {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    height: 400px;
    margin: 0 auto;
    .youtube-screen {
        display: flex;
        justify-content: center;
        align-items: center;
        background-image: url('../assets/images/home-6-hero-poster-final.jpg');
        width: 60%;
        height: 100%;
        border: 20px solid white;
        border-radius: 10px;
        box-shadow: 0px 2px 10px lightgrey;
        img {
            width: 100px;
            height: auto;
            margin: auto;
        }
    };
    .images {
        width: 20%;
        img {
            width: 100%;
        }
    }
}
</style>