<template>
<section main>
  <b-container>
    <h1 class="title-color">What on this month @ East London Theatres</h1>
    <h2>March 2019</h2>
    <br>
    <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "An Evening with Paolo Di Canio">
  <p class="title-color">

    Broadway Theatre Barking<br>
    Thurs 21 - Sat 23 March 2019
    </p>
    <b-button href="http://bit.ly/2O857LG" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Lord of the Flies">
  <p class="title-color">
    Greenwich Theatre<br>
    Wed 20 March - Sat 30 March 2019
    </p>
    <b-button href="http://bit.ly/2CKtih3" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Young Producers">
  <p class="title-color">
    Hackney Empire<br>
    Tues 08 Jan 2019- Tues 16 Apr 2019

    </p>
    <b-button href="http://bit.ly/2JnhX7Z" target="_blank" variant="info">open</b-button>

</b-card>
    </b-card-group>

        <b-card-group deck
      class="mb-3">

<b-card bg-variant="dark" text-variant="white" title= "Youth Arts Board : 16-19 yrs">
  <p class="title-color">
    Hoxton Hall<br>
    Tuesday's @ 6pm - 8pm

    </p>
    <b-button href="http://bit.ly/2EX7IsG" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Chiargo">

  <p class="title-color">
    Kenneth More Theatre Ilford<br>
    Thu 21 March - Sat 23  2019

    </p>
    <b-button href="http://bit.ly/2D9UPtc" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Local artists Art Exhibition">
  <p class="title-color">

  <p class="title-color">
    Queen's Theatre Hornchurch<br>
    Mon 11 - Sun 24 March 2019
    </p>
    <b-button href="http://bit.ly/2Soh3MB" target="_blank" variant="info">open</b-button>

</b-card>


    </b-card-group>
    <b-card-group deck
      class="mb-3">

      <b-card bg-variant="dark" text-variant="white" title= "Equus">
        <b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/yM2jqiDSkjQ"
          allowfullscreen
  ></b-embed>
  <p class="title-color">
    Theatre Royal Stratford East<br>
    Fri 15 Feb - Sat 23 Mar 2019

    </p>
    <b-button href="http://bit.ly/2JjU3Kr" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "Drake">
  <p class="title-color">
    The O2 arena<br>
    Mon 1 April - Mon 11 April 2019

    </p>
    <b-button href="http://bit.ly/2PpXswU" target="_blank" variant="info">open</b-button>

</b-card>

<b-card bg-variant="dark" text-variant="white" title= "The Crucible">
  <p class="title-color">

    The Yard Hackney<br>
    Wed 27 March — Thurs 11 May 2019

    </p>
    <b-button href="http://bit.ly/2OYFsdx" target="_blank" variant="info">open</b-button>

</b-card>


    </b-card-group>
      <div>
      <b-card-group deck
      class="mb-3">
    <b-card bg-variant="dark" text-variant="white" title= "">
  <p class="title-color">

  </p>
  <b-button-group>
  <b-button href="http://bit.ly/2O857LG" target="_blank" variant="info">Broadway Theatre Barking</b-button>
  <b-button href="http://bit.ly/2CKtih3" target="_blank" variant="info">Greenwich Theatre</b-button>
  <b-button href="http://bit.ly/2JnhX7Z" target="_blank" variant="info">Hackney Empire</b-button>
  </b-button-group>
  <br>
  <br>
  <b-button-group>
  <b-button href="http://bit.ly/2EX7IsG" target="_blank" variant="info">Hoxton Hall</b-button>
  <b-button href="http://bit.ly/2D9UPtc" target="_blank" variant="info">Kenneth More Theatre Ilford</b-button>
  <b-button href="http://bit.ly/2Soh3MB" target="_blank" variant="info">Queen's Theatre Hornchurch</b-button>
  </b-button-group>
  <br>
  <br>
  <b-button-group>
  <b-button href="http://bit.ly/2JjU3Kr" target="_blank" variant="info">Theatre Royal Stratford East</b-button>
  <b-button href="http://bit.ly/2PpXswU" target="_blank" variant="info">The 02</b-button>
  <b-button href="http://bit.ly/2OYFsdx" target="_blank" variant="info">The Yard Hackney</b-button>
  </b-button-group>

  </b-card>
  </b-card-group>

</div>

      </b-container>
      </section>

</template>

<script>
export default {
  head () {
    return {
      titleTemplate: '%s theatres',
      meta         : [
        { hid: 'description', name: 'description', content: 'Whats on at the east London Theatres this month, March 2019, Hackney empire, Kenneth More Theatre Ilford, Theatre Royal Stratford East and more!' }
      ]
    }
  }
}
</script>
