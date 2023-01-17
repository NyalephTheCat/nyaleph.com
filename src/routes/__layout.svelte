<script context="module">

import Navigation from "./_navigation.svelte";

</script>

<svelte:head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.0/font/bootstrap-icons.css">
</svelte:head>

<div class="main">

<Navigation/>

<div class="text-center">
    <slot/>
</div>

<footer class="text-center position-absolute bottom-0 start-50 translate-middle">
  <address>
    <div>Nyaleph</div>
    <div>Copyright © 2022</div>
    <div>Contact me: <a href="mailto:contact@nyaleph.com">contact@nyaleph.com</a></div>
  </address>
</footer>

</div>

<style>
  /* Colors from: https://coolors.co/3a3335-d81e5b-f0544f-fdf0d5-c6d8d3 */

  :global(body) {
    --bs-body-bg: #C6D8D3
  }

  :global(.navbar-nav .nav-link) :global(a) {
    color: #F0544F;
  }
</style>