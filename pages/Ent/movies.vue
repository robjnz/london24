<template>
<section main>
  <b-container>
    <h1 class="title-color">Movies showing today @ east London cinemas </h1>
    <br>
    <h2>Tuesday 26th March 2019</h2>

    <b-card-group deck
    class="mb-3">
    <Dog /><!--A Dog's Way Home-->
    <Alita /><!--Alita Battle Angel -->
    <Badla /><!--Badia -->
    </b-card-group>

  <b-card-group deck
  class="mb-3 ">
    <Band /><!--Band Vaaje-->
  <Ben /><!--Ben is Back 15-->
  <Bohemian /><!--Bohemian Rhapsody -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Border /><!--Border -->
  <Bumblebee /><!--Bumblebee -->
  <Caper /><!--Capernaum -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Marvel /><!-- Captain Marvil -->
  <Cold /><!--Cold Pursuit -->
  <Escape /><!--Escape Room -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Everybody /><!--Everybody Knows -->
<Fighting /><!--Fighting With My Family -->
<Fisherman /><!--Fisherman’s Friend -->
</b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Five /><!--Five Feet Apart-->
<Glass /><!--Glass-->
<Green /><!--Green Book-->
</b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Guddiyan /><!--Guddiyan Patole -->
<Gully /><!--Gully Boy -->
<Happy /><!--Happy Death Day -->
</b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Dragonworld /><!--How to Train Your Dragon the Hidden -->
<Beale /><!--If Beale Street Could talk-->
<family /><!--Instant Family  -->
</b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Luka /><!--Luka Chuppi  -->
<Scots /><!--Mary Queen Of Scots -->
<Poppins /><!--Mary Poppins-->
</b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Bala /><!--Miss Bala-->
  <Spider /><!--Spider-Man Into The Spider-Verse -->
  <Crow /><!--The White Crow-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Favourite /><!--The Favourite -->
  <King /><!--The Kid Who Would Be King-->
  <Prodigy /><!--The Prodigy-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Total /><!--Total Dhamal  -->
  <Us /><!--Us-->
  <Preview />
  <Blank />
</b-card-group>


      <!--<Ml --90ML -->
      <!--<Star --A star is Born-->
      <!--True --All Is True 12A"-->
      <!--<Bell --Bell bottom-->
      <!--<Aquaman --Aquaman -->
      <!--Black --Blackklansman -->
      <!--Boy --Beautiful Boy -->
      <!--Burning --Burning-->
      <!--<Dragon --Dragon Ball Super -->
      <!--<Erased --Boy Erased-->
      <!--<Fight --The Fight-->
      <!--<Forgive --Can You Ever Forgive Me -->
      <!--<Had --What They Had -->
      <!--<Hannah --Hannah-->
      <!--<Hole --The Hole In The Ground-->
      <!--<Kindergarten --The Kindergarten Teacher -->
      <!--<Kobiety --Kobiety Mafii 2 -->
      <!--kodathi --Kodathi Samaksham Balan Vakkeel-->
      <!--Kumbalangi --Kumbalangi Nights-->
      <!--Maiden --Maiden-->
      <!--<Milan -Milan Talkies-->
      <!--<Ralph --Ralph Breaks The Internet: Wreck-It -->
      <!--<Ring --Ring-->
      <!--Second --Second Act-->
      <!--Serenityx--Serenity -->
      <!--<Sex --On The Basis Of Sex-->
      <!--<Stan --Stan & Ollie -->
      <!--<Kala /> Kala Shah Kala -->
      <!--Upside --The Upside -->
      <!--Grinch --Grinch-->
      <!--<Rose --Wild Rose -->
      <!--<Vice --Vice-->
      </b-container>
      </section>

</template>

<script>

import Dog from '@/components/Films/Dog'
import Aquaman from '@/components/Films/Aquaman'
import Boy from '@/components/Films/Boy'
import Glass from '@/components/Films/Glass'
import Scots from '@/components/Films/Scots'
import Second from '@/components/Films/Second'
import Stan from '@/components/Films/Stan'
import Favourite from '@/components/Films/Favourite'
import Mule from '@/components/Films/Mule'
import Vice from '@/components/Films/Vice'
import Blank from '@/components/Films/Blank'
import Bohemian from '@/components/Films/Bohemian'
import Bumblebee from '@/components/Films/Bumblebee'
import Ralph from '@/components/Films/Ralph'
import Escape from '@/components/Films/Escape'
import Upside from '@/components/Films/Upside'
import Spider from '@/components/Films/Spider'
import Destroyer from '@/components/Films/Destroyer'
import Preview from '@/components/Films/Preview'
import Creed from '@/components/Films/Creed'
import Dragon from '@/components/Films/Dragon'
import Colette from '@/components/Films/Colette'
import Green from '@/components/Films/Green'
import Forgive from '@/components/Films/Forgive'
import Star from '@/components/Films/Star'
import Alita from '@/components/Films/Alita'
import Lego from '@/components/Films/Lego'
import Happy from '@/components/Films/Happy'
import True from '@/components/Films/True'
import Family from '@/components/Films/Family'
import King from '@/components/Films/King'
import Fighting from '@/components/Films/Fighting'
import Grinch from '@/components/Films/Grinch'
import Cold from '@/components/Films/Cold'
import Caper from '@/components/Films/Caper'
import Sex from '@/components/Films/Sex'
import Black from '@/components/Films/Black'
import Dragonworld from '@/components/Films/Dragonworld'
import War from '@/components/Films/War'
import Aftermath from '@/components/Films/Aftermath'
import Had from '@/components/Films/Had'
import Serenityx from '@/components/Films/Serenityx'
import Gully from '@/components/Films/Gully'
import Kala from '@/components/Films/Kala'
import Ml from '@/components/Films/Ml'
import Luka from '@/components/Films/Luka'
import Badla from '@/components/Films/Badla'
import Kindergarten from '@/components/Films/Kindergarten'
import Marvel from '@/components/Films/Marvel'
import Border from '@/components/Films/Border'
import Bala from '@/components/Films/Bala'
import Guddiyan from '@/components/Films/Guddiyan'
import Kumbalangi from '@/components/Films/Kumbalangi'
import Hole from '@/components/Films/Hole'
import Total from '@/components/Films/Total'
import Bell from '@/components/Films/Bell'
import Everybody from '@/components/Films/Everybody'
import Kobiety from '@/components/Films/Kobiety'
import Beale from '@/components/Films/Beale'
import Kodathi from '@/components/Films/Kodathi'
import Maiden from '@/components/Films/Maiden'
import Poppins from '@/components/Films/Poppins'
import Ben from '@/components/Films/Ben'
import Fisherman from '@/components/Films/Fisherman'
import Fight from '@/components/Films/Fight'
import Prodigy from '@/components/Films/Prodigy'
import Band from '@/components/Films/Band'
import Erased from '@/components/Films/Erased'
import Milan from '@/components/Films/Milan'
import Burning from '@/components/Films/Burning'
import Ring from '@/components/Films/Ring'
import Hannah from '@/components/Films/Hannah'
import Rose from '@/components/Films/Rose'
import Crow from '@/components/Films/Crow'
import Five from '@/components/Films/Five'











export default {
  head () {
    return {
      titleTemplate: '%s Movies Today',
      meta         : [
        { hid: 'description', name: 'description', content: ' Whats on today @ cineworld, odeon, picturehouses, showcase & Vue cinemas in east London, Bexleyheath, Greenwich 02, Ilford,romford, South Woodford and West India Quay, February 2019 ' }
      ]
    }
  },
  components: {
    Aftermath,
    Alita,
    Aquaman,
    Badla,
    Bala,
    Band,
    Beale,
    Bell,
    Ben,
    Black,
    Blank,
    Bohemian,
    Border,
    Boy,
    Bumblebee,
    Burning,
    Caper,
    Cold,
    Colette,
    Creed,
    Crow,
    Destroyer,
    Dog,
    Dragon,
    Dragonworld,
    Erased,
    Escape,
    Everybody,
    Family,
    Favourite,
    Fight,
    Fighting,
    Fisherman,
    Five,
    Forgive,
    Glass,
    Green,
    Grinch,
    Guddiyan,
    Gully,
    Had,
    Hannah,
    Happy,
    Hole,
    Kala,
    Kindergarten,
    King,
    Kobiety,
    Kodathi,
    Kumbalangi,
    Lego,
    Luka,
    Maiden,
    Marvel,
    Milan,
    Ml,
    Mule,
    Poppins,
    Preview,
    Prodigy,
    Ralph,
    Ring,
    Rose,
    Scots,
    Second,
    Serenityx,
    Sex,
    Spider,
    Stan,
    Star,
    Total,
    True,
    Upside,
    Vice,
    War,

      }
}
</script>
