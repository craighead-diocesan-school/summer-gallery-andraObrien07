<script>
  import Header from "$lib/Header.svelte";
  import Footer from "$lib/Footer.svelte";
  import Nav from "$lib/Nav.svelte";
  import Card from "$lib/Card.svelte";
</script>

<Header title="Welcome" subtitle="Emma is great" />

<Nav />
<main class="content section">
  <h2>SvelteKit</h2>
  <img src="/Orange:noskinss.jpg" alt="Orange with no skin" />
  <p>
    Welcome to coding with SvelteKit, a modern JavaScript framework that makes
    it easy to code great apps.
  </p>
</main>

<Card />
<Footer
  author="&copy; Craighead Diocesan School 2024"
  organisation="andra.org.nz"
  date="14/02/2024"
/>
