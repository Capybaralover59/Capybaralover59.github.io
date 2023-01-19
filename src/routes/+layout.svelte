<script>
  import "prism-themes/themes/prism-one-dark.css";
</script>

<svelte:head>
  <link rel="stylesheet" href="/pico.min.css" />

  <style>
    nav {
      margin-left: 10%;
      margin-right: 10%;
    }
    .container{
      margin:-25px;
    }
  </style>
</svelte:head>

<nav>
  <ul>
    <li><a href="/">Hem</a></li>
    <li><a href="/devblog">Blog</a></li>
  </ul>
</nav>

<main class="container-fluid">
  <hr />

  <main class="container">
    <slot />
  </main>
</main>
