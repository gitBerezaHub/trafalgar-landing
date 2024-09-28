<script setup>

const cards = [
  {
    img: require('@/assets/search.png'),
    name: 'Search doctor',
    text: 'Choose your doctor from thousands \n' +
        'of specialist, general, and trusted\n' +
        'hospitals'
  },
  {
    img: require('@/assets/pharmacy.png'),
    name: 'Online pharmacy',
    text: 'Buy  your medicines with our \n' +
        'mobile application with a simple \n' +
        ' delivery system'
  },
  {
    img: require('@/assets/consultation.png'),
    name: 'Consultation',
    text: 'Free consultation with our trusted \n' +
        'doctors and get the best \n' +
        'recommendation'
  },
  {
    img: require('@/assets/details.png'),
    name: 'Details info',
    text: 'Free consultation with our trusted \n' +
        'doctors and get the best \b' +
        'recommendation'
  },
  {
    img: require('@/assets/emergency.png'),
    name: 'Emergency care',
    text: 'You can get 24/7 urgent care for\n' +
        ' yourself or your children and your\n' +
        ' lovely family'
  },
  {
    img: require('@/assets/tracking.png'),
    name: 'Tracking',
    text: 'Track and save your medical history \n' +
        'and health data'
  }
]
</script>

<template>
  <div class="card" v-for="card in cards" :key="card">
    <div class="card__inner">
      <img class="card__image" :src="card.img" :alt="card.name" height="80">
      <h1 class="card__name">{{ card.name }}</h1>
      <p class="card__text">
        {{ card.text }}
      </p>
    </div>
  </div>
</template>

<style scoped lang="scss">
.card {
  aspect-ratio: 1 / 1;
  border-radius: 20px;
  margin: 15px;
  border: 1px solid #fff;

  &:hover {
    border: 1px solid #DEEEFE;
  }

  .card__inner {
    padding: 20px;

    .card__name {
      font-size: 20px;
      font-weight: 700;
      line-height: 56px;
      text-align: left;
    }

    .card__text {
      font-size: 12px;
      font-weight: 300;
      line-height: 24px;
      text-align: left;
      color: #7D7987;
    }
  }
}
</style>
