<template>
	<div class="projects">
		<div class="text">
			<h1>Lorem ipsum</h1>
			<p><span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. In nesciunt possimus maxime iure est at minus distinctio temporibus omnis, necessitatibus voluptas illo debitis, itaque sed quod, natus aperiam veniam consequuntur!</span>
			</p><br>
			<button class="lm">Learn more</button>
		</div>
		<div>
			<img src="../img/projects.jpg" alt="">
		</div>
	</div>
</template>

<script>
	
</script>

<style>
	.projects{
		display: flex;
		width: 100%;
		background: #EDEDED;
	}
	.projects div{
		display: flex;
		flex-direction: column;
		flex: 1;
	}
	.projects img{
		width: 100%;
		height: auto;
	}
	.text{
		padding: 2vw;
		font-size: 2vw;
	}
	.text h1{
		margin: 1vw;
	}
	.projects .lm{

	}
</style>
