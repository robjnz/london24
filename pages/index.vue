<template>
<section show class="showcase">
  <div class="intro" >

      <br><br>
    <b-badge pill variant="dark">
    <h1> <font color="gold"><br>Wednesday<br>27th March 2019</font></h1>
    <h2> What’s on today @ <br>the local cinemas,<br> theatres & nightclubs, <br>football matches & <br>places to visit <br>for days out <br>in east London.
</h2>

<h3 class="title-color">
  Home Game<br>Leyton Athletic F.C.<br>V<br>Walthamstow <br> @ 7.45pm
<br>
<b-button href="http://bit.ly/2LjQdCd" target="_blank" variant="info">open</b-button>
</h3>

<h3 class ="tory">
<br>Five Feet Apart<br>

<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/24YrEAGF32M"
          allowfullscreen
  ></b-embed>
    Showing today @
  <br>Cineworld

<br>
Ilford

</h3>

<b-button href="http://bit.ly/2AuCVyP" target="_blank" variant="info">open</b-button>
<br>
<br>

<h3 class="labour">In Basildon<br>
<b-embed type="iframe"
          aspect = "16by9"
          src    = "https://www.youtube.com/embed/d5ilLcjmvTE"
          allowfullscreen
  ></b-embed>
    Showing today @
  <br>Queen's Theatre Hornchurch
  <br>@<br>7.30pm
</h3>

<b-button href="http://bit.ly/2Soh3MB" target="_blank" variant="info">open</b-button>
<br><br>

    </b-badge>

    </div>


  </section>
</template>

<style scoped>
.showcase{
  background             : url(http://res.cloudinary.com/dzhbfdfa5/image/upload/v1515831480/tower_vow6im.jpg) no-repeat center center fixed;
  background-size        : cover;
  -webkit-background-size: cover;
  -moz-background-size   : cover;
  -o-background-size     : cover;
  height                 : 1500px;
  margin-top             : -75px;

}
.intro{
  margin-left : 20px;
  margin-right: 900px;
  margin-top  : 50px;
  padding-left: 30px;
  color       : ghostwhite;
  font-family : Damion;
  }

  .alert{
  margin-left : 20px;
  margin-right: 1000px;
  margin-top  : 1px;
  padding-left: 30px;
  color       : #171718;
  font-family : Damion;
  }




</style>

<script>


export default {
  components: {

}
}
</script>
