<template>
  <div class="about">
<img alt="Vue logo" src="../assets/Arizona.jpg" />

  <h1>Economy/Climate</h1>
<!-- Collapse -->
  <div>
    <b-button v-b-toggle.collapse-1 variant="primary">Economy</b-button>
    <b-collapse id="collapse-1" class="mt-2">
      <b-card>
        <p class="card-text">The state's per capita income is $40,828, ranking 39th in the U.S. The state had a median household income of $50,448, making it 22nd in the country and just below the U.S. national mean.[78] Early in its history, Arizona's economy relied on the "five C's": copper (see Copper mining in Arizona), cotton, cattle, citrus, and climate (tourism). Copper is still extensively mined from many expansive open-pit and underground mines, accounting for two-thirds of the nation's output.

Employment
Total employment 2016

2,379,409
Total employer establishments 2</p>
        <b-button v-b-toggle.collapse-1-inner size="sm">Climate</b-button>
        <b-collapse id="collapse-1-inner" class="mt-2">
          <b-card>Arizona is well known for its desert Basin and Range region in the state's southern portions, which is rich in a landscape of xerophyte plants such as the cactus. This region's topography was shaped by prehistoric volcanism, followed by the cooling-off and related subsidence. Its climate has exceptionally hot summers and mild winters. The state is less well known for its pine-covered north-central portion of the high country of the Colorado Plateau (see Arizona Mountains forests).!</b-card>
        </b-collapse>
      </b-card>
    </b-collapse>
  </div>



  </div>
</template>
