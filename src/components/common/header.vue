<template>
	<div class="header">
		<ul>
			<li class="h-btn">
				<slot name="left"></slot>
			</li>
			<li class="h-title">
				<slot name="title"></slot>
			</li>
			<li class="h-btn"></li>
		</ul>
	</div>
</template>
<script lang="ts">
	import Vue from 'vue'
	export default Vue.extend({
		// @props ({

		// })
	})
</script>
