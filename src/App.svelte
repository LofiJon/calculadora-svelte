<script lang="ts">
window.scrollTo(0, 0);
import Calculadora from "./components/Calculadora.svelte";
</script>

<main>
	<Calculadora/>
</main>

<style>
	:global(body::-webkit-scrollbar) {
		width: 2px;
	}

	:global(body::-webkit-scrollbar-track) {
		background: gray;        /* color of the tracking area */
	}

	:global(body::-webkit-scrollbar-thumb) {
		background-color: #023047;    /* color of the scroll thumb */
		border-radius: 5px;       /* roundness of the scroll thumb */
	}

	:global(body) {
		/*background-color: #333333;*/
		background-image: url("https://c.tenor.com/Uz2tRqvAJP8AAAAM/pixel-art.gif");
	}
	:root {
		--cor-fundo: #555;
	}
	main {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
</style>
