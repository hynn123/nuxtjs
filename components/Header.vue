<template>
	<div class="row">
		<div class="col">
			<Logo />
		</div>

		<div class="col">
			<Menu />
		</div>
	</div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Menu from '~/components/Menu.vue'

export default {
  components: {
    Logo,
    Menu,
  }
}
</script>