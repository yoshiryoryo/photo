<template>
  <div>
    <header>
      <Navbar />
    </header>
    <main>
      <div class="container">
        <RouterView />
      </div>
    </main>
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/Navber'
import Footer from './'

export default {
  components: {
    Navbar,
    Footer
  }
}
</script>