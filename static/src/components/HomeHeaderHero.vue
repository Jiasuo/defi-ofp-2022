<script setup>
  
</script>

<template>
  <!-- Container -->
  <div class="heroContainer">
    <!-- Content area -->
    <div class="contentContainer">
      <!-- Presentation -->
      <p class="presentation">Je suis fullstack designer</p>
      <!-- Title -->
      <h1><span class="secondary">Hola, mi nombre es</span><br/><strong>Olivier.</strong></h1>
      <!-- Description -->
      <p class="description">Développement : Environnement LAMP, Zend Framework, ExtJS, Webservices, AMFPHP, API Google Maps, Facebook Open Graph, API Twitter</p>
      <p class="description second">Directeur technique Webedia Madrid</p>
      <!-- CTAs -->
      <div class="ctas">
        <button class="main">Portfolio</button>
        <button class="secondary">Contact</button>
      </div>
    </div>
    <!-- Image -->
    <aside class="imageContainer">
      <img src="../assets/img/hero_image.jpg" alt="Photo de profil d'Olivier Depiesse">
    </aside>
  </div>
</template>

<style scoped>
  /* COMPONENT CONTAINER*/
  .heroContainer{
    /* Vertical margin between container and top bar */
    margin-top: 63.93px;
    /* Internal horizontal space with page's left */
    padding-left: 14.09%;
    /* Children's display */
    /* display: flex; */
    /* Alignment on main axis (horizontal) */
    /* justify-content: space-between; */
    /* Center direct children on cross-axis (vertical) */
    /* align-items: center; */
    position: relative;
  }
  /* #region CONTENT */
  /*    Container */
  .contentContainer{
    /* Set container's width */
    width: 32.42%;
  }
  /*    Presentation */
  .presentation{
    /* Set font style (font-size/line-height and font-family) */
    font: 0.875rem/1.5rem "Roboto", sans-serif;
    /* Set letter-spacing */
    letter-spacing: 0.25em;
    /* Text is uppercased */
    text-transform: uppercase;
    /* Set element's position to relative for the underline purpose */
    position: relative;
    /* Prevent text line return */
    white-space: nowrap;
  }
  /*      Presentation underline */
  .presentation::after{
    /* Empty content */
    content: "";
    /* Set sizes */
    width: 73px;
    height: 3px;
    /* Set positioning */
    position: absolute;
    left: 0;
    bottom: -10px;
    /* Set line color */
    background-color: var(--secondary);
  }
  /*    Title */
  h1{
    /* Set margins */
    margin-top: 33px;
    /* Set font-size */
    font-size: 72px;
    /* Set line-height */
    line-height: 1.4;
    /* Set letter-spacing */
    letter-spacing: -3px;
  }
  /*      secondary part */
  h1 .secondary{
    /* Prevent line return */
    white-space: nowrap;
    /* Set relative font-size for responsive consistency */
    /*    (consistent until next breakpoint: 1080px) */
    font-size: clamp(3.375rem, 3.87vw, 4.5rem)
  }
  /*      Title's core */
  h1 strong{
    /* Font weight */
    font-weight: 700;
    /* Different letter-spacing */
    letter-spacing: -1px;
    /* Different color */
    color: var(--secondary);
  }
  /*    Description */
  /*      First paragraph */
  .description{
    /* Set block size */
    width: 441px;
    /* Set block positionning */
    margin-top: 16px;
    /* Set text style to pre-registered variable "--paragraph" */
    font: var(--paragraph);
  }
  /*      Second paragraph */
  .description.second{
    /* Different margin-top */
    margin-top: 24px;
  }
  /*    CTAs */
  .ctas{
    /* Set container's spacing */
    margin-top: 90px;
    /* Set block size */
    width: 277px;
    /* Set children layout */
    display: flex;
    /* Align children horizontally */
    justify-content: space-between;
    /* Align children vertically */
    align-items: center;
  }
  /*      shared button properties */
  button{
    /* Same height */
    height: 47px;
    /* Approximately same horizontal padding */
    padding: 0 32px;
    /* Vertical padding offset */
    padding-top: 1px;
    /* Same border-radius */
    border-radius: 50px;
    /* Same border-width */
    border: 2px solid transparent;
    /* Default background-color */
    background-color: transparent;
    /* Same font style */
    font: 0.875rem/1.4875rem "Roboto", sans-serif;
    /* Approximately same internal text display */
    display: flex;
    /*    Center vertically */
    align-items: center;
    /*    Center horizontally */
    justify-content: center;
    /* Same cursor style */
    cursor: pointer;
  }
  /*      Main button style */
  button.main{
    /* background color */
    background-color: var(--red);
    /* border color */
    border-color: var(--red);
  }
  /*      Secondary button style */
  button.secondary{
    /* Padding right offset */
    padding-right: 47px;
    /* Border color */
    border-color: var(--secondary);
    /* Text color */
    color: var(--secondary);
  }
  /* #endregion */

  /* #region IMAGE */
  /* Container */
  .imageContainer{
    /* Set container's position to absolute for positionning */
    /*    and sizing */
    position: absolute;
    /* Attach to top of parent */
    top: 0;
    /* Attach to right of parent */
    right: 0;
    /* Set container size */
    /*    (Relative units because block should occupy same space) */
    width: 41.06%;
    height: 100%;
  }
  /* Inner image */
  .imageContainer img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    object-position: 40% center;
    vertical-align: middle;
  }
  /* #endregion */
</style>