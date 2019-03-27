<template>
	<div class="container">
		<div class="side-bar">
			<router-link to="/user_TK">题库</router-link>
			<router-link to="/user_ZY">资源库</router-link>
			<router-link to="/user_HD">活动库</router-link>
		</div>
		<div class="content"><router-view /></div>
	</div>
</template>

<script>
export default {
	name: 'Lib',
	data() {
		return {
			
		};
	}
};
</script>

<style scoped>
	.container {
		width: 90%;
		margin: 0 auto;
		
	}
	.side-bar {
		flex: 1 1 20%;
		flex-direction: column;
		background-color: #fff;
		margin-top: 20px;
	}
	a{
		margin-bottom: 30px;
	}
	.content{
		width: 80%;
		margin: 0 auto;
		margin-top: 20px;
		height: 600px;
	}
</style>

