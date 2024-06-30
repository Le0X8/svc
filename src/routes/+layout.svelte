<script lang="ts">
	import '../styles/global.scss';
</script>

<nav class="bg-slate-800 fixed w-full h-12 text-white top-0 left-0 flex">
	<a href="/" class="flex flex-col p-2 items-center justify-center">
    <h1 class="text-2xl leading-4">svc</h1>
	  <h2 class="text-xs leading-6">by Leonard Lesinski</h2>
  </a>
</nav>

<main class="bg-slate-700 w-full mt-12 h-[calc(100vh-3rem)] text-white">
	<slot />
</main>

<footer class="bg-slate-600 w-full text-white">
	<p class="text-center p-2">&copy; 2024 <a href="https://leox.dev/">Leonard Lesinski</a></p>
</footer>
