<script>
	import { Route, Router } from 'svelte-routing';
	import PartnerNav from './common/PartnerNav.svelte';
	import SideBar from './common/SideBar.svelte';

	export let url = "";
</script>

<Router {url}>
	<main>
		<Route path="/">
			<PartnerNav />
			<SideBar />			
		</Route>
	</main>
</Router>

<style>
	main {
		display: flex;
		flex-wrap: nowrap;
		height: 100vh;
		height: -webkit-fill-available;
		max-height: 100vh;
		overflow-x: auto;
		overflow-y: hidden;	
	}
</style>