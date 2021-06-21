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
    }
}

</style>