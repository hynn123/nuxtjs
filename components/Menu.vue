<template>
	<div class="d-flex flex-column justify-content-center">
		<div class="dropdown">
			<button class="btn btn-secondary btn-verde dropdown-toggle" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
				Portfólio
			</button>
			<div class="dropdown-menu text-center" aria-labelledby="dropdownMenu2">
				<button class="dropdown-item" type="button">Layouts</button>
				<button class="dropdown-item" type="button">Banners</button>
				<button class="dropdown-item" type="button">Logos</button>
			</div>
		</div>

		<a href="#" class="btn btn-secondary btn-verde">Sobre mim</a>
		<a href="#" class="btn btn-secondary btn-verde">Contato</a>
	</div>
</template>

<style>
.btn-verde
{
	border: 2px solid #88FF00;
	background-color: transparent;

	font-size: 14pt;
	font-weight: 400;
	letter-spacing: 2px;
	text-transform: uppercase;
	margin-bottom: 1em;
}

.btn-verde:last-of-type
{
	margin-bottom: 0;
}

.dropdown-menu
{

}
</style>