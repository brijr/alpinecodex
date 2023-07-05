<script>
	import './styles.css';
	import Alpine from '$lib/images/Alpine.svg';
	import Codex from '$lib/images/Codex.svg';
</script>

<main
	class="bg-[#0500FF] text-white min-w-screen min-h-screen w-full h-full flex justify-center items-center flex-col"
>
	<img src={Alpine} class="fixed top-0 left-0 md:w-64" alt="Alpine" />
	<slot />
	<img src={Codex} class="fixed bottom-0 right-0 md:w-64" alt="Codex" />
</main>
