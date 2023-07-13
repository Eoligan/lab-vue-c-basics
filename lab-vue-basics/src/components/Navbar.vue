<template lang="">
  <header>
    <nav class="primary-nav" data-visible="false">
      <ul>
        <li><a href="/index.html">Home</a></li>
        <li><a id="main-project" href="">Projects</a></li>
        <li><a href="#">Services</a></li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {}
</script>

<style lang="">
.primary-nav {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  font-size: 1rem;
  font-weight: bold;
}

.primary-nav ul {
  display: flex;
  list-style: none;
  padding: 0;
  gap: 4rem;
}
.primary-nav li {
  position: relative;
  cursor: pointer;
}
.primary-nav a {
  text-decoration: none;
  color: black;
}

.primary-nav a:hover {
  color: red;
}

.primary-nav li:hover {
  text-shadow: 1px 0px 0px gray;
}
</style>
