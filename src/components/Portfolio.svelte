<script>
</script>

<main>
	<section id="me">
		<div id="intro">
			<h3>Tyler Mack</h3>
			<p>IT Professional and Web Developer</p>
		</div>
		<hr />
		<div id="location">
			<p>Email: tylerwmack4321@gmail.com</p>
			<p>Phone Number: 585-250-2211</p>
			<p>Location: Rochester, NY</p>
		</div>
		<hr />
		<div id="socials">
			<a href="https://www.linkedin.com/in/tyler-mack-382374310/" target="_blank">LinkedIn Profile</a>
			<a href="https://github.com/Tyy47" target="_blank">GitHub Profile</a>
		</div>
		<hr>
	</section>

	<div class="flex-container">
		<section id="skills">
			<h2>Skills</h2>
			<hr />
			<h4>Programming Languages</h4>
			<p>Python, Javascript/Typescript, Rust.</p>
			<hr class="short-hr" />
			<h4>Scripting Languages</h4>
			<p>Bash and Powershell.</p>
			<hr class="short-hr" />
			<h4>Linux</h4>
			<p>Debian, Ubuntu, NixOS.</p>
			<hr class="short-hr" />
			<h4>VMs & Containerization</h4>
			<p>VMWare, Docker, Kubernetes.</p>
			<hr class="short-hr" />
			<h4>Adminstration</h4>
			<p>
				Linux & Windows Users, M365, Google Suite, Netsuite, Salesforce.
			</p>
			<hr class="short-hr" />
			<h4>Application Management</h4>
			<p>
				Microsofts Excel, Word, Access, Sharepoint, OneDrive, Outlook.
			</p>
			<hr class="short-hr" />
			<h4>Database Management</h4>
			<p>SQL and noSQL DBs.</p>
			<hr class="short-hr" />
			<h4>Networking</h4>
			<p>HTTP, DNS, TCP & UDP.</p>
			<hr />
		</section>

		<section id="experience">
			<h2>Experience</h2>
			<hr />
			<h3>Network Operations Center Analyst Level 1</h3>
			<p><em class="dimmed">April 2025 - January 2026</em></p>
			<ul>
				<li>
					Assisted users located across 250+ companies with a range of
					technical issues.
				</li>
				<li>
					Interact daily with our ticking system to create actionable
					plans for each ticket.
				</li>
				<li>
					Manage and assist users with programs including but not
					limited to SalesForce & Netsuite.
				</li>
				<li>
					Leverage M365 tools and platforms (Azure, Intune, Entra) to
					assist users with their requests.
				</li>
				<li>
					Build powerful and intuitive Powershell scripts for
					colleages to help aid in day-to-day mundane tasks. These
					shell scripts include password resets, shared mailbox
					creation, and user management.
				</li>
				<li>
					Aid our Desktop technician team in provisioning computers,
					deploying them in Intune, and user onboardings.
				</li>
				<li>
					Created an educational guide for new hires when onboarded so
					they can be successful in their role.
				</li>
			</ul>
			<hr />
			<h3>Merchandising Service Associate</h3>
			<ul>
				<li>
					Set and organize shelves based on plans given by vendors and
					merchants.
				</li>
				<li>
					Upkeep shelves stability and looks to meet a weekly quote
					and meet vendor standards.
				</li>
				<li>
					Reset shelves seasonally to rotate new stock in or to change
					the items to match the current retail season.
				</li>
				<li>
					Complete "X" amount of price changes daily to match the new
					prices sent by vendors.
				</li>
			</ul>
			<hr />
		</section>
	</div>

	<div class="flex-container">
		<section id="education">
			<h2>Education</h2>
			<hr />
			<h3>High School</h3>
			<p>Elba High School. September 2008 - June 2021</p>
			<hr class="short-hr" />
			<h3>Certifications</h3>
			<p>Google IT Support Professional</p>
			<p>Python For Everybody - University of Michigan</p>
			<hr class="short-hr">
		</section>
		<section id="projects">
			<h2>Projects</h2>
			<hr />
			<h3>Swiss</h3>
			<p>
				An all in one CLI tool written in Rust that offers various
				miscellaneous tools that aid in a developers workflow. Tools
				include, a search function for the web, favicon converter, build
				tools/options for various languages.
			</p>
			<hr class="short-hr" />
			<h3>Portable Homelab</h3>
			<p>
				A portable homelab built on a Raspberry Pi5 that contains
				multiple containers using Docker to create a transportable
				environment whereever I go. This lab offers network wide ad
				blocking via PiHole and a VPN using Tailscale to access this
				adblocked network whereever I go. This lab also contains a
				GitLab server that contains all of my projects and tools I can
				pull from.
			</p>
			<hr class="short-hr" />
		</section>
	</div>
</main>

<style>
	section {
		padding: 12px;
	}

	hr:not(.short-hr) {
		width: 80%;
		opacity: 25%;
	}

	.short-hr {
		width: 50%;
		opacity: 25%;
	}

	.dimmed {
		opacity: 50%;
	}

	/* Me Section */
	#me {
		margin: 32px auto;
		padding: 32px;
	}

	#intro {
		display: block;
		text-align: center;
		margin: 0 auto;
	}

	#location {
		display: flex;
		justify-content: space-evenly;
	}

	#socials {
		display: flex;
		justify-content: space-evenly;
	}

	#socials a {
		color: black;
	}
	/* Skills and Experience section */

	.flex-container {
		display: flex;
	}

	#skills {
		display: block;
		width: 40%;
		height: 25%;
		border-right: 1px solid black;
		text-align: center;
	}

	#experience {
		display: block;
		width: 60%;
		height: 25%;
		text-align: center;
	}

	#experience li {
		padding: 12px;
		list-style-type: upper-roman;
	}

	/* Education and Projects section */

	.flex-container:nth-child(3) {
		margin-top: 120px;
	}

	#education {
		display: block;
		width: 40%;
		height: 25%;
		border-right: 1px solid black;
		text-align: center;
	}

	#projects {
		display: block;
		width: 60%;
		height: 25%;
		text-align: center;
	}
</style>
