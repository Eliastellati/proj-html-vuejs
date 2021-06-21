<template>
  <header>
      <nav>
          <img src="../assets/images/light-logo.png" alt="">
          <div class="nav-right">
              <ul>
                  <li><a href="#">Home</a></li>
                  <li><a href="#">Pages</a></li>
                  <li><a href="#">Courses</a></li>
                  <li><a href="#">Features</a></li>
                  <li><a href="#">Blog</a></li>
                  <li><a href="#">Shop</a></li>
                  <li><a href="#">cart</a></li>
                  <li><a href="#">profile</a></li>
              </ul>
              <input type="text" placeholder="Search">
          </div>
      </nav>
      <div class="hero-text">
          <h1>Learn at your own pace!</h1>
          <h4>Get teamed up of the same will</h4>
          <button>Get started for free</button>
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
}
nav {
    display: flex;
    justify-items: space-between;
    align-items: center;
    width: 70%;
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
                padding: 1rem;
                a {
                    color: white;
                    text-decoration: none;
                }
             };
             input {
                 height: 40px;
             }
        }
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
    }
}
</style>