<template>
<v-app>
<Header />
<Content />
<Footer />
  </v-app>
</template>

<script>
import Header from './components/Header'
import Content from './components/Content'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    Footer,
    Header,
    Content
  },
  data () {
    return {
      //
    }
  }
}
</script>
