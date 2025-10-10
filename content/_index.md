---
title: "Cúmulo"
type: landing

image:
  filename: images/og-cumulo.jpg
  alt_text: "Cúmulo — Agencia y productora de contenidos educativos"

sections:
  # Banner full ancho con fondo + imagen
  - block: markdown
    id: banner
    content:
      text: |
        <div class="w-full py-12 md:py-16" style="background:#FCF1B1;">
          <div class="container mx-auto px-4 md:px-6">
            <div class="grid md:grid-cols-2 gap-8 items-center">
              <div>
                <p class="uppercase tracking-wide font-semibold mb-2" style="color:#3E6FBA;">Agencia & productora</p>
                <h1 class="text-3xl md:text-4xl font-bold leading-tight" style="color:#3F393B;">Contenidos para la educación y la ciencia</h1>
                <p class="mt-4 text-lg md:text-xl" style="color:#3F393B;">Imaginamos, diseñamos y producimos recursos claros, visuales y accesibles para enseñar y aprender.</p>
                <div class="mt-6 flex gap-3">
                  <a class="btn btn-primary" href="/contact">Contacto</a>
                  <a class="btn btn-outline" href="#servicios" style="border-color:#3E6FBA;color:#3E6FBA;">Servicios</a>
                </div>
              </div>
              <div class="text-center">
                <img src="/media/cumulo-equipo.jpg" alt="Cúmulo — equipo" class="rounded-2xl shadow-lg mx-auto" />
              </div>
            </div>
          </div>
        </div>
    design:
      full_width: true

  # Qué hacemos
  - block: markdown
    id: que-hacemos
    content:
      title: "Qué hacemos"
      text: |
        Diseñamos y producimos recursos para la **enseñanza y el aprendizaje** en diversos formatos y plataformas.
        Acompañamos a **docentes y organizaciones** para fortalecer sus propuestas, elegir el formato adecuado para cada contenido,
        **estructurar guiones** de clases y crear materiales **visuales, audiovisuales y escritos** que acerquen sus iniciativas a las y los estudiantes.
    design:
      background:
        color: ""

  # CTA intermedio (usa tu bloque cta)
  - block: cta
    id: cta-inicio
    content:
      title: "¿Arrancamos?"
      text: "Contanos tu idea y te ayudamos a convertirla en un recorrido claro para tus estudiantes."
      button:
        text: "Conversemos"
        url: "/contact"
    design:
      align: left

  # Servicios (features)
  - block: features
    id: servicios
    content:
      title: "Nuestros servicios"
      items:
        - name: "Clases en formato video"
          description: "Ponemos a disposición todas las posibilidades del lenguaje audiovisual para diseñar clases que transformen la experiencia de tus estudiantes."
        - name: "Videos institucionales"
          description: "Acompañamos en el guionado y llevamos adelante la producción y edición de videos para presentar tu organización."
        - name: "Facilitación visual para pósters científicos"
          description: "Síntesis visual, jerarquía de información y diagramación para comunicar resultados con impacto."
        - name: "Ilustraciones para presentaciones y contenidos educativos"
          description: "Ilustraciones conceptuales y funcionales para clases, guías y presentaciones."
        - name: "Materiales escritos e interactivos"
          description: "Corrección de textos y diseño editorial para materiales de lectura e interactivos."
    design:
      columns: "2"

  # Acompañamiento pedagógico (con color de acento suave)
  - block: markdown
    id: acompanamiento
    content:
      title: "Acompañamiento y asesoramiento pedagógico"
      text: |
        Nos involucramos desde el **inicio**: ideación, lenguajes, formatos y experiencias de aprendizaje.  
        ¿Qué conviene contar en **video** y qué en **material escrito**?  
        ¿La propuesta combina materiales e **instancias sincrónicas**? ¿Cómo articularlas sin repetir contenidos?
        Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto tenga **coherencia**.
        
        <div class="mt-4">
          <a class="btn btn-primary" href="/contact">Conversemos tu proyecto</a>
        </div>
    design:
      background:
        color: "#FFF8E0"  # derivado del amarillo de la paleta

  # Métricas / Stats
  - block: stats
    id: metricas
    content:
      title: "Métricas"
      items:
        - statistic: "170+"
          description: "clases en formato video"
    design:
      background:
        color: ""

  # Testimonios (caja con rosa claro)
  - block: testimonials
    id: testimonios
    content:
      title: "Testimonios"
      items:
        - name: "Estefanía Michlig"
          role: "Fundación Empretec"
          text: >
            "Lo que más valoramos es la **calidad** de los videos y el enorme **compromiso** con el que trabajan.
            No se limitan a entregar lo que pedimos: buscan que todo quede **claro, atractivo y realmente útil** para el usuario.
            Nos encanta que propongan mejoras de manera constante y que se pongan manos a la obra para lograr un producto cada vez mejor.
            La **cercanía**, la **rapidez de respuesta** y la **dedicación** para asegurarse de que todo quede perfecto hacen que trabajar juntos sea siempre un gusto."
    design:
      background:
        color: "#FFBBD5"

  # Logos de organizaciones
  - block: collection
    id: aliados
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: "Algunas de las organizaciones con las que colaboramos."
      items:
        - title: "Fundación Empretec"
          image:
            filename: images/logos/empretec.png
            alt_text: "Fundación Empretec"
        - title: "Capacitar (Min. Des. Productivo)"
          image:
            filename: images/logos/capacitar.png
            alt_text: "Capacitar"
        - title: "Banco Nación"
          image:
            filename: images/logos/bna.png
            alt_text: "Banco Nación"
        - title: "Academia Bancor"
          image:
            filename: images/logos/bancor.png
            alt_text: "Academia Bancor"
    design:
      columns: "4"
      card:
        style: "image"

  # CTA final (usa tu bloque cta)
  - block: cta
    id: cta-final
    content:
      title: "¿Vemos tu proyecto?"
      text: "Diseñamos el mejor formato para tus objetivos y tu audiencia."
      button:
        text: "Escribinos"
        url: "/contact"
    design:
      align: center
---
