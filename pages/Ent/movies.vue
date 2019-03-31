<template>
<section main>
  <b-container>
    <h1 class="title-color">Movies showing today @ east London cinemas </h1>
    <br>
    <h2>Monday 1st April 2019</h2>

    <b-card-group deck
    class="mb-3">
    <Airaa /><!--Airaa -->
    <Alita /><!--Alita Battle Angel -->
    <Badla /><!--Badia -->
    </b-card-group>

  <b-card-group deck
  class="mb-3 ">
    <Band /><!--Band Vaaje-->
  <Border /><!--Border -->
  <Caper /><!--Capernaum -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Marvel /><!-- Captain Marvil -->
  <Dumbo /><!--Dumbo -->
  <Lion /><!--Eaten by Lion -->
   </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Escape /><!--Escape Room -->
  <Everybody /><!--Everybody Knows -->
<Fighting /><!--Fighting With My Family -->
 </b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Fisherman /><!--Fisherman’s Friend -->
<Five /><!--Five Feet Apart-->
<Glass /><!--Glass-->
 </b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Green /><!--Green Book-->
<Guddiyan /><!--Guddiyan Patole -->
<Gully /><!--Gully Boy -->
 </b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Happy /><!--Happy Death Day -->
<Dragonworld /><!--How to Train Your Dragon the Hidden -->
<family /><!--Instant Family  -->
 </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Junglee /><!--Junglee -->
  <Lucifer /><!--Lucifer-->
  <Lords /><!--Lords of chaos-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Luka /><!--Luka Chuppi  -->
  <Bala /><!--Miss Bala-->
  <Notebook /><!--Notebook-->
   </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Blue /><!--Out Of Blue -->
  <Rabb /><!--Rabb Da Radio-->
  <Spider /><!--Spider-Man Into The Spider-Verse -->
   </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Crow /><!--The White Crow-->
  <Favourite /><!--The Favourite -->
  <King /><!--The Kid Who Would Be King-->
    </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Prodigy /><!--The Prodigy-->
  <Vanishing /><!--The Vanishing-->
  <Total /><!--Total Dhamal  -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Us /><!--Us-->
  <Vice /><!--Vice-->
  <Blank />
  </b-card-group>

  <h1 class="title-color">Movies free to watch online </h1>
  <b-card-group deck
  class="mb-3 ">
  <Dog /><!--A Dog's Way Home-->
  <Ben /><!--Ben is Back 15-->
  <Bohemian /><!--Bohemian Rhapsody -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Bumblebee /><!--Bumblebee -->
  <Forgive /><!--Can You Ever Forgive Me -->
  <Cold /><!--Cold Pursuit -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Beale /><!--If Beale Street Could talk-->
  <Scots /><!--Mary Queen Of Scots -->
  <Poppins /><!--Mary Poppins-->
  
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
      </b-container>
      </section>

</template>

<script>

import Dog from '@/components/Films/Dog'
import Aquaman from '@/components/Films/Aquaman'
import Boy from '@/components/Films/Boy'
import Glass from '@/components/Films/Glass'
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
import Dumbo from '@/components/Films/Dumbo'
import Junglee from '@/components/Films/Junglee'
import Lion from '@/components/Films/Lion'
import Us from '@/components/Films/Us'
import Blue from '@/components/Films/Blue'
import Notebook from '@/components/Films/Notebook'
import Lords from '@/components/Films/Lords'
import Lucifer from '@/components/Films/Lucifer'
import Rabb from '@/components/Films/Rabb'
import Airaa from '@/components/Films/Airaa/Airaa'
import Vanishing from '@/components/Films/Vanishing/Vanishing'
import Poppins from '@/components/Films/Poppins/Poppins'
import Scots from '@/components/Films/Scots/Scots'
import Forgive from '@/components/Films/Forgive/Forgive'












export default {
  head () {
    return {
      titleTemplate: '%s Movies Today',
      meta         : [
        { hid: 'description', name: 'description', content: ' Whats on today @ cineworld, odeon, picturehouses, showcase & Vue cinemas in east London, Bexleyheath, Greenwich 02, Ilford,romford, South Woodford and West India Quay, April 2019 and free to watch online movies' }
      ]
    }
  },
  components: {
    Aftermath,
    Airaa,
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
    Blue,
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
    Lucifer,
    Lords,
    Luka,
    Maiden,
    Marvel,
    Milan,
    Ml,
    Mule,
    Notebook,
    Poppins,
    Preview,
    Prodigy,
    Rabb,
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
    Vanishing,
    Vice,
    War,
    Dumbo,
    Junglee,
    Lion,
    Us,
      }
}
</script>
