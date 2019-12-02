<template>
  <div class="home">

    <img alt="Vue logo" src="../assets/download.jpeg" />
    <h1>Arizona</h1>
    <HelloWorld msg="Welcome to Your Vue.js App" />


    <!-- Collapse -->
    <div>
  <b-button v-b-toggle.collapse-1 variant="primary">History</b-button>
  <b-collapse id="collapse-1" class="mt-2">
    <b-card>
      <p class="card-text">Collapse contents Here</p>
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
