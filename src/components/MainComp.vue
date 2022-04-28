<template>
  <!-- QUESTION ABOUT US -->

  <div class="main">
    <hr />
    <div class="container">
      <div class="presentation">
        <strong>WHO WE ARE</strong>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt
          repellat quaerat quam veritatis dolore quia sed nostrum optio
          molestiae, labore laudantium libero aliquam architecto fugit eligendi
          aliquid sapiente perspiciatis est.
          <button>LEARN MORE</button>
        </p>
      </div>
      <div class="presentation">
        <strong>WHAT WE DO</strong>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde
          doloremque eligendi magnam cumque eius accusantium veniam, quasi, ad
          odit ipsam ullam facilis quam officiis, rerum molestias quis
          dignissimos! Saepe, amet?
          <button>LEARN MORE</button>
        </p>
      </div>
      <div class="presentation">
        <strong>WHERE WE WORK</strong>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Deserunt
          repellat quaerat quam veritatis dolore quia sed nostrum optio
          molestiae, labore laudantium libero aliquam architecto fugit eligendi
          aliquid sapiente perspiciatis est.
          <button>LEARN MORE</button>
        </p>
      </div>
    </div>

    <!-- OBJECTIVE CHECKED -->

    <div class="whitecontainer">
      <div class="objective">
        <span class="checkmark"><i class="fa-solid fa-check"></i></span>
        <strong>A GLOBAL VIEW</strong>
        <p>
          Deserunt repellat quaerat quam veritatis dolore quia sed nostrum optio
          molestiae, labore laudantium libero aliquam architecto fugit eligendi
          aliquid sapiente perspiciatis est.
        </p>
      </div>
      <div class="objective">
        <span class="checkmark"><i class="fa-solid fa-check"></i></span>
        <strong>EXPERT LAWYERS</strong>
        <p>
          Deserunt repellat quaerat quam veritatis dolore quia sed nostrum optio
          molestiae, labore laudantium libero aliquam architecto fugit eligendi
          aliquid sapiente perspiciatis est.
        </p>
      </div>
      <div class="objective">
        <span class="checkmark"><i class="fa-solid fa-check"></i></span>
        <strong>CLIENT FOCUS</strong>
        <p>
          Deserunt repellat quaerat quam veritatis dolore quia sed nostrum optio
          molestiae, labore laudantium libero aliquam architecto fugit eligendi
          aliquid sapiente perspiciatis est.
        </p>
      </div>
      <div class="objective">
        <span class="checkmark"><i class="fa-solid fa-check"></i></span>
        <strong>LOCAL KNOWLEDGE</strong>
        <p>
          Deserunt repellat quaerat quam veritatis dolore quia sed nostrum optio
          molestiae, labore laudantium libero aliquam architecto fugit eligendi
          aliquid sapiente perspiciatis est.
        </p>
      </div>
    </div>

    <!-- ASK AN EXPERT -->
    <div class="greenbanner">
      <span class="greenbannerfont"
        >QUESTIONS ABOUT A JUDICIAL ISSUE? ASK OUR EXPERTS.</span
      >
      <button id="greenbannerbutton">ASK AN EXPERT</button>
    </div>
    <!-- GLOBAL CHALLANGE -->
    <h2>GLOBAL CHALLANGE. WORLD CLASS RESPONSE</h2>
    <hr id="undermark" />
    <div class="our">OUR PEOPLE</div>
    <div class="our">OUR PRACTICE AREAS</div>
    <div class="our">OUR PUBBLICATIONS</div>
    <div class="cardcontainer">
      <div class="row1">
        <img src="..\src\assets\column1-image1.jpg" alt="DeborahBrown" />
        <img src="..\src\assets\column2-image1.jpg" alt="TaxLitigation" />
        <img src="..\src\assets\column3-image1.jpg" alt="LowOilPrices" />
      </div>
    </div>
  </div>
</template>

<script>
</script>

<style scoped lang="scss">
// GENERAL RULES

hr {
  width: 80%;
  margin: 10% 10% 0;
  border: 2px solid #54a096;
}
strong {
  display: block;
  margin: 5% 3%;
  background-color: white;
}
p {
  line-height: 30px;
  background-color: white;
}
button {
  margin: 25px 125px;
  padding: 10px 20px;
  border: 1px solid transparent;
  border-radius: 2px;
  color: white;
  background-color: #30343a;
  display: block;
}

// GENERAL RULES

// QUESTION ABOUT US

.container {
  display: block;
  width: 90vw;
  margin: 0 10vw;
}
.presentation {
  text-align: center;
  border: 1px solid white;
  margin: 0 1px;
  padding: 3% 3%;
  height: 380px;
  width: 493px;
  background-color: white;
  display: inline-block;
}

// QUESTION ABOUT US

// OBJECTIVE CHECKED

.whitecontainer {
  height: 500px;
  display: block;
  margin-top: 100px;
  background-color: white;
  width: 100vw;
}
.checkmark {
  background-color: white;
}
.objective {
  padding: 0;
  text-align: center;
  padding: 5% 3%;
  height: 380px;
  width: 400px;
  background-color: white;
  display: inline-block;
}

// OBJECTIVE CHECKED

// ASK AN EXPERT
.greenbanner {
  color: white;
  display: block;
  padding: 100px;
  background-color: #74a59e;
  width: 100vw;
}
.greenbannerfont {
  display: inline;
  background-color: #74a59e;
  font-size: 30px;
}
#greenbannerbutton {
  display: inline;
  font-size: 15px;
  background-color: #54a096;
  padding: 20px 30px;
  margin-left: 370px;
}

// ASK AN EXPERT

//  GLOBAL CHALLANGE
h2 {
  text-align: center;
  margin: 10% 0 1%;
}
#undermark {
  width: 10vw;
  margin: 2% 45% 5%;
  border: 1px solid #8c919e;
}
.our {
  font-weight: 700;
  display: inline-block;
  margin: 2% 12% 1%;
}
.cardcontainer {
  margin: 2% 12% 1%;
}
//  GLOBAL CHALLANGE
</style>
