<script lang="ts">
	import PersonalInfo from "./components/personal/PersonalInfo.svelte";
	import WorkplaceList from "./components/workplaces/WorkplaceList.svelte";
</script>

<main>
	<PersonalInfo />
	<WorkplaceList />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	section {
		background-color: antiquewhite;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
