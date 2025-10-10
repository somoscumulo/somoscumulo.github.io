---
title: "Cúmulo"
type: landing

image:
  filename: images/og-cumulo.jpg
  alt_text: "Cúmulo — Agencia y productora de contenidos educativos"

sections:
  # cta-image-paragraph (reemplaza banner + que-hacemos)
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Agencia y productora de contenidos para la educación y la ciencia"
          text: "Diseñamos y producimos recursos para la <strong>enseñanza y el aprendizaje</strong> en diversos formatos y plataformas.
                    Acompañamos a <strong>docentes y organizaciones</strong> para fortalecer sus propuestas, elegir el formato adecuado para cada contenido,<strong>estructurar guiones</strong> de clases y crear materiales <strong>visuales, audiovisuales y escritos</strong> que acerquen sus iniciativas a las y los estudiantes."
          image: "/cumulo-equipo.jpg"
          button:
            text: "Conversemos"
            url: "/#cta-final"


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

  # Acompañamiento pedagógico
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
          <a class="btn btn-primary" href="/contact" style="background:#3E6FBA;border-color:#3E6FBA;">Conversemos tu proyecto</a>
        </div>
    design:
      background:
        color: "#FFF8E0"

  # Métricas / Stats
  - block: stats
    id: metricas
    content:
      title: "Métricas"
      items:
        - statistic: "170+"
          description: "clases en formato video"

  # Testimonios
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

  # CTA final
  - block: cta
    id: cta-final
    content:
      title: "¿Arrancamos?"
      text: "Contanos tu idea y te ayudamos a convertirla en un recorrido claro para tus estudiantes."
      button:
        text: "Conversemos"
        url: "/contact"
    design:
      align: center

---
