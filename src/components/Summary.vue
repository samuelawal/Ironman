<template>
  <section>
    <div class="container px-7">
      <div class="row h-100 mt-lg-5 mt-md-5 mt-sm-3 pt-4">
        <div
          class="
            col-lg-6 col-md-12 col-sm-12 col-12
            order-sm-last
            order-last
            order-md-first
            order-lg-first
            order-xl-first
          "
        >
          <div class="d-flex flex-row bd-highlight mb-3 justify-content-center justify-content-md-start justify-content-sm-center">
            <div class="pb-4 sum-underline"></div>
            <div class="ms-2 ">18th August 2022</div>
          </div>
          <h1 class="text-center text-sm-center text-lg-start text-md-start">
            Iron Man
          </h1>
          <p class="text-entry text-center text-sm-center text-lg-start text-md-start">
            <strong>Tales of </strong>Supernova <strong>Gold Avenger</strong>
          </p>
          <p class="text-capitalize fw-light">
            Tony Stark, who has Inherited the defense Contractor Stack
            Industries from his Late Father Howard Stark, is in war -torn
            Afghanisthan with his friend and a History Liason. Tony now leads
            the avengers squad
          </p>
          <div class="d-flex flex-md-row bd-highlight mt-4 flex-sm-column justigy-content-lg-start justify-content-md-start ">
            <div class="bd-highlight">
              <button class="btn btn-danger px-2">
                Read More <i class="fa-solid fa-arrow-right ms-2"></i>
              </button>
            </div>
            <div class="p-2 bd-highlight d-sm-none d-md-block">
              <div class="d-flex flex-row bd-highlight ms-2 myVid">
                <div class="bd-highlight ">
                  <i class="fa-regular fa-circle-play fa-3x"></i>
                </div>
                <div class="bd-highlight ms-2 ">Watch<br />Intro Video</div>
              </div>
            </div>
          </div>
          <div class="slideContainer mt-3 mt-sm-2">
            <div class="d-flex flex-row bd-highlight mb-3 justigy-content-lg-start justify-content-md-start justify-content-sm-center">
              <div class="p-3 bd-highlight">01</div>
              <div class="p-3 bd-highlight active">02</div>
              <div class="p-3 bd-highlight">03</div>
              <div class="p-3 bd-highlight">04</div>
              <div class="p-3 bd-highlight ms-5">
                <i class="fa-solid fa-angle-left"></i>
                <i class="fa-solid fa-angle-right ms-4"></i>
              </div>
            </div>
            <input
              type="range"
              min="1"
              max="100"
              value="50"
              class="slider"
              id="myRange"
            />
          </div>
        </div>
        <div
          class="
            col-lg-6 col-md-12 col-sm-12 col-12
            order-sm-first order-md-last order-lg-last order-xl-last
          "
        >
          <div class="me-4">
            <img
              src="../assets/images/ironman.png"
              width="100%"
              class="ms-md-5 ms-0 myImg mb-5"
            />
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {
  name: "Summary",
};
</script>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,400;1,400;1,900&display=swap");
section {
  font-family: "Montserrat", sans-serif;
  color: #ffffff;
}

.active {
  color: #c00000;
}
.sum-underline {
  border-bottom: 1px solid red;
  width: 100px;
}
h1 {
  text-transform: uppercase;
  font-style: italic;
  font-size: 90px;
  font-weight: 900;
}
.text-entry {
  font-size: 28px;
  font-style: italic;
  word-spacing: 3;
}
button {
  background-color: #c00000;
  outline: none;
  width: 200px;
  height: 50px;
}
.slider {
  width: 200px;
}
.slider::-webkit-slider-thumb {
  background: #c00000;
}
    @media screen and (max-width: 1400px) {
      h1 {
        font-size: 70px;
      }
    }
    @media screen and (max-width: 1200px) {
      .myImg {
        width: 550px;
      }
    }
        @media screen and (max-width: 992px) {
          .slider{
            display: none;
          }
            .sum-underline{
              display: none;
            }
          button{
        width: 100%;
      }
              @media screen and (max-width: 560px) {
                .myImg{
                  width: 100%;
                }
            .text-entry{
              font-size: 20px;
              }
              }
        }
        @media screen and (max-width: 500px) {
          h1{
            font-size: 50px;
          }
        }
</style>
    
