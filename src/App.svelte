<script>
  import CartLength from "./CartLength.svelte";
  import Products from "./Products.svelte";
  import Cart from "./Cart.svelte";
  import Address from "./Address.svelte";
</script>

<CartLength />
<Products />
<Cart />
<Address />
<button class="btn testit">Button</button>
<button class="btn btn-primary">PButton</button>
<button class="btn btn-secondary">SButton</button>
<button class="btn btn-accent">AButton</button>
<button class="btn btn-ghost">GButton</button>
<button class="btn btn-link">LButton</button>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;
  .testit {
    background: green;
  }
</style>
