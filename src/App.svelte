<script>
	export let name;
</script>

<main>
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<h3 class="ms-bgColor-sharedCyanBlue10">Hello from Fabric</h3>
</main>

<style lang="scss" global>
	@import 'office-ui-fabric-core/dist/sass/Fabric.scss';
	main{
		text-align: center;
		h1{
			background-color: red;
			
		}
		p{
			font-size: 50px;
		}

	}
</style>