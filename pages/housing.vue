<template>
<section main>
  <b-container>
    <b-row>
    <h1 class="title-color">Housing</h1>
  <div>

<b-card-group deck
      class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Crisis">
  <p class="title-color">

    National charity for homeless people.
    <br>
    <br>
    <br>
    </p>
    <b-button href="http://bit.ly/2xM4fWG" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Tenancy Deposit Protection">
  <p class="title-color">
    Landlord must put your deposit in a government-backed tenancy deposit scheme.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2O0zrfe" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Shelter">
  <p class="title-color">
    Shelter helps people struggling with bad housing or homelessness.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2DpTWxF" target="_blank" variant="info">open</b-button>
</b-card>
</b-card-group>


<b-card-group deck
      class="mb-3">
<b-card bg-variant="dark" text-variant="white" title= "Shp">
  <p class="title-color">
    London-wide charity working to prevent homelessness.
    <br>
    <br>
  </p>
  <b-button href="http://bit.ly/2NB5J11" target="_blank" variant="info">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Zoopla">
  <p class="title-color">
    Free search for homes to buy or rent in the UK.
    <br>
    <br>

  </p>
  <b-button href="http://bit.ly/2MVBqNk" target="_blank" variant="primary">open</b-button>
</b-card>

<b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">

    <br>
    <br>
    <br>
  </p>

</b-card>
</b-card-group>





    </div>
    </b-row>
      </b-container>
    </section>
</template>

<script>
export default {
  head () {
    return {
      titleTemplate: '%s houseing',
      meta         : [
        { hid: 'description', name: 'description', content: 'information on housing and homeless advice in east London ' }
      ]
    }
  }
}
</script>
