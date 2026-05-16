<script>
    import { faMarsStroke, faClock, faCompass, faBuilding, faEnvelope } from "@fortawesome/free-solid-svg-icons";

	
	import { FontAwesomeIcon } from "@fortawesome/svelte-fontawesome";

</script>

<section id="contact-me">
	<div id="current-position">
		<p>Current position: Seasonal Merchandiser</p>
	</div>

	<div id="grid-container">
		<div id="first-half">
			<span><FontAwesomeIcon icon={ faBuilding } style="height: 25px; width:25px; display: inline; margin-right: 12px;" />Founder @CreoNexa</span>
			<span><FontAwesomeIcon icon={ faCompass } style="height: 25px; width:25px; display: inline; margin-right: 12px;" />Location: Rochester, New York</span>
		</div>
		<div id="second-half">
			<span><FontAwesomeIcon icon={ faMarsStroke } style="height: 25px; width:25px; display: inline; margin-right: 12px;" />he/him</span>
			<span><FontAwesomeIcon icon={ faClock } style="height: 25px; width:25px; display: inline; margin-right: 12px;" />Timezone: EST</span>
		</div>
	</div>
	<div id="email"><FontAwesomeIcon icon={ faEnvelope } style="height: 25px; width:25px; display: inline; margin-right: 12px;" />Email: tylerwmack4321@gmail.com</div>
</section>


<style>

	span {
		display: flex;
		margin-top: 12px;
		text-align: center;
		justify-content: center;
	}

	#contact-me {
		margin: 36px auto;
		padding: 12px;
		border: 1px solid var(--border-color);
		color: ghostwhite;
	}

	#current-position {
		text-align: center;
	}

	#grid-container {
		display: grid;
		border: 1px solid var(--border-color);
		margin: 12px;
		padding: 12px;
		grid-template-columns: repeat(2, 1fr);
	}

	#email {
		display: flex;
		text-align: center;
		justify-content: center;
	}

	@media screen and (min-width: 320px) and (max-width: 960px) {

		#grid-container {
			grid-template-columns: repeat(1, 1fr);
			text-align: center;
		}
	}
</style>
