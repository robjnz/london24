<template>
<section main>
  <b-container>
    <h1 class="title-color">This weeks events in East London</h1>
    <h2>February 2019</h2>
    <br>
    <b-card-group deck
class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "">
<a href="#" target="_blank"><b-img src="" fluid-grow alt=""/></a>
</b-card>


<b-card bg-variant="dark" text-variant="white" title= "">
<a href="#" target="_blank"><b-img src="" fluid-grow alt=""/></a>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
<a href="#" target="_blank"><b-img src="" fluid-grow alt=""/></a>
</b-card>

</b-card-group>
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.google.com/maps/d/embed?mid=1F9WADbgsmZ44JzTDdiOnHzyfux3uOFxI" width = "640" height = "480"
          allowfullscreen
  ></b-embed>


</b-container>
      </section>

</template>

<script>
export default {
  head () {
    return {
      titleTemplate: '%s todays events',
      meta         : [
        { hid: 'description', name: 'description', content: 'This weeks events in east London sunday 20th to 27th January 2019' }
      ]
    }
  }
}
</script>
