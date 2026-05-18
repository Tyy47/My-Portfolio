<script></script>

<section id="socials-section">
	<div class="grid-container">
		<div class="grid-slot">
			<div class="img-container">
				<a href="https://www.github.com/Tyy47" target="_blank"><img src="https://assets.chanhdai.com/images/link-icons/github.webp?t=1759581475" alt="Github Logo" class="social-img" /> </a>
			</div>
			<div class="text-container">
				<h4><a href="https://www.github.com/Tyy47" target="_blank">Github</a></h4>
				<p class="social-username">@Tyy47</p>
			</div>
		</div>
		<div class="grid-slot">
			<div class="img-container">
				<a href="https://www.linkedin.com/in/tyler-mack-382374310" target="_blank"><img src="https://assets.chanhdai.com/images/link-icons/linkedin.webp?t=1759581475" alt="LinkedIn Logo" class="social-img"> </a>
			</div>
			<div class="text-container">
				<h4><a href="www.linkedin.com/in/tyler-mack-382374310" target="_blank">LinkedIn</a></h4>
				<p class="social-username">Tyler Mack</p>
			</div>

		</div>
	</div>
</section>

<style>

	a {
		color: ghostwhite;

	}

	#socials-section {
		border: 1px solid var(--border-color);
		margin: 36px auto;
		padding: 20px;
	}

	.grid-container {
		display: grid;
		border: 1px solid var(--border-color);
		grid-template-columns: repeat(2, 1fr);
		margin: 0 auto;
		padding: 20px;
		color: ghostwhite;
	}

	.grid-slot {
		display: flex;
		flex-direction: row;
		flex-wrap: nowrap;
		justify-content: center;
	}
	
	.img-container {
		display: inline;
	}

	.text-container {
		display: inline;
		margin-left: 16px;
	}

	.social-username {
		color: gray;
	}

	.social-img {
		display: inline;
		width: 50px;
		height: 50px;
		border-radius: 7%;
	}

</style>
