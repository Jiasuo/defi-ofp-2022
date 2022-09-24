<script setup>

</script>

<template>
  <div class="topBarContainer">
    <div class="topBarLeft">
      <div class="logo"><a href="javascript:;" title="Olivier Depiesse - Fullstack Designer">Olivier.</a></div>
      <div class="contactContainer">
        <a href="tel:+9876541423" class="phoneContainer" title="Vous pouvez me joindre par téléphone">
          <img src="../assets/img/phone_w.svg" alt="Icône du téléphone" class="phoneIcon">
          <span class="phoneNumber">+98 76-54-1423</span>
        </a>
        <a href="mailto:olivier.depiesse@gmail.com" class="emailContainer" title="Vous pouvez aussi me joindre par email">
          <img src="../assets/img/email_w.svg" alt="Icône de l'adresse email" class="emailIcon">
          <span class="emailAddress">olivier.depiesse@gmail.com</span>
        </a>
      </div>
    </div>
    <div class="menuContainer">
      <img src="../assets/img/burgerMenu_w.svg" alt="Icône de menu burger" class="menuIcon">
    </div>
  </div>
</template>

<style scoped>
.topBarContainer {
  height: 84px;
  padding: 0 60px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.topBarLeft {
  display: flex;
  align-items: center;
}

.logo {
  margin-left: 2px;
  font-family: "Roboto", sans-serif;
  font-size: 2rem;
  line-height: 0.8125;
  font-weight: 900;
  color: var(--white);
}

.contactContainer {
  display: flex;
  align-items: center;
  margin-left: 98px;
  font: var(--paragraph);
  color: var(--white);
}

.contactContainer>div {
  display: flex;
  align-items: center;
  cursor: pointer;
}

.phoneIcon {
  margin-top: -1px;
  width: 22px;
  height: 22px;
}

.phoneNumber {
  margin-left: 7px;
}

.emailContainer {
  margin-left: 76.83px;
}

.emailIcon {
  width: 18.33px;
  height: 18.18px;
}

.emailAddress {
  margin-left: 13.83px;
}

.menuIcon {
  cursor: pointer;
}
</style>