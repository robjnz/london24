<template>
<section main>
  <b-container>
    <h1 class="title-color">Movies showing today @ east London cinemas </h1>
    <br>
    <h2>Tuesday 2nd April 2019</h2>

    <b-card-group deck
    class="mb-3">
    <Airaa /><!--Airaa -->
    <AlitaC /><!--Alita Battle Angel -->
    <Badla /><!--Badia -->
    </b-card-group>

  <b-card-group deck
  class="mb-3 ">
    <Band /><!--Band Vaaje-->
  <Border /><!--Border -->
  <BoyC /><!--Beautiful Boy -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Caper /><!--Capernaum -->
  <MarvelC /><!-- Captain Marvel -->
  <Dumbo /><!--Dumbo -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Lion /><!--Eaten by Lion -->
  <EscapeC /><!--Escape Room -->
  <EverybodyC /><!--Everybody Knows -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
<FightingC /><!--Fighting With My Family -->
<Fisherman /><!--Fisherman’s Friend -->
<FiveC /><!--Five Feet Apart-->
</b-card-group>

  <b-card-group deck
  class="mb-3 ">
<GlassC /><!--Glass-->
<GreenC /><!--Green Book-->
<Guddiyan /><!--Guddiyan Patole -->
</b-card-group>

  <b-card-group deck
  class="mb-3 ">
<Gully /><!--Gully Boy -->
<HappyC /><!--Happy Death Day -->
<DragonworldC /><!--How to Train Your Dragon the Hidden -->
</b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <FamilyC /><!--Instant Family  -->
  <Junglee /><!--Junglee -->
  <Lucifer /><!--Lucifer-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Lords /><!--Lords of chaos-->
  <Luka /><!--Luka Chuppi  -->
  <Bala /><!--Miss Bala-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Notebook /><!--Notebook-->
  <Blue /><!--Out Of Blue -->
  <Rabb /><!--Rabb Da Radio-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Spider /><!--Spider-Man Into The Spider-Verse -->
  <Favourite /><!--The Favourite -->
  <King /><!--The Kid Who Would Be King-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Prodigy /><!--The Prodigy-->
  <VanishingC /><!--The Vanishing-->
  <Crow /><!--The White Crow-->

  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Total /><!--Total Dhamal  -->
  <Us /><!--Us-->
  <Vice /><!--Vice-->
  </b-card-group>



  <h1 class="title-color">Movies free to watch online </h1>
  <b-card-group deck
  class="mb-3 ">
  <Dog /><!--A Dog's Way Home-->
  <Alita /><!--Alita Battle Angel -->
  <Boy /><!--Beautiful Boy -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Ben /><!--Ben is Back 15-->
  <Bohemian /><!--Bohemian Rhapsody -->
  <Bumblebee /><!--Bumblebee -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Escape /><!--Escape Room -->
  <Fighting /><!--Fighting With My Family -->
  <Forgive /><!--Can You Ever Forgive Me -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Marvel /><!-- Captain Marvel -->
  <Cold /><!--cold Pursuit -->
  <Dragonworld /><!--How to Train Your Dragon the Hidden -->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Five /><!--Five Feet Apart-->
  <Everybody /><!--Everybody Knows -->
  <Glass /><!--Glass-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Green /><!--Green Book-->
  <Happy /><!--Happy Death Day -->
  <Beale /><!--If Beale Street Could talk-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Family /><!--Instant Family  -->
  <Scots /><!--Mary Queen Of Scots -->
  <Poppins /><!--Mary Poppins-->
  </b-card-group>

  <b-card-group deck
  class="mb-3 ">
  <Vanishing /><!--The Vanishing-->
  <Blank />
  <Blank />
  </b-card-group>

      <!--<Ml --90ML -->
      <!--<Star --A star is Born-->
      <!--True --All Is True 12A"-->
      <!--<Bell --Bell bottom-->
      <!--<Aquaman --Aquaman -->
      <!--Black --Blackklansman -->
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

import Aquaman from '@/components/Films/Aquaman'
import Second from '@/components/Films/Second'
import Stan from '@/components/Films/Stan'
import Favourite from '@/components/Films/Favourite'
import Mule from '@/components/Films/Mule'
import Vice from '@/components/Films/Vice'
import Blank from '@/components/Films/Blank'
import Ralph from '@/components/Films/Ralph'
import Upside from '@/components/Films/Upside'
import Spider from '@/components/Films/Spider'
import Destroyer from '@/components/Films/Destroyer'
import Preview from '@/components/Films/Preview'
import Creed from '@/components/Films/Creed'
import Dragon from '@/components/Films/Dragon'
import Colette from '@/components/Films/Colette'
import Star from '@/components/Films/Star'
import Lego from '@/components/Films/Lego'
import True from '@/components/Films/True'
import King from '@/components/Films/King'
import Grinch from '@/components/Films/Grinch'
import Caper from '@/components/Films/Caper'
import Sex from '@/components/Films/Sex'
import Black from '@/components/Films/Black'
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
import Border from '@/components/Films/Border'
import Bala from '@/components/Films/Bala'
import Guddiyan from '@/components/Films/Guddiyan'
import Kumbalangi from '@/components/Films/Kumbalangi'
import Hole from '@/components/Films/Hole'
import Total from '@/components/Films/Total'
import Bell from '@/components/Films/Bell'
import Kobiety from '@/components/Films/Kobiety'
import Kodathi from '@/components/Films/Kodathi'
import Maiden from '@/components/Films/Maiden'
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
import VanishingC from '@/components/Films/Vanishing/VanishingC'
import Poppins from '@/components/Films/Poppins/Poppins'
import Scots from '@/components/Films/Scots/Scots'
import Forgive from '@/components/Films/Forgive/Forgive'
import Boy from '@/components/Films/Boy/Boy'
import BoyC from '@/components/Films/Boy/BoyC'
import Dog from '@/components/Films/Dog/Dog'
import Ben from '@/components/Films/Ben/Ben'
import Bohemian from '@/components/Films/Bohemian/Bohemian'
import Cold from '@/components/Films/Cold/Cold'
import Beale from '@/components/Films/Beale/Beale'
import Bumblebee from '@/components/Films/Bumblebee/Bumblebee'
import Alita from '@/components/Films/Alita/Alita'
import AlitaC from '@/components/Films/Alita/AlitaC'
import Marvel from '@/components/Films/Marvel/Marvel'
import MarvelC from '@/components/Films/Marvel/MarvelC'
import Happy from '@/components/Films/Happy/Happy'
import HappyC from '@/components/Films/Happy/HappyC'
import Green from '@/components/Films/Green/Green'
import GreenC from '@/components/Films/Green/GreenC'
import Glass from '@/components/Films/Glass/Glass'
import GlassC from '@/components/Films/Glass/GlassC'
import Five from '@/components/Films/Five/Five'
import FiveC from '@/components/Films/Five/FiveC'
import Fighting from '@/components/Films/Fighting/Fighting'
import FightingC from '@/components/Films/Fighting/FightingC'
import Family from '@/components/Films/Family/Family'
import FamilyC from '@/components/Films/Family/FamilyC'
import Everybody from '@/components/Films/Everybody/Everybody'
import EverybodyC from '@/components/Films/Everybody/EverybodyC'
import Escape from '@/components/Films/Escape/Escape'
import EscapeC from '@/components/Films/Escape/EscapeC'
import Dragonworld from '@/components/Films/Dragonworld/Dragonworld'
import DragonworldC from '@/components/Films/Dragonworld/DragonworldC'














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
    AlitaC,
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
    BoyC,
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
    DragonworldC,
    Erased,
    Escape,
    EscapeC,
    Everybody,
    EverybodyC,
    Family,
    FamilyC,
    Favourite,
    Fight,
    Fighting,
    FightingC,
    Fisherman,
    Five,
    FiveC,
    Forgive,
    Glass,
    GlassC,
    Green,
    GreenC,
    Grinch,
    Guddiyan,
    Gully,
    Had,
    Hannah,
    Happy,
    HappyC,
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
    MarvelC,
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
    VanishingC,
    Vice,
    War,
    Dumbo,
    Junglee,
    Lion,
    Us,
      }
}
</script>
