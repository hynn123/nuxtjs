<template>
	<div class="row d-flex flex-column">
		<div class="col-sm">
			<Logo />
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