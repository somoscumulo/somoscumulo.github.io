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

# 4.5) Quiénes somos (markdown usando shortcode para Page Resources)
  - block: markdown
    id: quienes-somos
    content:
      title: "Quiénes somos"
      text: |
        <div class="grid grid-cols-2 gap-8 items-start">
          <!-- Julián -->
          <div class="text-center">
            <div class="rounded-full overflow-hidden mx-auto shadow w-28 h-28 md:w-32 md:h-32">
              {{< author_avatar slug="julian" alt="Julián" >}}
            </div>
            <div class="mt-2 font-medium">Julián</div>
          </div>
  
          <!-- Cielo -->
          <div class="text-center">
            <div class="rounded-full overflow-hidden mx-auto shadow w-28 h-28 md:w-32 md:h-32">
              {{< author_avatar slug="cielo" alt="Cielo" >}}
            </div>
            <div class="mt-2 font-medium">Cielo</div>
          </div>
        </div>
    design:
      spacing:
        padding: ["2px","0","2px","0"]

# 6) Organizaciones que confían — grid responsiva (sin scroll)
  - block: markdown
    id: aliados
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        <div class="w-full" style="max-width:100%;">
          <!-- Grid responsiva: columnas auto-fit, logos “anchos” y sin overflow -->
          <div style="
            display:grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 24px 32px;
            align-items:center;">
            
            <div class="flex items-center justify-center">
              <img src="https://somoscumulo.github.io/img/logo1.jpg" alt="Logo 1" style="max-width: 220px; width: 100%; height:auto;" />
            </div>
            <div class="flex items-center justify-center">
              <img src="https://somoscumulo.github.io/img/logo2.jpg" alt="Logo 2" style="max-width: 220px; width: 100%; height:auto;" />
            </div>
            <div class="flex items-center justify-center">
              <img src="https://somoscumulo.github.io/img/logo3.jpg" alt="Logo 3" style="max-width: 220px; width: 100%; height:auto;" />
            </div>
            <div class="flex items-center justify-center">
              <img src="https://somoscumulo.github.io/img/logo4.png" alt="Logo 4" style="max-width: 220px; width: 100%; height:auto;" />
            </div>
  
            <!-- Agregá más logos repitiendo el bloque <div>...</div> -->
          </div>
        </div>
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
