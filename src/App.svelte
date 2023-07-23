<script>
  import Moon from "./components/Moon.svelte";  
  import Article from "./components/Article.svelte";
</script>

<section class="container">
  <Moon/>
  <Article/>
</section>

<style>
  .container{
      display: grid;
      place-items: center;
      margin: 120px auto;
      width: 100%;
      height: max-content;
  }
</style>
