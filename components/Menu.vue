<template>
	<div class="d-flex flex-column justify-content-center">
		<div class="dropdown mb-3">
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
	color: rgb(255, 255, 255);
    border: 1px solid rgba(136, 255, 0, 1);
    font-size: 14px;
    font-family: oswald;
    font-weight: 400;
    text-transform: uppercase;
    text-align: center;
    letter-spacing: 2px;
    box-shadow: rgba(0, 0, 0, 0) 0px 0px 0px;
    transform: none;
}

.btn-verde:last-of-type
{
	margin-bottom: 0;
}

.dropdown-menu
{

}
</style>