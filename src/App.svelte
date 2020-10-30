<script>
</script>

<main   id="contenido"> 
    <header class="header">
      <div class="container">
        <figure class="logo">
          <img src="static/1image.jpg" height="50" alt="prueba svelte" />
        </figure>
        <nav class="menu">
          <ol>
            <li>
              <a class="link" href="#portafolio">Portafolio</a>
            </li>
            <li>
              <a class="link" href="#eventos">Experiencia</a>
            </li>
            <li>
              <a class="link" href="#contacto">Blog</a>
            </li>
          </ol>
        </nav>
      </div>
    </header>

		<div class="banner">
			<div class="banner-text">
			  <h1>Header </h1>
			  <h6>Web development Marketing Finance templates</h6>
			</div>
		  </div>
    
    <section class="portfolio">
      <div class="container">
        <h2>Portafolio</h2>
      <article class="project">
        <div class="project-details">
          <h3 class="project-title">Next Events</h3>
          <h6 class="project-course">Curso react native muy pronto</h6>
          <p class="project-date"><small><strong>Fecha:</strong> 01/11/2020</small></p>
          <p class="project-url"><small><strong>Puedes verlo en:</strong> </small></p>
          <p class="project-description">
              Curso de react native muy pronto</p>
        </div>
        <figure class="project-imageContainer">
          <img class="project-image" width="500" src="1image.jpg" alt="proyecto">
        </figure>
      </article>
      <article class="project">
          <div class="project-details">
            <h3 class="project-title">Curso Marketing Digital & Webmaster</h3>
            <h6 class="project-course"> SEO Science </h6>
            <p class="project-date"><small><strong>Fecha:</strong> 01/07/2018</small></p>
            <p class="project-url"><small><strong>Puedes verlo en:</strong>daltramarket</small></p>
            <p class="project-description"> Muy pronto</p>
          </div>
          <figure class="project-imageContainer">
            <img class="project-image" width="500" src="static/1image.jpg" alt="prouyecto del curso de React Native">
          </figure>
        </article>
      </div>
      
    </section>
    <div class="container">
      <h2 class="event-list-title">Proximos proyectos</h2>
    </div>
    <section id="eventos" class="event-list">
      <div class="container">
        <article class="event">
          <figure class="event-imageContainer">
            <img class="event-image" src="static/wave.jpg" width="500" alt=""/>
          </figure>
          <div class="event-detail">
            <h3 class="event-title">Conferencia grafica sobre programacion </h3>
            <p class="event-description">Aprendizaje recursivo </p>
            <a class="event-url" href="https://www.instagram.com/digital_minds" target="_blank">Ver Plática</a>
          </div>
        </article>
        <article class="event">
          <figure class="event-imageContainer">
            <img class="event-image" src="images/platzi-conf.jpg" width="500" alt=" eventos" />
          </figure>
          <div class="event-detail">
            <h3 class="event-title">Octubre 2020</h3>
            <p class="event-description">Claridad en la programacion</p>
            <a class="event-url" href="www.digitalminds.com/conferencia" target="_blank">Conectate ahora</a>
          </div>
        </article>
        <article class="event">
          <figure class="event-imageContainer">
            <img class="event-image" src="images/platzi-conf.jpg" width="500" alt="events"/>
          </figure>
          <div class="event-detail">

          </div>
        </article>
        <article class="event">
          <figure class="event-imageContainer">
            <img class="event-image" src="images/platzi-conf.jpg" alt = "imagen no cargada " width="500" />
          </figure>
          <div class="event-detail">
            <h3 class="event-title">Siguientes cursos</h3>
            <p class="event-description">Marketing organico  </p>
            <img class="event-url" alt="name" src="wave.jpg" />
        </article>
      </div>
    </section>
    <section class="contact">
      <div class="container">
        <form action="/suscripcion/" class="form-email">
          <h3>¿Creamos algo juntos?</h3>
          <input type="text" placeholder="Déjame tu email" id="email">
          <button>Enviar</button>
        </form>
        <div class="social">
          <a href="https://twitter.com/daajt1" class="social-link twitter">twitter</a>
          <a href="https://facebook.com/daaqt" class="social-link facebook">facebook</a>
          <a href="https://github.com/daajt1" class="social-link github">github</a>
          <a href="https://instagram.com/digitalminds" class="social-link instagram">instagram</a>
        </div>
      </div>
    </section>
    <footer class="footer">
      <div class="container">
        <div>
          <p>Pagina desarrollada por Daniel Juarez
		
		</div>
		
        <div>
			

			<a href="instagram.com/digitalminds.com">
			
        </div>
      </div>
    </footer>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}
h1, 
h2,
h3,
h6{
  font-family: 'Fjalla One', sans-serif;
  font-weight: normal;
}

h1 {
  font-size: 40px;
  line-height: 1.5;
  letter-spacing: -.2px;
  color: white;
  margin: 0;
  /* margin: 100px 150px 70px 30px; */
  /* text-transform: uppercase; */
  /* text-decoration: dashed; */
}

ol {
	margin: 0;
  padding: 0;
  list-style: none;
}
h2 {
  color: #b6d1f5;
  text-transform: uppercase;
  font-family: 'Source Sans Pro', sans-serif;
  font-weight: bold;
  font-size: 24px;
  margin-bottom: 40px;
}






.portfolio {
  background: #fafafa;
  padding: 20px;
  /* background: red; */
}

.banner h1, .banner h6 {
  margin: 0;
  text-shadow: 2px 2px 6px #000;
  text-align: center;
}

.banner {
  color: white;
  background-image: image('/static/wave.jpg');
  height: 300px;
  width: auto;
  display: flex;
  justify-content: center;
  align-items: center;
}

.project {
  
  border: 1px solid gray;
  border-radius: 10px;
  margin-bottom: 15px;
  /* margin-right
  margin-left 
  margin-top */
  padding: 20px;
  background: white;
  display: flex;
  align-items: center;
  justify-content: space-between;
}
.project-course,
.project-date,
.project-url {
  margin: 10px 0;
}
.project-description {
  font-size: 20px;
}
.project strong {
  font-family: 'Fjalla One', sans-serif;
}
.project-title {
  font-size: 30px;
  margin-top: 0;
  margin-bottom: 10px;
}


.project-details {
  width: 500px;
}

.project-imageContainer {
  width: 500px;
}

.header {
  background-color: #1b2127;
  color: white;
  display: flex;
  height: 70px;
  align-items: center;
  justify-content: space-between;
}

ol,
figure {
  margin: 0;
}

.header a {
  color: white;
  text-decoration: none;
}
.menu {
  height: inherit;
}
.header ol {
  display: flex;
  height: inherit;
}
.header ol li {
  height: inherit;
}
.header a {
  display: flex;
  align-items: center;
  height: inherit;
  padding: 0 10px;
}




.footer {
  color: white;
  background-color: #1b2127;
  display: flex;
  align-items: center;
  justify-content: space-between;
}


.footer a {
  color: white;
}

.event-list {
  display: flex;
  flex-wrap: wrap;
}
.event-list-title {
  margin-left: 20px;
}
.event { 
  margin: 10px;
  width: 480px;
  flex-shrink: 0;
  border-radius: 10px;
  overflow: hidden;
  background: #f4fbff;
}
.event img {
  width: 480px;
  height: 200px;
  object-fit: cover;
}
.event-detail {
  margin: 20px 40px;
  margin-top: -40px;
  background-color: white;
  position: relative;
  padding: 20px;
  text-align: center;
}
.event-description {
  text-align: left;
}

.event-url {
  color: #056fff;
  border: 1px solid;
  padding: 5px 20px;
  text-decoration: none;
  border-radius: 5px;
}

.contact {
  background-color: #056fff;
  color: white;
  height: 150px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}


.social {
  display: inline-block;
  width: 50px;
  height: 50px;
  margin: 0 10px;
  background-size: 50px 50px;
}

.social-link.twitter {
  background-image: url('../images/twitter.svg');
}
.social-link.facebook {
  background-image: url('../images/facebook.svg');
}
.social-link.github {
  background-image: url('../images/github.svg');
}
.social-link.instagram {
  background-image: url('../images/instagram.svg');
}


.form-email input {
  border-color: gray;
  border-style: solid;
  border-radius: 10px;
  padding: 10px 20px 10px 25px;
  background-size: 15px 15px;
  background-repeat: no-repeat;
  background-position-y: center;
  background-position-x: 5px;
}

.form-email button {
  display: block;
  background: transparent;
  color: white;
  padding: 10px 0;
  border-radius: 5px;
  width: 100px;
  margin-top: 10px;
}

.form-email h3 { 
  font-family: 'Source Sans Pro', sans-serif;
}

.container {
  /* border: 1px solid red; */
  width: 1000px;
  margin: 0 auto;
  display: inherit;
  justify-content: inherit;
  align-items: inherit;
  height: inherit;
  flex-wrap: inherit;
}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}

	#contenido { width: 800px; margin: 0 auto; }
</style>