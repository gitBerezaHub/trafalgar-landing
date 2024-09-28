<script setup>

</script>

<template>
  <main class="main">
    <div class="main__inner">
      <div class="main__left">
        <div class="main__welcome">
          <h1 class="main__welcome-main-text">Virtual healthcare <br/> for you
          </h1>
          <p class="main__welcome-sub-text">
            Trafalgar provides progressive, and affordable <br/>
            healthcare, accessible on mobile and online <br/>
            for everyone
          </p>
          <button class="main__consult-button">
            Consult today
          </button>
        </div>
      </div>
      <div class="main__right">
        <img src="../assets/welcome.png" alt="" width="462">
      </div>
    </div>
  </main>
</template>

<style scoped lang="scss">
.main {
  .main__inner {
    display: flex;
    flex-direction: row;
  }

  .main__left, .main__right {
    width: 50vw;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .main__left {
    display: flex;
    flex-direction: column;
    text-align: left;
    .main__welcome {
      .main__welcome-main-text {
        font-size: 48px;
        font-weight: 700;
        line-height: 46px;
        text-align: left;
        margin-bottom: 30px;
      }

      .main__welcome-sub-text {
        font-size: 16px;
        font-weight: 300;
        line-height: 28px;
        text-align: left;
        color: #7D7987;
        margin-bottom: 40px;
      }
    }

    .main__consult-button {
      background-color: #458FF6;
      border-radius: 55px;
      border: none;
      color: #fff;
      font-size: 16px;
      font-weight: 700;
      line-height: 40px;
      width: 15vw;
      aspect-ratio: 4 / 1;
    }
  }
}
</style>
