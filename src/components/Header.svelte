<script>

	import { FontAwesomeIcon } from '@fortawesome/svelte-fontawesome';
	import { faGithub, faLinkedin } from '@fortawesome/free-brands-svg-icons';
    import { faAddressCard } from '@fortawesome/free-solid-svg-icons';

</script>

<header>
	<nav>
		<a href="../../Resume.pdf" class="social-icon" target="_blank"><FontAwesomeIcon icon={ faAddressCard } /></a>
		<a href="https://www.github.com/Tyy47" class="social-icon" target="_blank"><FontAwesomeIcon icon={ faGithub } /></a>
		<a href="https://www.linkedin.com/in/tyler-mack-382374310" target="_blank" class="social-icon"><FontAwesomeIcon icon={ faLinkedin } /></a>
	</nav>
</header>
<hr>

<style>
	
	header {
		margin: 12px auto;
		float: right;
	}

	nav {
		display: flex;
		flex-direction: row;
		justify-content: space-around;
		gap: 30px;
	}

	.social-icon {
		width: 25px;
		height: 25px;
		margin: 0 auto;
	}

	a {
		color: ghostwhite;
		text-align: center;
		text-decoration: none;
	}

	a:hover {
		scale: 1.1;
	}

	hr {
		width: 90%;
		opacity: 50%;
		margin: 24px auto;
	}

	@media screen and (min-width: 320px) and (max-width: 960px) {
		
		header {
			display: block;
			float: none;
		}
		
		nav {
			flex-direction: row;
			margin: 12px auto;
		}
		
	}

</style>
