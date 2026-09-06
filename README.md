# fabduarte.cl

Sitio académico de Fabián Duarte, profesor asociado del Departamento de Economía,
Universidad de Chile. En vivo en https://fabduarte.cl

## Estructura

Sitio estático, sin frameworks ni dependencias. Para editar contenido basta abrir
el archivo HTML en cualquier editor de texto.

| Inglés | Español | Contenido |
|---|---|---|
| `index.html` | `index-es.html` | Bio, cargos, contacto |
| `research.html` | `research-es.html` | Agenda de investigación por líneas |
| `teaching.html` | `teaching-es.html` | Cursos, bots docentes, tesis |
| `projects.html` | `projects-es.html` | Encuestas, asesorías, fondos, servicio |

Los títulos y abstracts de papers van siempre en inglés, en ambas versiones.

`style.css` es compartido por las ocho páginas. `cv.pdf` es el currículum;
para actualizarlo basta reemplazar el archivo.

## Publicar cambios

    git add -A && git commit -m "descripción" && git push

Los cambios aparecen en el sitio en uno o dos minutos.

## Dominio

`fabduarte.cl` está registrado en NIC Chile y su DNS lo administra Cloudflare,
apuntando a GitHub Pages. El archivo `CNAME` no debe borrarse. El certificado
HTTPS lo emite y renueva GitHub automáticamente.
