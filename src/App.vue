<script>
import HeaderComp from './components/HeaderComp.vue'
import HomeHero from './components/HomeHero.vue'
import Stats from './components/Stats.vue'
import CoursesContainer from './components/CoursesContainer.vue'
import IdeasComponent from './components/IdeasComponent.vue'
import ComplimentsComp from './components/ComplimentsComp.vue'
import ContactsComp from './components/ContactsComp.vue'
import FooterComp from './components/FooterComp.vue'
export default {
  name: `app`,

  components: {
    HeaderComp,
    HomeHero,
    Stats,
    CoursesContainer,
    IdeasComponent,
    ComplimentsComp,
    ContactsComp,
    FooterComp,
  },
}
</script>

<template>
  <HeaderComp />
  <HomeHero />
  <Stats />
  <CoursesContainer />
  <IdeasComponent />
  <ComplimentsComp />
  <ContactsComp />
  <FooterComp />
</template>
