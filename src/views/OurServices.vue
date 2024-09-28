<script setup>

import ServiceCards from '@/components/ServiceCards.vue'
</script>

<template>
  <main class="our-services">
    <div class="our-services__inner">
      <div class="our-services__text">
        <h1 class="our-services__text main">Our services</h1>
        <hr class="our-services__text line"/>
        <p class="our-services__text sub">
          We provide to you the best choices for you. Adjust it to your health
          needs and make sure your undergo treatment <br/> with our highly
          qualified doctors you can consult with us which type of service is
          suitable for your health
        </p>
      </div>
      <div class="our-services__cards">
        <service-cards/>
      </div>
    </div>
  </main>
</template>

<style scoped lang="scss">
.our-services {
  .our-services__inner {
    margin-top: 70px;
    display: flex;
    flex-direction: column;
    align-items: center;

    .our-services__text {
      display: flex;
      flex-direction: column;
      align-items: center;

      .main {
        width: fit-content;
        font-size: 28px;
        font-weight: 700;
        line-height: 56px;
        text-align: left;
      }

      .line {
        width: 60px;
        margin-bottom: 25px;
      }

      .sub {
        color: #7D7987;
        font-size: 14px;
        font-weight: 300;
        line-height: 20px;
        text-align: center;
      }
    }

    .our-services__cards {
      margin-top: 50px;
      display: grid;
      grid-template-columns: repeat(3, 250px);
    }

  }
}
</style>
