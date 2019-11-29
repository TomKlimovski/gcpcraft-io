<script>
	export let name;
</script>

<main>
	<!-- <h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p> -->

	<div data-collapse="medium" data-animation="default" data-duration="400" class="navbar w-nav">
		<div>
		<div class="nav-container w-container">
			<a href="/" class="w-nav-brand w--current"><img src="assets/web/cloudcraft-logo-with-text.svg" alt="GCPcraft logo" class="logo"></a>
			<nav role="navigation" class="nav-menu w-clearfix w-nav-menu">
			<div class="login-buttons-box">
				<a href="/app" class="button login-button w-button">LOGIN</a>
				<a href="/signup" class="button signup-button w-button">SIGN UP</a></div>
				<a href="/" class="navlink w-nav-link w--current" style="max-width: 728px;">Home</a>
				<a href="/#Create-your-cloud" class="navlink w-nav-link" style="max-width: 728px;">Learn More</a>
				<a href="/pricing" class="navlink w-nav-link" style="max-width: 728px;">Pricing</a>
				<a href="/app" class="navlink login-menu-item w-nav-link" style="max-width: 728px;">LOGIN</a>
				<a href="/signup" class="navlink sign-up-menu-item w-nav-link" style="max-width: 728px;">SIGN UP</a></nav>
			<div class="w-nav-button">
			<div class="w-icon-nav-menu"></div>
			</div>
		</div>
		</div>
	<div class="w-nav-overlay" data-wf-ignore=""></div>
	</div>
</main>
<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
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