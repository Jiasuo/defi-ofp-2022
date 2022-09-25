<script setup>

</script>

<template>
  <!-- CONTAINER -->
  <section class="servicesContainer">
    <!-- INTRO -->
    <div class="intro">
      <!--  Title -->
      <h2>Compétences</h2>
      <!--  Description -->
      <p class="introDescription">It doesn’t matter how great your product or service<br/>is if your copy does not captivate your audience.</p>
    </div>
    <!-- SERVICE LIST -->
    <ul class="serviceList">
      <!--  Service -->
      <li class="service technic">
        <!--    Icon -->
        <div class="serviceIcon">
          <img src="../assets/img/service_1.svg" alt="Icône service technique" class="serviceVector">
        </div>
        <!--    Title -->
        <div class="h3 serviceName">Technique</div>
        <!--    Description -->
        <p class="serviceDescription">Voluptatum deleniti atque corrupti quos dolores et quas molestias excepturi</p>
      </li>
      <!--  Service -->
      <li class="service project">
      <!--    Icon -->
        <div class="serviceIcon">
          <img src="../assets/img/service_2.svg" alt="Icône service Gestion de projet" class="serviceVector">
        </div>
      <!--    Title -->
        <div class="h3 serviceName">Gestion de projet</div>
      <!--    Description -->
        <p class="serviceDescription">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore</p>
      </li>
      <!--  Service -->
      <li class="service management">
      <!--    Icon -->
        <div class="serviceIcon">
          <img src="../assets/img/service_3.svg" alt="Icône service management" class="serviceVector">
        </div>
      <!--    Title -->
        <div class="h3 serviceName">Management</div>
      <!--    Description -->
        <p class="serviceDescription">Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia</p>
      </li>
      <!--  Service -->
      <li class="service languages">
      <!--    Icon -->
        <div class="serviceIcon">
          <img src="../assets/img/service_4.svg" alt="Icône service Langues" class="serviceVector">
        </div>
      <!--    Title -->
        <div class="h3 serviceName">Langues</div>
      <!--    Description -->
        <p class="serviceDescription">At vero eos et accusamus et iusto odio dignissimos ducimus qui blanditiis</p>
      </li>
    </ul>
  </section>
</template>

<style scoped>
/* CONTAINER */
.servicesContainer{
  /* Spacing */
  padding: 152px 14.09% 216px 14.09%;
  /* Background color */
  background-color: var(--bg2);
  /* Children element positioning */
  display: flex;
  flex-direction: column;
  /* centered on vertical axis (cross) */
  align-items: center;
}
/* #region INTRO */
.intro{
  /* Shared text style */
  text-align: center;
}
/*    Title */
h2{
  /* Set font style to H2 */
  font: var(--H2);
  /* Set position to relative for the underline */
  position: relative;
}
/*      Underline */
h2::after{
  content: "";
  /* Set position to absolute */
  position: absolute;
  /* Sizing */
  width: 73px;
  height: 3px;
  /* Spacing */
  /* Centered horizontally */
  left: 50%;
  transform: translateX(-50%);
  /* 9px from bottom of text */
  bottom: -9px;
  background-color: var(--secondary);
}
/*    Description */
.introDescription{
  /* Spacing */
  margin-top: 45px;
  /* Font */
  font: var(--paragraph2);
}
/* #endregion */

/* #region SERVICE LIST */
/* Container */
.serviceList{
  /* Spacing */
  margin-top: 116px;
  /* Sizing */
  width: 100%;
  height: 182px;
  /* Children layout */
  display: flex;
  justify-content: space-between;
}
/*    Service item (shared) */
.service{
  /* Sizing */
  max-width: 192px;
  height: 100%;
  /* Children layout */
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}
/*      Service icon */
.serviceIcon{
  /* Sizing */
  width: 52px;
  height: 52px;
  /* Shape */
  border-radius: 18px;
  /* Colors */
  background-color: var(--white);
  /* Child layout */
  display: flex;
  align-items: center;
  justify-content: center;
}
/*        Service icon vector */
.serviceVector{
  object-fit: contain;
}
/*      Service name */
.serviceName{
  /* Spacing */
  margin-top: 19px;
  /* Font */
  font: var(--H4);
}
/*      Service description */
.serviceDescription{
  /* Spacing */
  margin-top: 16px;
  /* Font */
  font: var(--paragraph2);
  /* Text color */
  color: var(--icon)
}
/*      Specific vector sizes */
.technic .serviceVector{
  width: 19.56px;
  height: 20px;
  /* Offset */
  margin-right: 10.24px;
}
.project .serviceVector{
  width: 18.27px;
  height: 18.68px;
}
.management .serviceVector{
  width: 18.75px;
  height: 19.17px;
}
.languages .serviceVector{
  width: 19px;
  height: 19.22px;
}
/* #endregion */
</style>