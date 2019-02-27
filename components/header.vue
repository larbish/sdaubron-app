<template>
	<section class="header-container">
		<b-navbar toggleable="md"  variant="faded" type="light">

			<b-navbar-toggle target="nav_collapse"></b-navbar-toggle>

			<b-navbar-brand to="/">
				<div class="d-flex flex-row">
					<img src="~/assets/images/footprint.svg" width="60" height="60" alt="">
					<div class="d-none  d-md-flex flex-column">
						<span class="text-bold text-24-xs"> Sandrine Daubron </span>
						<span class="text-muted text-12-xs">Pédicure Podologue</span>
					</div>
				</div>
			</b-navbar-brand>

			<b-collapse is-nav id="nav_collapse">
				<!-- Right aligned nav items -->
				<b-navbar-nav class="ml-auto">
					<b-nav-item to="/">Accueil</b-nav-item>

					<b-nav-item-dropdown text="Pédicurie" right>
						<b-dropdown-item to="/pedicurie/soin">Soin</b-dropdown-item>
						<b-dropdown-item to="/pedicurie/pied-du-diabetique">Pied du diabétique</b-dropdown-item>
					</b-nav-item-dropdown>
					
					<b-nav-item-dropdown text="Podologie">
						<b-dropdown-item to="/podologie/semelles">Semelles</b-dropdown-item>
						<b-dropdown-item to="/podologie/podologie-du-sport">Podologie du sport</b-dropdown-item>
						<b-dropdown-item to="/podologie/orthoplastie">Orthoplastie</b-dropdown-item>
					</b-nav-item-dropdown>

					<b-nav-item class="text-black" to="/posturologie">Posturologie</b-nav-item>

					<b-nav-item to="/podopediatrie">Podopédiatrie</b-nav-item>

					<b-nav-item to="/reflexologie">Réfléxologie</b-nav-item>

					<b-nav-item to="/contact">Contact</b-nav-item>

				</b-navbar-nav>

			</b-collapse>
		</b-navbar>
	</section>
</template>

<script>
export default {}
</script>

<style>	
	li  > a {
		color: black !important;
	}

	.dropdown-item.active, .dropdown-item:active {
		background-color: black !important;
		color: white !important;
	}
</style>
