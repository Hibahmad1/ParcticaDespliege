<practica despliege>
---
layout: default
title: "Bienvenido a Mi Sitio Jekyll"
---

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>{{ page.title }}</title>
    <link rel="stylesheet" href="{{ '/assets/styles.css' | relative_url }}">
</head>
<body>
    <header>
        <h1>{{ site.title }}</h1>
        <nav>
            <ul>
                <li><a href="{{ '/' | relative_url }}">Inicio</a></li>
                <li><a href="{{ '/about' | relative_url }}">Sobre mí</a></li>
                <li><a href="{{ '/contact' | relative_url }}">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <h2>Bienvenido a mi sitio web</h2>
            <p>Este es un sitio web generado con Jekyll y GitHub Pages. Aquí puedes aprender más sobre mí y mis proyectos.</p>
        </section>

        <section>
            <h2>Proyectos Recientes</h2>
            <ul>
                <li><strong>Proyecto 1:</strong> Descripción breve del proyecto.</li>
                <li><strong>Proyecto 2:</strong> Descripción breve del proyecto.</li>
                <li><strong>Proyecto 3:</strong> Descripción breve del proyecto.</li>
            </ul>
        </section>

        <section>
            <h2>Testimonios</h2>
            <blockquote>
                "Este sitio es increíble. He aprendido mucho sobre Jekyll." - Usuario Satisfecho
            </blockquote>
            <blockquote>
                "La información es clara y concisa. Muy recomendable." - Otro Usuario
            </blockquote>
        </section>

        <section>
            <h2>Últimas Publicaciones</h2>
            <ul>
                <li><a href="#">Publicación 1: Título de la publicación</a></li>
                <li><a href="#">Publicación 2: Título de la publicación</a></li>
                <li><a href="#">Publicación 3: Título de la publicación</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Mi Sitio Jekyll. Todos los derechos reservados.</p>
        <p>Sígueme en <a href="https://twitter.com/tuusuario" target="_blank">Twitter</a></p>
    </footer>
</body>
</html>
