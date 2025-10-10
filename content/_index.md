---
title: "Cúmulo"
type: landing

sections:

  # 1) CTA image + paragraph (fondo amarillo, logo reducido 30%)
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Agencia y productora de contenidos para la educación y la ciencia"
          text: "Diseñamos y producimos recursos para la <strong>enseñanza y el aprendizaje</strong> en diversos formatos y plataformas. Acompañamos a <strong>docentes y organizaciones</strong> para fortalecer sus propuestas, elegir el formato adecuado para cada contenido, <strong>estructurar guiones</strong> de clases y crear materiales <strong>visuales, audiovisuales y escritos</strong> que acerquen sus iniciativas a las y los estudiantes."
          image: "cumulo.png" 
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
        - name: "Clases en formato video"
          description: "Ponemos a disposición todas las posibilidades del lenguaje audiovisual para diseñar clases que transformen la experiencia de tus estudiantes."
        - name: "Videos institucionales"
          description: "Acompañamos en el guionado y llevamos adelante la producción y edición de videos para presentar tu organización."
        - name: "Ilustración original para presentaciones"
          description: "Creamos ilustraciones a medida que fortalecen la comunicación visual de tus presentaciones. Definimos objetivos y estilo junto al equipo."
        - name: "Facilitación visual para pósters científicos"
          description: "Diseñamos e ilustramos pósters que combinan claridad conceptual y coherencia visual. Organizamos la información y destacamos aportes clave."
        - name: "Paquete de ilustraciones (banco de imágenes)"
          description: "Desarrollamos un banco de ilustraciones originales adaptable a múltiples formatos. Definimos líneas estéticas y temáticas de tu proyecto."
        - name: "Materiales escritos e interactivos"
          description: "Corrección de textos y diseño editorial para materiales de lectura e interactivos."
    design:
      columns: "2"
      spacing:
        padding: ["12px","0","6px","0"]

  # 3) Acompañamiento (cta-image-paragraph, fondo azul, texto blanco, sin botón)
  - block: cta-image-paragraph
    id: acompanamiento
    content:
      items:
        - title: "<span style='color:#FFFFFF'>Acompañamiento y asesoramiento pedagógico</span>"
          text: "<span style='color:#FFFFFF'>Nos involucramos desde el <strong>inicio</strong>: ideación, lenguajes, formatos y experiencias de aprendizaje. ¿Qué conviene contar en <strong>video</strong> y qué en <strong>material escrito</strong>? ¿La propuesta combina materiales e <strong>instancias sincrónicas</strong>? ¿Cómo articularlas sin repetir contenidos? Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto tenga <strong>coherencia</strong>.</span>"
          image: "cumuloilus-08.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "max-width:80%"
    design:
      background:
        color: "#3E6FBA"

  # 4) Métricas / Stats (menos margen)
  - block: stats
    id: metricas
    content:
      title: "Métricas"
      items:
        - statistic: "170+"
          description: "clases en formato video"
        - statistic: "40+"
          description: "docentes trabajaron con Cúmulo"
        - statistic: "10"
          description: "propuestas de formación acompañadas"
    design:
      spacing:
        padding: ["6px","0","4px","0"]   # menos espacio

  # 4.5) People (requiere partial hbx/blocks/people/block.html)
  - block: people
    id: people
    content:
      title: "Quiénes somos"
      authors:
        - slug: "julian"
          name: "Julián"
        - slug: "cielo"
          name: "Cielo"
    design:
      columns: 2
      spacing:
        padding: ["4px","0","4px","0"]   # muy poco espacio para pegarse a métricas/testimonios

  # 5) Testimonios (menos margen)
  - block: testimonials
    id: testimonios
    content:
      title: "Testimonios"
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
        padding: ["4px","0","6px","0"]

  # 6) Organizaciones que confían — logos inline (usar /media/logos/)
  - block: markdown
    id: aliados
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        <div class="mt-2 flex flex-wrap items-center gap-4">
          <img src="/media/logos/logo1.jpg" alt="Logo 1" style="height:36px;width:auto" />
          <img src="/media/logos/logo2.jpg" alt="Logo 2" style="height:36px;width:auto" />
          <img src="/media/logos/logo3.jpg" alt="Logo 3" style="height:36px;width:auto" />
          <img src="/media/logos/logo4.jpg" alt="Logo 4" style="height:36px;width:auto" />
        </div>
    design:
      spacing:
        padding: ["6px","0","8px","0"]

  # 7) CTA final (bloque cta real con contenido visible)
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
      background:
        color: "#F4A26D"
      container:
        max_width: "1280px"
      spacing:
        padding: ["36px","0","36px","0"]

  # 8) CSS puntual al final y sin ocupar espacio visual
  - block: markdown
    id: style-fixes
    content:
      text: |
        <style>
          #metricas h2, #testimonios h2, #aliados h2, #people h2 {
            margin-top: 0.25rem; margin-bottom: 0.25rem;
          }
        </style>
    design:
      spacing:
        padding: ["0","0","0","0"]
---
