<template>
	<div class="services">
		<div class="box">
			<h1 class="service">Lorem ipsum</h1>
			<ul>
				<li>lorem ipsum dolor</li>
				<li>lorem ipsum dolor</li>
				<li>lorem ipsum dolor</li>
				<li>lorem ipsum dolor</li>
			</ul><br>
			<a href="#"><button class="lm">Learn more</button></a>
		</div>
			<div class="box">
			<h1 class="service">Lorem ipsum</h1>
			<ul>
				<li>lorem ipsum dolor</li>
				<li>lorem ipsum dolor</li>
				<li>lorem ipsum dolor</li>
				<li>lorem ipsum dolor</li>
			</ul><br>
			<a href="#"><button class="lm">Learn more</button></a>
		</div>
	</div>
</template>

<script>
	
</script>

<style>
	.services{
		display: flex;
		justify-content: center;
		align-items: center;
		padding: 3vw;
		background: #242424;
		flex-wrap: wrap;
	}
	.box{
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		margin: 2rem;
		background: #EDEDED;
		border-radius: 3vw;
		padding: 2rem;
		width: 40%;
	}
	.service{
		color: #242424;
		margin: 1vw;
	}
	.services li{
		text-decoration: none;
		list-style: none;
		font-size: 2vw;
	}
	.lm{
		width: 8vw;
		height: 3vw;
		padding: 1vw;
		border: none;
		border-radius: 3vw;
		background: #242424;
		color: #EDEDED;
		font-size: 1vw;
	}
	.lm:hover{
		transition: 0.5s;
		background: #BBBBBB;
		color: #242424;
	}
</style>