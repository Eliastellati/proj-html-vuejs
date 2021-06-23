<template>
  <footer>
      <div class="container">
          <div class="address">
              <h6>Address</h6>
              <p>Loc. Sella Mereti 3a int.1 <br> Levanto (SP) Italy <br> +39 3519402353 <a href="mailto:eliastellatibvb@gmail.com">eliastellatibvb@gmail.com</a></p>
              <div class="socials-container">
                  <div class="social">
                      <a href="https://it-it.facebook.com/elia.stellati.3" target="_blank"><i class="fab fa-facebook-square"></i></a>
                  </div>
                  <div class="social">
                      <a href=""><i class="fab fa-twitter"></i></a>
                  </div>
                  <div class="social">
                      <a href="https://www.instagram.com/eliastellati/" target="_blank"><i class="fab fa-instagram"></i></a>
                  </div>
                  <div class="social">
                      <a href=""><i class="fab fa-linkedin"></i></a>
                  </div>
              </div>
          </div>
          <div class="menu-bottom">
                <div class="menu-left">
                   <h6>
                     explore
                   </h6>
                   <ul>
                      <li>Start Here</li>
                      <li>Blog</li>
                      <li>About Us</li>
                      <li>Success stories</li>
                      <li>Courses</li>
                      <li>Contact Us</li>
                   </ul>
                </div>
                <div class="menu-right">
                    <h6>Information</h6>
                    <ul>
                      <li>Membership</li>
                      <li>Purchase Guide</li>
                      <li>Privacy Policy</li>
                      <li>Terms of Services</li>
                    </ul>
                </div>
              
          </div>
          
      </div>
      <p class="credits">&copy;Boolean .srl</p>
  </footer>
</template>

<script>
export default {
name:'Footer'
}
</script>

<style lang="scss">
footer {
    font-family: 'Poppins', sans-serif;
    background-color:#EFF2F6;
    .container {
        display: flex;
        justify-content: space-between;
        h6 {
          font-size: 16px;
          color: rgb(44, 44, 44);
        }
    }

}
.address {
    line-height: 2;
    p {
        color: #6c6c6c;
        font-size: 12px;
    };
    a {
        text-decoration: none;
    };
    .socials-container {
        display: flex;
        justify-content: start;
        .social {
            font-size: 20px;
            text-align: start;
            padding: .5rem;
            a {
                text-decoration: none;
                color: #6c6c6c;
            }
        }
    }
}
.menu-bottom {
    width: 50%;
    height: 150px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    ul {
        list-style: none;
        li {
            color: #6c6c6c;
            font-size: 12px; 
            padding: .5rem;
            text-align: start;
        }
    }
}
.menu-left ul {
    display: flex;
    flex-wrap: wrap;
    justify-content: flex-start;
    width: 40%;
    height: 50px;
}
.menu-right {
    width: 40%;
}
.menu-left {
    width: 60%;
}
.credits {
    text-align: center;
    color: #6c6c6c;
    font-size: 12px;
    padding: 1rem;
}
</style>