<script>
import Navbar from './components/Navbar.vue'
import FooterComponent from './components/FooterComponent.vue'
import OperationComponent from './components/OperationComponent.vue'
export default {
  components: {
    Navbar,
    FooterComponent,
    OperationComponent
  }
}
</script>

<template>
  <div>
    <Navbar />
    <OperationComponent />
    <FooterComponent />
  </div>
</template>

<style scoped></style>
