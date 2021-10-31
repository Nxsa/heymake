<template>
	<div class="pg-index">
		<logo />
	</div>
</template>

<script>
import Logo from "@/vectors/Logo.vue";
export default {
	name: "Index",
	components: {
		Logo,
	},
	metaInfo: {
		title: "Heymake!",
		titleTemplate: "%s - Think. Make. Create",
	},
};
</script>

<style lang="scss" scoped>
</style>
