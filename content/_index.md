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

  # 2) Servicios — markdown con imagen superior por card (usar /static/media/cumuloilus-08.png)
  - block: markdown
    id: servicios
    content:
      title: "Nuestros servicios"
      text: |
        <div class="grid md:grid-cols-3 gap-8">
          <!-- Card 1 -->
          <div class="text-center">
            <img src="/media/cumuloilus-08.png" alt="Ilustración Cúmulo" style="max-height:64px;margin:0 auto 8px auto;display:block;">
            <h3 class="text-lg font-semibold">Producción de videos educativos</h3>
            <p class="mt-2">Diseñamos clases en video que convierten el contenido en experiencias de aprendizaje. Desde la ideación y el guion hasta la producción y la edición, integramos recursos audiovisuales en múltiples formatos para comunicar con claridad e impacto.</p>
          </div>

          <!-- Card 2 -->
          <div class="text-center">
            <img src="/media/cumuloilus-08.png" alt="Ilustración Cúmulo" style="max-height:64px;margin:0 auto 8px auto;display:block;">
            <h3 class="text-lg font-semibold">Ilustración científica y facilitación visual</h3>
            <p class="mt-2">Desarrollamos recursos visuales que complementan materiales en proyectos de formación e investigación, para que cada imagen refuerce el contenido y mejore la experiencia de aprendizaje. Trabajamos en distintos formatos: presentaciones para clases o eventos, pósters científicos, materiales de lectura, entre otros.</p>
          </div>

          <!-- Card 3 -->
          <div class="text-center">
            <img src="/media/cumuloilus-08.png" alt="Ilustración Cúmulo" style="max-height:64px;margin:0 auto 8px auto;display:block;">
            <h3 class="text-lg font-semibold">Acompañamiento en el diseño pedagógico</h3>
            <p class="mt-2">Antes de producir contenidos, ofrecemos asesoramiento para diseñar la propuesta según el perfil de las y los estudiantes y los temas a desarrollar. Nos involucramos desde el inicio en la ideación y en la selección de formatos, recursos y modalidades del contenido a producir. Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto mantenga coherencia.</p>
          </div>
        </div>
    design:
      spacing:
        padding: ["12px","0","6px","0"]

  # 3) Métricas / Stats (SIN título) — fondo celeste y letra blanca
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
      background:
        color: "#3E6FBA"
      spacing:
        padding: ["12px","0","12px","0"]

  # 4) Quiénes somos (avatars y nombres linkean a /authors/<slug>/)
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

  # 5) Organizaciones que confían — tira horizontal (nowrap, scroll suave si hace falta)
  - block: markdown
    id: aliados
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        <div class="w-full" style="max-width:100%;overflow-x:auto;scroll-behavior:smooth;">
          <div class="flex items-center gap-8 flex-nowrap py-2" style="min-width:max-content;">
            <!-- Cambiá las rutas por tus archivos locales en /static/media/logos/ -->
            <img src="/media/logos/logo1.jpg" alt="Logo 1" style="height:64px;width:auto;flex:0 0 auto;">
            <img src="/media/logos/logo2.jpg" alt="Logo 2" style="height:64px;width:auto;flex:0 0 auto;">
            <img src="/media/logos/logo3.jpg" alt="Logo 3" style="height:64px;width:auto;flex:0 0 auto;">
            <img src="/media/logos/logo4.png" alt="Logo 4" style="height:64px;width:auto;flex:0 0 auto;">
            <!-- Agregá más logos repitiendo la línea de <img> -->
          </div>
        </div>
    design:
      spacing:
        padding: ["6px","0","8px","0"]

  # 6) Testimonios (SIN título)
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

  # 7) CTA final — cta-card
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
        css_style: "background-color:#F4A26D;color:#3F393B;text-align:center;padding:2.5rem;border-radius:1rem;"

  # 8) CSS puntual al final (no ocupa espacio)
  - block: markdown
    id: style-fixes
    content:
      text: |
        <style>
          /* Métricas en blanco sobre #3E6FBA */
          #metricas, #metricas * { color:#FFFFFF !important; }
          /* Margen reducido en títulos si se usan */
          #metricas h2, #testimonios h2, #aliados h2, #people h2 { margin-top: .25rem; margin-bottom: .25rem; }
        </style>
    design:
      spacing:
        padding: ["0","0","0","0"]
---
