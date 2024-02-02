<script>
   import '../app.css';
   import Navbar from '../components/Navbar.svelte';
</script>

<Navbar />
<h1 class="text-red-500 text-3xl">Header</h1>
<slot />
<h4>Footer</h4>  