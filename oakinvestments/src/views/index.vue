<script setup>
import navigation from '@/components/navigation.vue'
</script>

<template>
  <navigation />
  <section class="se-hero">
    <div class="hero-heading">
      <p class="hero-sub-heading-green">Shaping The Future</p>
      <h1 class="hero-main-heading">
        Empowering the Future Through<br />
        Clean Energy <span> Innovation</span>
      </h1>
      <p class="hero-sub-heading-normal">One Sustainable Solution At A Time.</p>
    </div>

    <div class="hero-rating">
      <div class="hero-rating-wrapper">
        <h3>4.9</h3>
        <p>UNHCR</p>
      </div>
      <div class="hero-rating-wrapper">
        <h3>4.9</h3>
        <p>UNHCR</p>
      </div>
      <div class="hero-rating-wrapper">
        <h3>4.9</h3>
        <p>UNHCR</p>
      </div>
    </div>
  </section>

  <section class="se-about">
    <div class="about-wrapper">
      <h1 class="about-heading">OAK Investments Limited</h1>
      <p class="about-par">
        A Rwandan service provider committed to increasing access to cleaner, more sustainable
        energy solutions for cooking and lighting and promoting environmental conservation with
        affordability across the region.
      </p>
    </div>

    <div class="about-pateners"></div>
  </section>

  <div class="se-products">
    <h1 class="products-heading">
      <span>Products</span><br />
      Our Industry-<br />
      Supercharged Products.
    </h1>

    <div class="products-wrapper">
      <div class="product">
        <h3 class="product-name">STOVE</h3>
        <p class="product-desc">
          The ZED X has been designed to meet the needs of roboticists working at the bleeding edge.
        </p>
        <p class="product-link">view</p>
      </div>
      <div class="product">
        <h3 class="product-name">STOVE</h3>
        <p class="product-desc">
          The ZED X has been designed to meet the needs of roboticists working at the bleeding edge.
        </p>
        <p class="product-link">view</p>
      </div>
    </div>
  </div>

  <div class="se-services">
    <div class="services-main">
      <h1 class="services-title">
        <span>Services</span><br />
        What OAK offers to <br />
        it’s dearest customers.
      </h1>
      <div class="services-wrapper">
        <div class="services-serve">
          <p>Crafted Briquettes</p>
        </div>
        <div class="services-serve">
          <p>Meticulous Stoves</p>
        </div>
        <div class="services-serve">
          <p>Customer Support</p>
        </div>
      </div>
    </div>
    <div class="services-3d">3d</div>
  </div>

  <div class="se-featured">
    <h1 class="featured-heading">
      <span>Featured</span><br />
      Find out what has been<br />
      said about us on media.
    </h1>

    <div class="featured-main">
      <div class="featured-wrapper">
        <img src="" alt="" />
        <h3 class="featured-title-green">November 2nd 2020</h3>
        <h3 class="featured-title">
          Reducing Deforestation<br />
          Africa’s Rwanda
        </h3>
        <p class="featured-par">
          To reduce deforestation, Rwanda aims to diminish the usage of biomass for cooking.
          Werecently visited
        </p>
        <a href="" class="featured-link"> Read More </a>
      </div>
      <div class="featured-wrapper">
        <img src="" alt="" />
        <h3 class="featured-title-green">November 2nd 2020</h3>
        <h3 class="featured-title">
          Reducing Deforestation<br />
          Africa’s Rwanda
        </h3>
        <p class="featured-par">
          To reduce deforestation, Rwanda aims to diminish the usage of biomass for cooking.
          Werecently visited
        </p>
        <a href="" class="featured-link"> Read More </a>
      </div>
      <div class="featured-wrapper">
        <img src="" alt="" />
        <h3 class="featured-title-green">November 2nd 2020</h3>
        <h3 class="featured-title">
          Reducing Deforestation<br />
          Africa’s Rwanda
        </h3>
        <p class="featured-par">
          To reduce deforestation, Rwanda aims to diminish the usage of biomass for cooking.
          Werecently visited
        </p>
        <a href="" class="featured-link"> Read More </a>
      </div>
    </div>
  </div>

  <section class="se-contacts">
    <h1 class="contacts-4">
      <span>Contacts</span><br />
      Have a chat with us<br />
      we’re always here for you.
    </h1>

    <form action="" class="form">
      <div class="form-wrpp">
        <div class="contacts-form">
          <label for="name">name</label>
          <input id="name" type="text" />
        </div>
        <div class="contacts-form">
          <label for="email">email</label>
          <input id="email" type="email" />
        </div>
      </div>

      <div class="form-wrpp">
        <div class="contacts-form">
          <label for="number">number</label>
          <input id="number" type="number" />
        </div>
        <div class="contacts-form">
          <label for="location">location</label>
          <input id="location" type="text" />
        </div>
      </div>

      <div class="contacts-form">
        <label for="message">message</label>
      </div>
      <button>Send</button>
    </form>
  </section>

  <div class="se-footer">
    <div class="footer-header">
      <div class="logo">
        <p>
          Oak<br />
          Investments<br />
          Limited
        </p>
      </div>

      <form action="/search" method="GET" class="search">
        <input type="search" name="query" placeholder="Search..." />
        <button type="submit">icon</button>
      </form>
    </div>

    <div class="footer-links">
      <div class="links">
        <p>
          Headquarters – Kacyiru KG 7<br />
          Factory – Mageragere, Nyarugenge
        </p>
        <a href=""> oakinvestmentrwanda@gmail.com </a>
      </div>
      <div class="links">
        <p>social media</p>
        <a href="">instagram</a>
        <a href="">facebook</a>
        <a href="">linked</a>
      </div>
      <div class="links">
        <p>social media</p>
        <a href="">Home</a>
        <a href="">About</a>
        <a href="">Services</a>
        <a href="">Products</a>
        <a href="">Featured</a>
        <a href="">Contact Us</a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.se-hero {
  display: flex;
  flex-direction: column;
  height: calc(100vh - 71px);
  padding: 32px 112px;
  gap: 72px;
  align-self: flex-end;
  margin-top: 71px;
  justify-content: flex-end;
  .hero-heading {
    display: flex;
    flex-direction: column;
    gap: 24px;
  }

  .hero-rating {
    display: flex;

    .hero-rating-wrapper {
      margin-right: 32px;
    }
  }
}

/*  */
.se-about {
  display: flex;
  padding: 32px 112px;
  height: calc(100vh - 71px);
  margin-top: 71px;

  .about-wrapper {
    height: 60vh;
    display: flex;
    flex-direction: column;
    gap: 32px;

    width: 45vw;
  }
}

/*  */
.se-products {
  display: flex;
  flex-direction: column;
  padding: 32px 112px;
  gap: 72px;
  margin-top: 71px;

  .products-wrapper {
    display: flex;
    gap: 32px;
    margin: 16px 0;
    height: calc(100vh - 71px);
    .product {
      border-radius: 8px;
      width: 100%;
      height: 100%;
      background-color: rgb(0, 0, 0, 0.25);
      padding: 32px;
      display: flex;
      flex-direction: column;
      justify-content: flex-end;
      gap: 16px;
    }
  }
}

.se-services {
  display: flex;
  padding: 32px 112px;
  gap: 72px;
  height: calc(100vh - 71px);
  margin-top: 71px;

  .services-main {
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    height: 100%;

    .services-title {
    }

    .services-wrapper {
      display: flex;
      flex-direction: column;
      gap: 16px;

      .services-serve {
        padding: 16px 8px;
        border: 1px solid #0c4f26;
        border-radius: 8px;
        /* width: 50%; */
      }
    }
  }
}

.se-featured {
  display: flex;
  flex-direction: column;
  gap: 72px;
  padding: 32px 112px;
  gap: 72px;
  margin-top: 71px;

  .featured-heading {
  }

  .featured-main {
    display: flex;
    gap: 32px;
    .featured-wrapper {
      height: 80vh;
      flex-grow: 1;
      border: 1px solid #0c4f26;
    }
  }
}

.se-contacts {
  display: flex;
  flex-direction: column;
  gap: 72px;
  padding: 32px 112px;
  gap: 72px;
  height: calc(100vh - 71px);
  margin-top: 71px;
  .form {
    display: flex;
    flex-direction: column;
    gap: 72px;
    .form-wrpp {
      width: 100%;
      display: flex;
      gap: 72px;

      .contacts-form {
        width: 100%;
        display: flex;
        flex-direction: column;
        gap: 16px;

        label {
        }

        input {
          border-bottom: 1px solid black;
        }
      }
    }
  }
}

.se-footer {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  padding: 32px 112px;
  gap: 72px;
  height: calc(100vh - 71px);
  margin-top: 71px;
  background-color: #0f301b;
  color: white;

  .footer-header {
    display: flex;
    justify-content: space-between;
    width: 100%;

    .search {
      padding: 8px 16px;
      background-color: #427656;
      height: fit-content;
      border-radius: 32px;

      input {
        color: #ffffff;
      }
    }
  }

  .footer-links {
    display: flex;
    justify-content: space-between;
    width: 100%;

    .links {
      display: flex;
      flex-direction: column;
      gap: 16px;
    }
  }
}
</style>
