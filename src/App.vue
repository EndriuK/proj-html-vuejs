
<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data() {
    return {
      headerLinks: [
        { text: 'Home', href: '#' },
        { text: 'Services', href: '#' },
        { text: 'About', href: '#' },
        { text: 'Projects', href: '#' },
        { text: 'Results', href: '#' },
        { text: 'Contact', href: '#', isButton: true }
      ],
      footerLinks: [
        { text: 'Privacy Policy', href: '#' },
        { text: 'Terms of Service', href: '#' },
        { text: 'Contact Us', href: '#' }
      ]
    }
  }
}
</script>

<template>
  <div>
    <AppHeader :links="headerLinks" />
    <AppMain />
    <AppFooter :links="footerLinks" />
  </div>
</template>

<style lang="scss">
  @import './style/generals.scss';
</style>
