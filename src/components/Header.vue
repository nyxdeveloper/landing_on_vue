<template>
	<header>
		<div class="logo"><img src="../img/logo.png" class="graphicLogo"></div>
		<nav>
			<a href="#about">about</a>
			<a href="#projects">projects</a>
			<a href="#services">services</a>
			<a href="#contacts">contacts</a>
		</nav>
	</header>
</template>

<script>
	
</script>

<style>
*{
	padding: 0;
	margin: 0;
}
	header{
		display: flex;
		justify-content: space-between;
		padding: none;
		margin: none;
		height: 8vw;
		width: 100%;
		min-width: 100%;
		align-items: center;
		background: #242424;
	}
	nav{
		display: flex;
		justify-content: space-around;
	}
	header a{
		margin: 1rem;
		text-decoration: none;
		color: #EDEDED;
		font-size: 3vw;
		transition: 0.3s;
	}
	header a:hover{
		transition: 0.3s;
		color: #A0A0A0;
	}

	.logo{
		display: flex;
		height: 100%
	}
	.graphicLogo{
		height: 100%;
		width: auto;
		box-sizing: border-box;
	}

</style>