<template>
  <div class="home">

    <img alt="Arizona" src="../assets/download.png" />
    <h1>Arizona</h1>
    <HelloWorld msg="Welcome to Your Vue.js App" />


    <!-- Collapse -->
    <div>
  <b-button v-b-toggle.collapse-1 variant="primary">History</b-button>

  <b-collapse id="collapse-1" class="mt-2">
    <b-card>
      <!-- <p class="card-text">Collapse contents Here</p> -->
      <p>Arizona, the Grand Canyon state, achieved statehood on February 14, 1912, the last of the 48 coterminous United States to be admitted to the union. Originally part of New Mexico, the land was ceded to the United States in 1848, and became a separate territory in 1863</p>
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
