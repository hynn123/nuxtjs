<template>
	<div class="d-flex flex-column justify-content-center">
		<div class="dropdown mb-3">
			<button class="btn btn-secondary btn-verde btn-block dropdown-toggle" type="button" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
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
	border: 1px solid #88FF00;
	background-color: transparent;

	font-family: 'Oswald';
	font-size: 14pt;
	font-weight: 100;
	letter-spacing: 2px;
	text-transform: uppercase;

	padding: 1em 2em;
	margin-bottom: 1rem;

	transition: ease all .3s;
}

.btn-verde:last-of-type
{
	margin-bottom: 0;
}

.btn-verde:hover
{
	background-color: #88FF00;
	border-color: transparent;
	transition: ease all .3s;
}
</style>