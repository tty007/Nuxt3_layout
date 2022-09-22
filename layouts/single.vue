<template>
	<div>
		<span>single layout</span>
		<AppNavigation />
		<hr>
		<NuxtPage/>
		<nuxt-link to="/">トップへ戻る</nuxt-link>
		<hr>
		<footer>
			footer
		</footer>
	</div>
</template>

<script>
import AppNavigation from '~/components/AppNavigation.vue'

export default {
	components: {
		AppNavigation
	}
}
</script>