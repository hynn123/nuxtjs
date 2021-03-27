<template>
	<div class="d-flex flex-column justify-content-center">
		<div class="dropdown mb-3">
			<button class="btn btn-secondary dropdown-toggle btn-verde w-100" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
				Trabalhos
			</button>
			<div class="dropdown-menu text-center text-uppercase w-100" aria-labelledby="dropdownMenuButton">
				<a class="dropdown-item" href="#">Layouts</a>
				<a class="dropdown-item" href="#">Banners</a>
				<a class="dropdown-item" href="#">Logos</a>
			</div>
		</div>

		<NuxtLink to="/sobremim" href="" class="btn btn-secondary btn-verde" type="button">
			Sobre mim
		</NuxtLink>
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

.btn-secondary:not(:disabled):not(.disabled).active, .btn-secondary:not(:disabled):not(.disabled):active, .show>.btn-secondary.dropdown-toggle
{
	background-color: transparent;
	border-color: #88FF00;
	box-shadow: unset !important;
}

.dropdown-menu.text-center
{
	width: fit-content;
	position: relative;
	background-color: #111;
	border: 0px solid #88FF00;
	border-top: 0;
	padding: 0;

	font-family: 'Oswald';
	font-size: 12pt;
	letter-spacing: 2px;
	text-transform: uppercase;
}

.dropdown-menu.text-center a
{
	color: #fff;
	border-bottom: 1px dashed #333;
	padding: 1em;
}

.dropdown-menu.text-center a:hover
{
	color: #000;
	background-color: #88FF00;
	border-bottom: 1px dashed #333;
}

.dropdown-menu.text-center a:last-of-type
{
	border-bottom: 0;
}

.dropdown-menu.text-center.w-100 a:active
{
	color: #88ff00;
	background-color: rgba(172, 255, 47, 0.151);
}

.dropdown-item
{
	font-weight: 100;
}
</style>