<template>
  <div id="app">

    <!--=============== Navbar ===============-->
    <Navbar></Navbar>
    <!--=============== End Navbar ===============-->

    <!--=============== Hero Section ===============-->
    <HeaderContent></HeaderContent>
    <!--=============== End Hero Section ===============-->

    <!--=============== About Section ===============-->
    <About></About>
    <!--=============== End About Section ===============-->

    <!--=============== Statistics Section ===============-->
    <Statistics></Statistics>
    <!--=============== End Statistics Section ===============-->

    <!--=============== Services Section ===============-->
    <Services></Services>
    <!--=============== End Services Section ===============-->

    <!--=============== Skills Section ===============-->
    <Skills></Skills>
    <!--=============== End Skills Section ===============-->

    <!--=============== Resume section ===============-->
    <Resume></Resume>
    <!--=============== End Resume section ===============-->

    <!--=============== Portfolio Section ===============-->
    <Portfolio></Portfolio>
    <!--=============== End Portfolio Section ===============-->

    <!--=============== Contact Section ===============-->
    <Contact></Contact>
    <!--=============== End Contact Section ===============-->

    <!--=============== Clients Section ===============-->
    <Clients></Clients>
    <!--=============== End Clients Section ===============-->

    <!--=============== Footer ===============-->
    <Footer></Footer>
    <!--=============== End Footer ===============-->

    <!--=============== Scroll To Top Button ===============-->
    <div id="scrollTop" class="text-center ellipsis">
      <i class="fa fa-angle-up"></i>
    </div>
    <!--=============== End Scroll To Top Button ===============-->

    <!--=============== Preloader ===============-->
    <div class="preloader">
      <div class="preloader-inner d-flex align-items-center justify-content-center">

        <div class="circle-big">
          <div class="circle-small"></div>
        </div>

      </div>
    </div>
    <!--=============== End Preloader ===============-->

  </div>
</template>

<script>
import HeaderContent from './components/HeaderContent'
import Navbar from './components/Navbar'
import About from './components/About'
import Statistics from './components/Statistics'
import Services from './components/Services'
import Skills from './components/Skills'
import Resume from './components/Resume'
import Portfolio from './components/Portfolio'
import Contact from './components/Contact'
import Clients from './components/Clients'
import MainFooter from './components/MainFooter'

export default {
  name: 'app',
  components: {
    HeaderContent,
    Navbar,
    About,
    Statistics,
    Services,
    Skills,
    Resume,
    Portfolio,
    Contact,
    Clients,
    MainFooter
  }
}
</script>
