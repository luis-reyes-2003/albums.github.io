<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Mis 500 álbumes favoritos." />
  <title>Mis Reseñas Musicales</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header -->
  <header>
    <nav class="container nav">
      <a href="#inicio" class="brand">
        <span class="logo"></span>
        <span>Mis álbumes favoritos</span>
      </a>
      <div class="menu">
        <a href="#albums">Álbumes</a>
        <a href="#sobre-mi">Sobre mí</a>
      </div>
    </nav>
  </header>

  <!-- Hero -->
  <main id="inicio" class="container">
    <h1>Bienvenido a mi refugio musical</h1>
    <p class="lead">Aquí comparto mis pensamientos, impresiones y reseñas sobre los álbumes que más me han marcado.</p>
    <a class="btn btn-primary" href="#albums">Mis reseñas</a>
  </main>

  <!-- Álbumes -->
  <section id="albums" class="container">
    <h2>Mis Álbumes Favoritos</h2>
    <div class="album-list" id="albums">
    <!-- Aquí se insertarán los álbumes dinámicamente -->
    </div>
  </section>

  <!-- Sobre mí -->
  <section id="sobre-mi" class="container">
    <h2>Sobre mí</h2>
    <p>Hola, soy Luis y como saben la música es una de mis grandes pasiones. Aquí compartiré la lista de mis 500 álbumes que considero importantes en mi vida. Mi objetivo es registrar mi viaje musical y tal vez inspirar a otros a descubrir nuevos sonidos.</p>
  </section>

  <!-- Footer -->
  <footer>
    <div class="container">&copy; <span id="year"></span> Mis Reseñas Musicales</div>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
  <script>
  async function cargarAlbums() {
    try {
      const res = await fetch('albums.json');
      const albums = await res.json();
      const contenedor = document.getElementById('albums');

      contenedor.innerHTML = albums.map((album, i) => `
        <article class="album">
          <h2><span class="album-numero">#${i + 1} - ${album.titulo} (${album.year})</span></h2>
          <img src="${album.portada}" alt="Portada de ${album.titulo}">
          <h3>${album.titulo}</h3>
          <p>${album.artista}</p>
          <p>${album.year}</p>
          <p>${album.genero}</p>
        </article>
      `).join('');
    } catch (error) {
      console.error("Error al cargar los álbumes:", error);
    }
  }

    cargarAlbums();
  </script>
</body>
</html>