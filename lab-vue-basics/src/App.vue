<script>
import Navbar from './components/Navbar.vue'
import FooterComponent from './components/FooterComponent.vue'
import OperationComponent from './components/OperationComponent.vue'
import Iteration3if from './components/Iteration3if.vue'
import Iteration4for from './components/Iteration4for.vue'
import Iteration5background from './components/Iteration5background.vue'
export default {
  components: {
    Navbar,
    FooterComponent,
    OperationComponent,
    Iteration3if,
    Iteration4for,
    Iteration5background
  }
}
</script>

<template>
  <div>
    <Navbar />
    <OperationComponent />
    <Iteration3if />
    <Iteration4for />
    <Iteration5background />
    <FooterComponent />
  </div>
</template>

<style scoped></style>
