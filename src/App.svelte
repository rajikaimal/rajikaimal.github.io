<script>
  import Talk from "./Talk.svelte";
  import Home from "./Home.svelte";
  import { Router, Link, Route } from "svelte-routing";

  export let url = "";
</script>

<style>
  .navBar {
    float: right;
    margin: 20px;
  }

  nav :global(a) {
    color: blue;
    margin-right: 10px;
    text-decoration: underline;
  }
</style>

<link href='https://fonts.googleapis.com/css?family=Roboto' rel='stylesheet'>

<Router {url}>
  <nav class="navBar">
    <Link to="/">Home</Link>
    <Link to="talks">Talks</Link>
  </nav>
  <div>
    <Route path="talks" component={Talk} />
    <Route path="/" component={Home} />
  </div>
</Router>
