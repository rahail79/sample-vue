<template>
  <div class="home">

    <img alt="Vue logo" src="../assets/download.png" />
    <h1>Arizona</h1>
    <HelloWorld msg="Welcome to Your Vue.js App" />


    <!-- Collapse -->
    <div>
  <b-button v-b-toggle.collapse-1 variant="primary">History</b-button>

  <b-collapse id="collapse-1" class="mt-2">
    <b-card>
      <!-- <p class="card-text">Collapse contents Here</p> -->
      <p>The history of Arizona encompasses Spanish, Mexican, and American periods. Arizona was part of the state of Sonora, Mexico from 1822, but the settled population was small.Arizona became a state in 1912 but was primarily rural with an economy based on cattle, cotton, citrus and copper.</p>
      <img alt="Vue logo" style="width: 400px" src="../assets/arizona2.jpg" />

      <b-button v-b-toggle.collapse-1-inner size="sm">Toggle Inner Collapse</b-button>
      <b-collapse id="collapse-1-inner" class="mt-2">
        <b-card>Hello!</b-card>
      </b-collapse>
    </b-card>
  </b-collapse>
</div>

  </div>
</template>
<script>

</script>

<style>

</style>
