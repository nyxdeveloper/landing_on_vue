<template>
	<div class="top">
		<form>
			<h1 class="top-h">Lorem ipsum dolor sit amet.</h1>
			<input type="text" placeholder="Name">
			<input type="phone" placeholder="Phone">
		</form>
		<div class="img-box">
		</div>
	</div>
</template>

<script>
	
</script>

<style>
*{
	margin: 0;
	padding: 0;
}
	.top{
		display: flex;
		height: 39vw;
		padding: 0;
		margin: 0;
	}
	.top form{
		display: flex;
		flex-direction: column;
		flex: 1;
		padding: 1vw;
	}
	.top input{
		padding: 1vw;
		margin: 1vw;
		width: 60%;
		border: none;
		border-radius: 3vw;
		height: 3vw;
		color: #757575;
		background: #242424;
		font-size: 2vw;
	}
	.top-h{
		color: #EDEDED;
		padding-top: 6vw;
		padding-left: 3vw;
		font-size: 4vw;
	}
	.img-box::before{
		content: '';
		position: absolute;
		left: 0; right: 0;
		top: 0; bottom: 0;
		z-index: -1; 
		background: url(img/busines.jpg)center;
		background-size: 100% 140%;
		filter: blur(3px);
	}
	.img-box{
		display: flex;
		flex: 1;
	}
	.img-box img{
		width: 100%;
		height: auto;
		box-sizing: border-box;
	}
</style>