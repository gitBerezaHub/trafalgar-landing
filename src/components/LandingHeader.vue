<script setup>

</script>

<template>
  <header class="header">
    <div class="header__inner">
      <a class="header__logo logo" href="/">
        <img class="header__logo-image" src="@/assets/trafalgar-logo.png"
             alt="" width="160">
      </a>
      <nav class="header__menu">
        <ul class="header__menu-list">
          <li class="header__menu-item chosen">Home</li>
          <li class="header__menu-item">Find a doctor</li>
          <li class="header__menu-item">Apps</li>
          <li class="header__menu-item">Testimonials</li>
          <li class="header__menu-item">About us</li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<style scoped lang="scss">
.header {
  .header__inner {
    display: flex;
    height: 10vh;
    padding: 30px 60px;
    justify-content: space-between;
    align-items: center;
  }

  .header__menu {
    .header__menu-list {
      display: flex;
      align-items: center;
      justify-content: center;

      .header__menu-item {
        font-size: 18px;
        font-weight: 400;
        line-height: 22.59px;
        text-align: left;
        margin-left: 40px;
        color: rgb(31, 21, 52, 0.5);
      }

      .chosen {
       font-weight: 700;
        color: #1F1534;
      }
    }
  }
}
</style>
