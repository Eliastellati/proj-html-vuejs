<template>
  <main>
      <section>
          <div class="container cnt-1">
              <div class="text-container">
                  <h2>
                      Let passion and determination be the guide along the way and develop at your own pace <br>
                      That's comfortable.
                  </h2>
                  <h4>FANNIE MORENO</h4>
                  <span>Founder and CEO</span>
              </div>
              <div class="numbers-container">
                  <div class="number">
                      <h3>1.926</h3>
                      <p>finished sessions</p>
                  </div>
                  <div class="number">
                      <h3>3.092+</h3>
                      <p>enrolled learners</p>
                  </div>
                  <div class="number">
                      <h3>200</h3>
                      <p>online instructors</p>
                  </div>
                  <div class="number">
                      <h3>100%</h3>
                      <p>satisfaction rate</p>
                  </div>
              </div>
              <div class="cards-container">
                  <div class="column cln-1">
                      <div class="card">
                          <h3>Graphic Design</h3>
                          <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Suscipit voluptatum quia nemo ipsum debitis necessitatibus officiis quam natus quaerat autem.</p>
                          <img src="../assets/images/home-6-service-image-01.png" alt="">
                      </div>
                      <div class="card"></div>
                  </div>
                  <div class="column cln-2">
                      <div class="card"></div>
                      <div class="card"></div>
                  </div>
                  <div class="service-text">
                      <h5>together we can create</h5>
                      <h2>Services we <span>can provide</span> for my clients</h2>
                      <ul>
                          <li><i class="fas fa-check"></i>Select &amp; customise courses to your preferences</li>
                          <li><i class="fas fa-check"></i>Change the tutor and make arrangements</li>
                          <li><i class="fas fa-check"></i>Partecipate in events to join others</li>
                          <li><i class="fas fa-check"></i>Get the desire certificate delivered at house</li>
                      </ul>
                      <button>get started for free</button>
                  </div>
              </div>
          </div>
      </section>
  </main>
</template>

<script>
export default {
name: 'Main'
}
</script>

<style lang="scss">
main {
    background-color: #FEFEFE;
    font-family: 'Poppins', sans-serif;
}
.container {
    width: 70%;
    margin: 0 auto;
}
.cnt-1 {
    background-image: url('../assets/images/background-pattern-grid-line.png');
    background-repeat: repeat;
    background-size: calc(100% / 4);
    background-position: center;
    padding-top: 100px;
    .text-container {
        width: 60%;
        margin: 0 auto;
        padding: 3rem 0;
        text-align: center;
        h2 {
            padding: 2rem;
            font-size: 20px;
        };
        h4 {
            font-size: 12px;
        };
        span {
            font-size: 10px;
            color: #bcbcbc;
        }
    };
    .numbers-container {
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        text-align: center;
        padding: 3rem 0;
        .number>h3 {
            color: #27ab94;
            font-size: 30px;
        };
        p {
            text-transform: uppercase;
            font-size: 12px;
            font-weight: 600;
            color: #6c6c6c;
        }
    };
    .cards-container {
        display: flex;
        justify-content: space-evenly;
        .column {
            width: 20%;
            .card {
                background-color: #ffffff;
                box-shadow: 1px 1px 28px grey;
                h3, p {
                    font-size: 10px;
                    padding: .3rem;
                }
                img {
                    width: 100%;
                    object-fit: contain;
                }
            }
        }

        .service-text {
            width: 40%;
            padding: 3rem;
            h5 {
                color:#6c6c6c;
                text-transform: uppercase;
                font-size: 10px;
                padding: 1rem 0;
            };
            h2 {
                font-weight: 400;
                font-size: 30px;
                line-height: 1;
                text-transform: capitalize;
                span {
                    color: #27ab94;
                    font-weight: 300;
                }
            };
            ul {
                list-style: none;
                padding: 2rem 0;
                li {
                    padding: .4rem;
                    font-size: 10px;
                    color:#6c6c6c;
                    i {
                        color: #27ab94;
                        padding-right: .5rem;
                    }
                }
            }
        }
    }
}

</style>