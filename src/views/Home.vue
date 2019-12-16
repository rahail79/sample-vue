<template>
  <div class="home">

    <img alt="Vue logo" style="width: 400px" src="../assets/download.png" />
 />
    <h1>Arizona</h1>
    <HelloWorld msg="Welcome to Your Vue.js App" />


    <!-- Collapse -->
    <div>
  <b-button v-b-toggle.collapse-1 variant="primary">Life</b-button>

  <b-collapse id="collapse-1" class="mt-2">
    <b-card>
      <!-- <p class="card-text">Collapse contents Here</p> -->
      <p> So, with that in mind, I can tell you that I absolutely love it here. The weather is the first part of the story. Not having to shovel snow or cut grass is amazing. Winter is like a long fall with jeans and sweatshirt weather at its worst (who doesn’t love that?). Spring in the desert is so beautiful, and now in April, I am already swimming. It’s Saturday morning, the birds are singing, and it’s beautiful. The town I live in has bike trails everywhere, and you can be as active as you want. It’s truly a runners paradise. The lifestyle here is very laid back and pleasant. People reached out to me, and I am starting to make friends. There is never any shortage of fun things to do, especially if you like the outdoors. I could hike or explore something different every weekend. There are festivals and lots of artists and art inspired places to visit. There are cool little towns that are like out of a movie. I went to a Diamondbacks game last weekend, and it was a blast. The highways are a breeze to drive, and it’s super easy to get around the state. As for the schools, my daughter loves hers, and that is saying something for a kid who had to change high schools. The state must do something about teacher salaries and education spending</p>
      <img alt="Vue logo" style="width: 400px" src="../assets/arizona2.jpg" />

      <b-button v-b-toggle.collapse-1-inner size="sm">Location</b-button>
      <b-collapse id="collapse-1-inner" class="mt-2">
        <b-card>Arizona is located in the southwestern quadrant of the conterminous states, bordered by California to the west, Nevada to the northwest, Utah to the north, New Mexico to the east, and the Mexican state of Sonora to the south</b-card>

     />
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
