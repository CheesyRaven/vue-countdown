<template>
	<div>
		<h3>Hello World</h3>
		<Counter
			:year="2020"
			:month="9"
			:date="31"
			:hour="10"
			:minute="10"
			:second="10"
			:millisecond="10"
		/>
	</div>
</template>

<script>
import Counter from '@/components/Counter.vue'
export default {
	components: {
		Counter
	}

};

</script>

<style lang="scss" scoped>
</style>
