<template>
	<div class="main">
		{{msg}}asdasdasasdasdasd
		<ul>
			<li v-for="item in 20">{{item }}{{msg}}</li>
		</ul>
	</div>
</template>

<script>
	export default{
		data(){
			return {
				msg:'asdasdasdasdasd'
			}
		}
	}
</script>

<style scoped>
	.main{
		width: 100px;
		height: 500px;
		background: red;
	}
</style>