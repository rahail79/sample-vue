<template>
  <div class="about">
    <b-container>
      <b-card>
<img alt="Vue logo" src="../assets/Arizona.jpg" />

  <h1>Things to do/Climate</h1>
<!-- Collapse -->
  <div>
    <b-button v-b-toggle.collapse-1 variant="primary">Things to do</b-button>
    <b-collapse id="collapse-1" class="mt-2">
      <b-card>
        <p class="Activitys">Flagstaff, a ponderosa pine–covered mountain town, is a major gateway to the Grand Canyon. Other natural sites include Saguaro National Park, protecting cactus-filled Sonoran Desert landscape. Tucson is University of Arizona territory and home to the Arizona-Sonora Desert Museum.

Employment
Total employment 2016

2,379,409
Total employer establishments 2</p>
<img alt="Vue logo" style="width: 400px" src="../assets/City.jpeg" />
        <b-button v-b-toggle.collapse-1-inner size="sm">Climate</b-button>
        <b-collapse id="collapse-1-inner" class="mt-2">
          <b-card>Arizona is well known for its desert Basin and Range region in the state's southern portions, which is rich in a landscape of xerophyte plants such as the cactus. This region's topography was shaped by prehistoric volcanism, followed by the cooling-off and related subsidence. Its climate has exceptionally hot summers and mild winters. The state is less well known for its pine-covered north-central portion of the high country of the Colorado Plateau (see Arizona Mountains forests).!</b-card>

          <img alt="Vue logo" src="../assets/cactus.jpeg" />

        </b-collapse>
      </b-card>
    </b-collapse>
  </div>

</b-card>
</b-container>
  </div>
</template>

<style scoped>
.about {
}


</style>
