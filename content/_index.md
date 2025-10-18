---
title: "Cúmulo"
type: landing

image:
  filename: images/og-cumulo.jpg
  alt_text: "Cúmulo — Agencia y productora de contenidos educativos"

sections:

  # 1) CTA image + paragraph (fondo amarillo, logo reducido ~30%)
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Agencia y productora de contenidos para la educación y la ciencia"
          text: "Diseñamos y producimos recursos para la <strong>enseñanza y el aprendizaje</strong> en diversos formatos y plataformas. Acompañamos a <strong>docentes y organizaciones</strong> para fortalecer sus propuestas, elegir el formato adecuado para cada contenido, <strong>estructurar guiones</strong> de clases y crear materiales <strong>visuales, audiovisuales y escritos</strong> que acerquen sus iniciativas a las y los estudiantes."
          image: "cumulo.png"           # archivo en assets/media/
          image_alt: "Logotipo Cúmulo"
          image_style: "max-width:70%"
          button:
            text: "Conversemos"
            url: "/#cta-final"
    design:
      background:
        color: "#FCF1B1"

  # 2) Servicios (features)
  - block: features
    id: servicios
    content:
      title: "Nuestros servicios"
      items:
        - name: "Producción de videos educativos"
          description: "Creamos clases en video que convierten el contenido en experiencias de aprendizaje. Desde la ideación y el guion hasta la producción y la edición, integramos recursos audiovisuales en múltiples formatos para comunicar con claridad e impacto."
        - name: "Ilustración científica y facilitación visual"
          description: "Desarrollamos recursos visuales que complementan materiales en proyectos de formación e investigación, para que cada imagen refuerce el contenido y mejore la experiencia de aprendizaje.
Trabajamos en distintos formatos: presentaciones para clases o eventos, pósters científicos, materiales de lectura, entre otros."
        - name: "Acompañamiento en el diseño pedagógico"
          description: "Antes de producir contenidos, ofrecemos asesoramiento para diseñar la propuesta según el perfil de las y los estudiantes y los temas a desarrollar.
Nos involucramos desde el inicio en la ideación y en la selección de formatos, recursos y modalidades del contenido a producir.
Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto mantenga coherencia."
    design:
      columns: "3"
      spacing:
        padding: ["12px","0","6px","0"]

  # 3) Acompañamiento (cta-image-paragraph, fondo azul, texto blanco, sin botón)
  - block: cta-image-paragraph
    id: servicios
    content:
      items:
        - title: "<span style='color:#FFFFFF'>Producción de videos educativos</span>"
          text: "<span style='color:#FFFFFF'>Creamos clases en video que convierten el contenido en experiencias de aprendizaje. Desde la ideación y el guion hasta la producción y la edición, integramos recursos audiovisuales en múltiples formatos para comunicar con claridad e impacto."
          image: "cumuloilus-08.png"    # archivo en assets/media/
          image_alt: "Ilustración Cúmulo"
          image_style: "max-width:80%"
        - title: "<span style='color:#FFFFFF'>Ilustración científica y facilitación visual</span>"
          text: "<span style='color:#FFFFFF'>Desarrollamos recursos visuales que complementan materiales en proyectos de formación e investigación, para que cada imagen refuerce el contenido y mejore la experiencia de aprendizaje.
Trabajamos en distintos formatos: presentaciones para clases o eventos, pósters científicos, materiales de lectura, entre otros."
          image: "cumuloilus-08.png"    # archivo en assets/media/
          image_alt: "Ilustración Cúmulo"
          image_style: "max-width:80%"
        - title: "<span style='color:#FFFFFF'>Acompañamiento y asesoramiento pedagógico</span>"
          text: "<span style='color:#FFFFFF'>Antes de producir contenidos, ofrecemos asesoramiento para diseñar la propuesta según el perfil de las y los estudiantes y los temas a desarrollar.
Nos involucramos desde el inicio en la ideación y en la selección de formatos, recursos y modalidades del contenido a producir.
Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto mantenga coherencia."
          image: "cumuloilus-08.png"    # archivo en assets/media/
          image_alt: "Ilustración Cúmulo"
          image_style: "max-width:80%"
    design:
      background:
        color: "#3E6FBA"

  # 4) Métricas / Stats (SIN título)
  - block: stats
    id: metricas
    content:
      items:
        - statistic: "170+"
          description: "clases en formato video"
        - statistic: "40+"
          description: "docentes trabajaron con Cúmulo"
        - statistic: "10"
          description: "propuestas de formación acompañadas"
    design:
      spacing:
        padding: ["6px","0","2px","0"]   # compacto

 # 4.5) Quiénes somos (avatars y nombres linkean a /authors/<slug>/)
  - block: markdown
    id: quienes-somos
    content:
      title: "Quiénes somos"
      text: |
        <div class="grid grid-cols-2 gap-8 items-start">
          <!-- Julián -->
          <a href="/authors/julian/" class="text-center group" aria-label="Ir al perfil de Julián">
            <div class="rounded-full overflow-hidden mx-auto shadow w-28 h-28 md:w-32 md:h-32 flex items-center justify-center">
              {{< author_avatar slug="julian" alt="Julián" >}}
            </div>
            <div class="mt-2 font-medium group-hover:underline">Julián</div>
          </a>
  
          <!-- Cielo -->
          <a href="/authors/cielo/" class="text-center group" aria-label="Ir al perfil de Cielo">
            <div class="rounded-full overflow-hidden mx-auto shadow w-28 h-28 md:w-32 md:h-32 flex items-center justify-center">
              {{< author_avatar slug="cielo" alt="Cielo" >}}
            </div>
            <div class="mt-2 font-medium group-hover:underline">Cielo</div>
          </a>
        </div>
    design:
      spacing:
        padding: ["2px","0","2px","0"]



  - block: markdown
    id: aliados
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        {{< logos_grid >}}
    design:
      spacing:
        padding: ["6px","0","8px","0"]


  # 5) Testimonios (SIN título)
  - block: testimonials
    id: testimonios
    content:
      items:
        - name: "Estefanía Michlig"
          role: "Fundación Empretec"
          text: >
            Lo que más valoramos es la **calidad** de los videos y el enorme **compromiso** con el que trabajan.
            No se limitan a entregar lo que pedimos: buscan que todo quede **claro, atractivo y realmente útil** para el usuario.
            Nos encanta que propongan mejoras de manera constante y que se pongan manos a la obra para lograr un producto cada vez mejor.
            La **cercanía**, la **rapidez de respuesta** y la **dedicación** para asegurarse de que todo quede perfecto hacen que trabajar juntos sea siempre un gusto.
    design:
      spacing:
        padding: ["2px","0","6px","0"]
    
  # 7) CTA final — cta-card (usa design.card.* como el ejemplo que te funciona)
  - block: cta-card
    id: cta-final
    content:
      title: "¿Arrancamos?"
      text: |
        Contanos tu idea y te ayudamos a convertirla en un recorrido claro para tus estudiantes.
      button:
        text: "Conversemos"
        url: "/contact"
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#F4A26D;color:#3F393B;text-align:center; padding: 2.5rem; border-radius: 1rem;"

  # 8) CSS puntual al final (no ocupa espacio)
  - block: markdown
    id: style-fixes
    content:
      text: |
        <style>
          /* si volvés a poner títulos, mantenemos el margen reducido */
          #metricas h2, #testimonios h2, #aliados h2, #people h2 {
            margin-top: 0.25rem; margin-bottom: 0.25rem;
          }
        </style>
    design:
      spacing:
        padding: ["0","0","0","0"]
---
