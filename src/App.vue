<template>
  <div>
    <!--<img alt="Vue logo" src="./assets/logo.png">-->
    <nav-bar></nav-bar>
    <mast-head></mast-head>
    <about-me></about-me>
    <our-services></our-services>
    <my-projects></my-projects>
    <contact-me></contact-me>
    <app-footer></app-footer>
  </div>
</template>

<script>
  import nav from "./components/nav";
  import masthead from "./components/masthead";
  import about from "./components/about";
  import ourServices from "./components/ourServices";
  import projects from "./components/projects";
  import contactMe from "./components/contactMe";
  import footer from "./components/footer";

export default {
  name: 'App',
  components: {
    'nav-bar' : nav,
    'mast-head' : masthead,
    'about-me' : about,
    'our-services' : ourServices,
    'my-projects' : projects,
    'contact-me' : contactMe,
    'app-footer' : footer
  }
}
</script>

<style>

</style>
