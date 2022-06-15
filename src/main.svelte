<script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from "./routes/index.svelte";
  import About from "./routes/about.svelte"
  import Products from "./routes/products.svelte";
  import logo from "./assets/PotabiTDLogo.png"
  export let url = "";
  import "./app.css"
</script>

<Router url="{url}">
  <nav class="bg-white px-2 sm:px-4 py-2.5">
    <div class="container flex flex-wrap justify-between items-center mx-auto">
      <div class="flex gap-3 items-center">
        <Link to="/">
          <span class="flex gap-2 items-center">
            <img src="{logo}" alt="Logo" class="w-10">
          </span>
        </Link>
        <Link to="/about">
          <h1 class="text-md">About</h1>
        </Link>
        <Link to="/products">
          <h1 class="text-md">Products</h1>
        </Link>
      </div>
    </div>
  </nav>
  <div>
    <Route path="/"><Home /></Route>
    <Route path="/about"><About /></Route>
    <Route path="/products/*"><Products /></Route>
  </div>
</Router>