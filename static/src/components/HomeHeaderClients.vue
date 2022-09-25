<script setup>

</script>

<template>
  <!-- Container -->
  <div class="clientsContainer">
    <!--  Title -->
    <h2>Clients</h2>
    <!--  Client list -->
    <ul class="clientList">
      <!--    Client -->
      <li class="client sega"><img src="../assets/img/client_1.png" alt="Logo Sega" class="clientLogo"></li>
      <!--    Client -->
      <li class="client ubisoft"><img src="../assets/img/client_2.png" alt="Logo Ubisoft" class="clientLogo"></li>
      <!--    Client -->
      <li class="client microsoft"><img src="../assets/img/client_3.png" alt="Logo Microsoft" class="clientLogo"></li>
      <!--    Client -->
      <li class="client ea"><img src="../assets/img/client_4.png" alt="Logo Electronics Arts" class="clientLogo"></li>
      <!--    Client -->
      <li class="client capcom"><img src="../assets/img/client_5.png" alt="Logo Capcom" class="clientLogo"></li>
      <!--    Client -->
      <li class="client bethesda"><img src="../assets/img/client_6.png" alt="Logo Bethesda" class="clientLogo"></li>
    </ul>
  </div>
</template>

<style scoped>
/* CONTAINER */
.clientsContainer{
  /* Spacing */
  margin: 0 auto;
  margin-top: 214.1px;
  /* Sizing */
  width: 1015.15px;
  /* Children display */
  display: flex;
  /* Go vertically */
  flex-direction: column;
  /* Center horizontally */
  align-items: center;
}
/* TITLE */
h2{
  /* Font */
  font: 0.75rem/1.91875rem "Roboto", sans-serif;
  /* Letter spacing */
  letter-spacing: 3px;
  /* Upper case */
  text-transform: uppercase;
}
/* CLIENT LIST */
.clientList{
  /* Spacing */
  margin-top: 7.53px;
  /* Sizing */
  width: 100%;
  /* Flex horizontal */
  display: flex;
  /* Distribute margins evenly */
  justify-content: space-between;
  /* Center vertically */
  align-items: center;
}
/*  Shared client image properties */
.client img{
  /* Occupy all width */
  width: 100%;
  /* Occupy all height */
  height: 100%;
  /* Fit all space */
  object-fit: contain;
}
/*  Individual client sizing */
.sega{
  width: 109px;
  height: 36.36px;
}
.ubisoft{
  width: 73.45px;
  height: 67.48px;
}
.microsoft{
  width: 151px;
  height: 36px;
}
.ea{
  width: 167.11px;
  height: 30px;
}
.capcom{
  width: 131.2px;
  height: 24.02px;
}
.bethesda{
  width: 158.57px;
  height: 22.99px;
}
</style>