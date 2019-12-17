<template>
  <div class="About2">
    <h1>Natural beaty</h1>
<p>Arizona is a land of beauty. Home to canyons, mountains, deserts, forests, and riparian areas, Arizona is a state where every turn features a stunning landscape. Today, we're going to honor that natural beauty by looking at some of our state's favorite locations.<p>
<font color="green">This is some text!</font>
<img alt="Vue logo" src="../assets/Cactus.jpg" />
<!-- Collapse -->
    <div>
      <b-button v-b-toggle.collapse-1 variant="primary">Grand canyons</b-button>
      <b-collapse id="collapse-1" class="mt-2">
        <b-card>
          <p class="card-text">the iconic Grand Canyon draws oohs and aahs from visitors perched at the edge of its towering cliffs. Carved by the copper-colored Colorado River, the colorful rock layers record billions of years of history and hide many unique species.</p>
          <img alt="Vue logo" src="../assets/map.png" />

          <b-button v-b-toggle.collapse-1-inner size="sm">Major cities</b-button>
          <b-collapse id="collapse-1-inner" class="mt-2">
            <b-card>Hello!</b-card>
            <div>
              <b-table striped hover :items="items"></b-table>
            </div>

          </b-collapse>
        </b-card>
      </b-collapse>
    </div>

</div>
</template>

<script>
  export default {
    data() {
      return {
        items: [
          { Population: 1.6, City: 'Phoenix', County: 'Maricopa' },
          { Population:535677, City: 'Tucson', County: 'Pima' },
          { Population: 496401, City: 'Mesa', County: 'Maricopa' },
          { Population: 253458, City: 'Chandler', County: 'Maricopa' }
        ]
      }
    }
  }
</script>
