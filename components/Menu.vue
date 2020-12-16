<template>
	<div class="d-flex flex-column justify-content-center">
		<div class="dropdown mb-3">
			<a class="btn btn-secondary btn-verde btn-block dropdown-toggle" type="a" id="dropdownMenu2" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
				Portfólio
			</a>
			<div class="dropdown-menu text-center w-100" aria-labelledby="dropdownMenu2">
				<a class="dropdown-item" type="a">Layouts</a>
				<a class="dropdown-item" type="a">Banners</a>
				<a class="dropdown-item" type="a">Logos</a>
			</div>
		</div>

		<NuxtLink to="/sobremim" class="btn btn-secondary btn-verde">Sobre mim</NuxtLink>
		<a href="#" class="btn btn-secondary btn-verde">Contato</a>
	</div>
</template>

<style>
.btn-verde
{
	color: #fff;

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
	color: #000;
	background-color: #88FF00;
	border-color: transparent;
	transition: ease all .3s;
}

.btn-verde:focus
{
	box-shadow: unset;
}

.dropdown-menu.text-center.w-100
{
	background-color: #111;
	border: 1px solid #88FF00;
	border-top: 0;
	border-bottom-left-radius: 10px;
	border-bottom-right-radius: 10px;
}

.dropdown-menu.text-center.w-100 a
{
	color: #88ff00;
}

.dropdown-menu.text-center.w-100 a:active
{
	color: #88ff00;
	background-color: rgba(172, 255, 47, 0.151);
}
</style>