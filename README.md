ITSSLab
Directorio web de plataformas educativas 100 % gratuitas para aprender matemáticas e inglés, desde preescolar hasta la universidad.
🌐 Ver la página: https://gabb031.github.io/mathub/
> ITSSLab era antes conocido como \*MATHUB\*. El repositorio conserva el nombre `mathub` por ahora.
---
¿Qué es ITSSLab?
ITSSLab es una página web que reúne, en un solo lugar, plataformas externas de calidad para aprender. Cada plataforma aparece como una tarjeta con su descripción, nivel, idioma y un enlace directo.
Gratis de verdad: solo se incluyen plataformas cuyo contenido principal es 100 % gratuito.
Sin copiar contenido: ITSSLab no aloja ni incrusta el material de otras páginas. Solo redirige al sitio original, respetando los derechos de autor.
Bilingüe: la página funciona en español e inglés con un selector ES / EN.
Niveles y materias
Niveles	Materias
Preescolar	Matemáticas
Primaria	Inglés
Secundaria	
Bachillerato	
Universidad	
Se puede filtrar por nivel, idioma y materia.
Criterios para incluir una plataforma
Una plataforma entra al catálogo solo si cumple todo lo siguiente:
Su contenido principal es totalmente gratuito (no se aceptan modelos freemium).
Es una plataforma o sitio web, no un canal de YouTube.
Su idioma y nivel están verificados.
Pasa la revisión final del responsable del proyecto.
Se aceptan plataformas con publicidad, siempre que el contenido sea gratuito (por ejemplo, Math is Fun).
Estructura del proyecto
```
ITSSLab/
├── index.html          # Página principal (tarjetas, filtros, selector ES/EN, música)
├── plataformas.json    # Catálogo de plataformas
├── assets/
│   └── str.png         # Logo institucional
└── README.md           # Este archivo
```
La página carga las tarjetas leyendo `plataformas.json`. Si ese archivo falta, las tarjetas no aparecen.
Cómo agregar una plataforma
Verifica que cumpla los criterios de arriba.
Abre `plataformas.json` y agrega un nuevo bloque siguiendo el formato de las plataformas existentes (nombre, enlace, descripción, niveles, materia e idiomas).
Guarda el archivo y súbelo al repositorio.
Espera un par de minutos y recarga la página para ver el cambio.
Música de fondo
La página incluye un reproductor con una playlist de pistas originales generadas por código, por lo que no hay problemas de derechos de autor. Viene apagado por defecto y tiene botones de reproducir/pausar, anterior, siguiente y control de volumen.
Identidad visual
Los colores salen del logo institucional:
Color	HEX
Rojo carmesí	`#A91D22`
Azul marino	`#101828`
Blanco	`#FFFFFF`
Gris plateado	`#D0D5DD`
Hoja de ruta
[x] Base del proyecto y repositorio en GitHub
[x] Primera versión publicada con GitHub Pages
[x] Catálogo inicial verificado
[x] Nuevo nivel Preescolar y materia Inglés
[x] Paleta de colores del logo
[ ] Revisión final del catálogo ampliado
[ ] Más plataformas de Inglés para todos los niveles
[ ] Mejoras de diseño y experiencia de usuario
[ ] Posible backend (PHP/MySQL)
Créditos
Proyecto creado y dirigido por Gabbo (@Gabb031).
Desarrollado con apoyo de herramientas de inteligencia artificial para investigación, código y diseño.
Aviso
ITSSLab no es propietario de las plataformas que enlaza. Todo el contenido, marcas y logos pertenecen a sus respectivos autores.
