<template>
  <header class="p-3">
      <div class="container">
          <nuxt-link to="/es" >
              <h1 style="font-weight:medium; color: #333">SOYMIZRA.COM</h1>
          </nuxt-link>
        <div class="row">
            <div class="col-sm-12">
                <nav class="navbar navbar-expand-lg navbar-light ">
                    
                    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                        <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarNav">
                        <ul class="navbar-nav">
                        <li class="nav-item active">
                            <nuxt-link class="nav-link" to="/es">Inicio</nuxt-link>
                        </li>
                        <li class="nav-item disabled">
                            <a class="nav-link" href="#">Proyectos</a>
                        </li>
                        <li class="nav-item">
                            <nuxt-link class="nav-link" to="/es/blog">Blog</nuxt-link>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Asesoría</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#" tabindex="-1">Podcast</a>
                        </li>
                        </ul>
                    </div>
                </nav>
            </div>  
        </div>
      <hr>
      </div>
  </header>
</template>
<script>
export default {
  computed: {
    year () {
      return new Date().getFullYear()
    }
  }
}
</script>

<style lang="scss">
.footer {
	&__info {
		background-color: $background-secondary;
		padding: 1.5em 0;
  }
  
  &__info-container {
    display: flex;
    justify-content: space-between;
    width: 100%;
    flex-direction: column;

    @media (min-width: $screen-sm){
      flex-direction: row;
    }
  }

	&__copyright {
		text-align: center;
		@media (min-width: $screen-sm) {
			text-align: inherit;
		}
	}

	&__top-page {
		color: $text-negative;
		display: block;
		text-align: center;
		line-height: 1;
		-webkit-transition: 1s;
		-moz-transition: 1s;
    transition: 1s;
    
		@media (min-width: $screen-sm){
			text-align: right;
		}
	}
}
</style>

