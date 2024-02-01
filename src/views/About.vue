<script setup>
import AboutItem from '../components/AboutItem.vue'

</script>


<template>
  <div class="about">
    <AboutItem>
      <template v-slot:title>Raid Times</template>
      <template v-slot:body>
        <p>
        <ul>
          <li>Main Raid: <span class="indigo">Tuesday, Wednesday</span></li>
          <li>Optional Heroic Raid: <span class="indigo">Friday</span></li>
          <li>Raid Times: <span class=indigo>7pm - 10pm CST</span></li>
        </ul>
        </p>
      </template>
      <template v-slot:footer></template>
    </AboutItem>

    <AboutItem>
      <template v-slot:title>Progress</template>
      <template v-slot:body>
        <p>
        <ul>
          <li>Amirdrassil, the Dream's Hope: <a
              href="https://www.warcraftlogs.com/embed/guild-progress-tile/35?difficulty=5&guild=688437">6/9M</a></li>
          <li>Aberrus, the Shadowed Crucible: <span class="indigo">7/9M</span></li>
        </ul>
        </p>
      </template>
      <template v-slot:footer></template>
    </AboutItem>

    <AboutItem>
      <template v-slot:title>About Us</template>
      <template v-slot:body>
        <p>
          <i>Must Be Bugged</i> is a guild formed during S1 of Dragonflight.
          The core raid team is a bunch of competitive goofballs who love to mess with each other during downtime while
          pushing each other during progression.
          Outside of raid we have M+ teams running most nights and an active discord for socializing or other games.
        </p>
      </template>
      <template v-slot:footer></template>
    </AboutItem>
  </div>
</template>
  
<style>
.about {
  display: flex;
  align-items: center;
  flex-direction: column;
}

@media (min-width: 1024px) {
  .about {
    min-height: 60vh;
    max-height: 60vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    max-width: 700px;
    align-items: normal;
  }
}
</style>
  