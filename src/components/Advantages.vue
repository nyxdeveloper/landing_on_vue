<template>
	<div class="advantages">
		<div>
			<img src="../img/guard.png">
			<h2>Lorem ipsum</h2>
		</div>
		<div>
			<img src="../img/quality.png">
			<h2>Lorem ipsum</h2>
		</div>
		<div>
			<img src="../img/stonks.png">
			<h2>Lorem ipsum</h2>
		</div>
	</div>
</template>

<script>
	
</script>

<style>
	.advantages{
		display: flex;
		padding: 10%;
	}
	.advantages div{
		display: flex;
		flex-direction: column;
		height: 15vw;
		width: 25%;
		margin: 5%;
		justify-content: center;
	}
	.advantages img{
		height: 100%;
		width: auto no-repeat;
	}
	.advantages h2{
		font-size: 2vw;
		text-align: center;
		padding: 1vw;
	}
</style>