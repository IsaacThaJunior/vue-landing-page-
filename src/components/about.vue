<template>
  <div>
    <section class="section-about">
      <div class="u-center-text u-margin-bottom-big">
        <h2 class="heading-secondary">Exciting tours for adventurous people</h2>
      </div>

      <div class="flex">
        <div class="col-1-of-2">
          <h3 class="heading-tertiary u-margin-bottom-small">Youre going to fall in love with nature</h3>
          <p class="paragraph">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolor nulla beatae ipsum sed veniam magni fugit
            incidunt ducimus, aspernatur quasi nesciunt.
            Laudantium inventore reprehenderit cumque. Dicta quo quisquam esse voluptatum.
          </p>

          <h3 class="heading-tertiary u-margin-bottom-small">Live adventures like you never have before</h3>
          <p class="paragraph">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem delectus eligendi eos? Natus, velit dolor
            obcaecati eligendi cumque iste consequatur
            qui deserunt error tempore.
          </p>

          <a href="#" class="btn-text">Learn more &rarr;</a>
        </div>
        <div class="col-1-of-2">
          <div class="composition">
            <img src="../assets/gadget3.jpeg" alt="Photo 1"
              class="composition__photo composition__photo--p1">

            <img src="../assets/coding.jpeg" alt="Photo 2"
              class="composition__photo composition__photo--p2">

            <img src="../assets/gadget4.jpeg" alt="Photo 3"
              class="composition__photo composition__photo--p3">
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<style scoped>
  .composition {
  position: relative;
  }
  .composition__photo {
    width: 55%;
    box-shadow: 0 1.5rem 4rem rgba(0,0,0, 0.4);
    position: absolute;
    z-index: 10;
    transition: all 0.2s;
    outline-offset: 2rem;
  }

    @media screen and (max-width: 56.25em) {
      .composition__photo{
      width: 33.3333%;
      box-shadow: 0 1.5rem 4rem rgba(0,0,0, 0.4);
      position: relative;
      float: left;
    }

    .composition__photo--p1 {
      top: 0;
        transform: scale(1.2);
    }

    .composition__photo--p2 {
      top: -1rem;
        transform: scale(1.3);
        z-index: 100;
    }

    .composition__photo--p3 {
      top: 0;
        left: 0;
        transform: scale(1.1);
    }

    .heading-secondary {
      font-size: 3rem;
    }
    }

    @media screen and (max-width: 37.5em) {
      .composition__photo{
      width: 50%;
      box-shadow: 0 1.5rem 4rem rgba(0,0,0, 0.4);
      position: relative;
      float: left;
    }

    .heading-secondary {
      font-size: 2.5rem;
    }
    }
      
  

    .composition__photo--p1 {
      left: 0;
      top: -2rem;

    }

    .composition__photo--p2 {
      right: 0;
      top: 2rem;
    }

    .composition__photo--p3 {
      left: 20%;
      top: 10rem;
    }

    .composition__photo:hover {
      outline: 1.5rem solid greenyellow;
      transform: scale(1.05) translateY(-0.5rem);
      box-shadow: 0 2.5rem 4rem rgba(0,0,0, 0.5);
      z-index: 20;
    }

  .composition__photo:hover .composition__photo__photo:not(:hover) {
    transform: scale(0.95);
  }


.heading-secondary {
  font-size: 3.5rem;
  text-transform: uppercase;
  font-weight: 700;
  display: inline-block;
  background-image: linear-gradient(
    to right,
    greenyellow,
    darkgreen
  );
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  letter-spacing: 0.2rem;
  transition: all 0.2s;
}
  .heading-secondary:hover {
    transform: skewY(2deg) skewX(15deg) scale(1.1);
    text-shadow: 0.5rem 1rem 2rem rgba(0,0,0, 0.2);
  }

  .col-1-of-2 {
    width: calc((100% - #{$gutter-horizontal}) / 2);
  }
</style>