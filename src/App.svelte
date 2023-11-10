<script>
	export let name;
</script>

<main>
	<nav class="navbar navbar-expand-lg navbar-light bg-light">
		<a class="navbar-brand" href="/">
		  <img src="/logo.png" alt="Logo" width="30" height="30">
		</a>
		<div class="collapse navbar-collapse">
		  <ul class="navbar-nav mr-auto">
			<li class="nav-item">
			  <a class="nav-link" href="#produits">Produits</a>
			</li>
			<li class="nav-item">
			  <a class="nav-link" href="#linkit">Link IT</a>
			</li>
			<li class="nav-item">
			  <a class="nav-link" href="#contact">Contact</a>
			</li>
		  </ul>
		</div>
	  </nav>
	  



	<div class="container">
		<h1>Link IT</h1>
		<!-- Plus de contenu ici -->
	  </div>



	  <footer class="footer mt-auto py-3 bg-light">
		<div class="container">
		  <span class="text-muted">Placez ici vos informations de contact.</span>
		  <ul class="list-unstyled">
			<li><a href="#produits">Produits</a></li>
			<li><a href="#linkit">Link IT</a></li>
			<li><a href="#contact">Contact</a></li>
		  </ul>
		</div>
	  </footer>
</main>

<style>
	main {
		padding: 0;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	/* Styles personnalisés pour le header */
	.navbar {
    /* Style pour la barre de navigation */
  }

	.navbar-brand {
		/* Style pour le logo */
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}

	.footer {
    /* Styles personnalisés pour le footer */
  }

	.footer .container {
		/* Style pour le conteneur à l'intérieur du footer */
	}

	.footer .text-muted {
		/* Style pour le texte du footer */
	}

	.footer ul {
		/* Style pour la liste dans le footer */
	}

	.footer ul li {
		/* Style pour les éléments de liste */
	}

	.footer ul li a {
		/* Style pour les liens dans le footer */
	}
</style>