<script context="module">

import Navigation from "./_navigation.svelte";

</script>

<svelte:head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.7.0/font/bootstrap-icons.css">
</svelte:head>

<Navigation/>

<div class="text-center">
    <slot/>
</div>

<footer class="text-center position-absolute bottom-0 start-50 translate-middle">
    <div>Nyaleph</div>
    <div>Copyright © 2022</div>
    <div>Contact me: <a href="mailto:contact@nyaleph.com">contact@nyaleph.com</a></div>
</footer>