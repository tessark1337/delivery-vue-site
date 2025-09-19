<template>
  <footer class="footer">
    <div class="container">
      <div class="footer-box">
        <router-link to="/" class="footer-logo logo">
          <img src="../assets/images/logo.png" alt="logo" />
        </router-link>
        <div class="footer-nav">
          <ul>
            <li>Ресторанам</li>
            <li>Курьерам</li>
            <li>Пресс-центр</li>
          </ul>
        </div>
        <div class="footer-social">
          <img src="../assets/images/socials/INST.png" alt="INST" />
          <img src="../assets/images/socials/FB.png" alt="FB" />
          <img src="../assets/images/socials/VK.png" alt="VK" />
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
    min-height: 156px;
    display: flex;
    align-items: center;
    padding: 60px 0;
}

.footer-box {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 36px;
    flex-wrap: wrap;
}

.footer-nav {
    flex-grow: 1;
}

.footer-nav ul {
    display: flex;
    align-items: center;
    list-style: none;
    padding: 0;
    margin: 0;
    gap: 15px;
}

.footer-nav ul li {
    color: #595959;
    font-weight: 400;
    font-size: 18px;
    line-height: 100%;
    letter-spacing: 0%;
}

.footer-social {
    display: flex;
    align-items: center;
    justify-content: flex-end;
    gap: 20px;
}
</style>