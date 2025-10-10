---
title: "Cúmulo"
type: landing

image:
  filename: images/og-cumulo.jpg
  alt_text: "Cúmulo — Agencia y productora de contenidos educativos"

sections:
  # CTA image + paragraph (fondo amarillo claro, padding reducido)
  - block: markdown
    id: cta-image-paragraph
    content:
      text: |
        <section class="w-full py-8 md:py-10" style="background:#FCF1B1;">
          <div class="container mx-auto px-4 md:px-6">
            <div class="grid md:grid-cols-2 gap-8 items-center">
              
              <!-- Imagen -->
              <div class="text-center">
                <img src="/media/cumulo-equipo.jpg" alt="Cúmulo — equipo" class="rounded-2xl shadow-lg mx-auto" />
              </div>

              <!-- Texto -->
              <div>
                <h1 class="text-2xl md:text-3xl font-bold leading-tight" style="color:#3F393B;">
                  Agencia y productora de contenidos para la educación y la ciencia
                </h1>
                <div class="prose md:prose-lg max-w-none mt-3" style="color:#3F393B;">
                  <p class="mb-3">
                    Diseñamos y producimos recursos para la <strong>enseñanza y el aprendizaje</strong> en diversos formatos y plataformas.
                    Acompañamos a <strong>docentes y organizaciones</strong> para fortalecer sus propuestas, elegir el formato adecuado para cada contenido,
                    <strong>estructurar guiones</strong> de clases y crear materiales <strong>visuales, audiovisuales y escritos</strong> que acerquen sus iniciativas a las y los estudiantes.
                  </p>
                </div>
                <div class="mt-4 flex gap-3">
                  <a class="btn btn-primary" href="/contact" style="background:#3E6FBA;border-color:#3E6FBA;">Contacto</a>
                  <a class="btn btn-outline" href="#servicios" style="border-color:#3E6FBA;color:#3E6FBA;">Servicios</a>
                </div>
              </div>

            </div>
          </div>
        </section>
    design:
      full_width: true

  # CTA breve (padding reducido)
  - block: cta
    id: cta-inicio
    content:
      title: "¿Arrancamos?"
      text: "Contanos tu idea y la transformamos en un recorrido claro para tus estudiantes."
      button:
        text: "Conversemos"
        url: "/contact"
    design:
      align: left
      spacing:
        padding: ["16px","0","0","0"]

  # Servicios (features) — padding reducido
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
        padding: ["24px","0","8px","0"]

  # Acompañamiento pedagógico — padding reducido
  - block: markdown
    id: acompanamiento
    content:
      title: "Acompañamiento y asesoramiento pedagógico"
      text: |
        Nos involucramos desde el **inicio**: ideación, lenguajes, formatos y experiencias de aprendizaje.  
        ¿Qué conviene contar en **video** y qué en **material escrito**?  
        ¿La propuesta combina materiales e **instancias sincrónicas**? ¿Cómo articularlas sin repetir contenidos?
        Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto tenga **coherencia**.
        
        <div class="mt-3">
          <a class="btn btn-primary" href="/contact" style="background:#3E6FBA;border-color:#3E6FBA;">Conversemos tu proyecto</a>
        </div>
    design:
      background:
        color: "#FFF8E0"
      spacing:
        padding: ["24px","0","8px","0"]

  # Métricas / Stats — padding reducido
  - block: stats
    id: metricas
    content:
      title: "Métricas"
      items:
        - statistic: "170+"
          description: "clases en formato video"
    design:
      spacing:
        padding: ["16px","0","8px","0"]

  # Testimonios — caja rosa claro, padding moderado
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
      spacing:
        padding: ["20px","0","10px","0"]

  # Logos — título + fila de logos chicos en línea
  - block: markdown
    id: aliados-inline
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        <div class="mt-2 flex flex-wrap items-center gap-4">
          <img src="/logo1.jpg" alt="Logo 1" style="height:36px;width:auto" />
          <img src="/logo2.jpg" alt="Logo 2" style="height:36px;width:auto" />
          <img src="/logo3.jpg" alt="Logo 3" style="height:36px;width:auto" />
          <img src="/logo4.jpg" alt="Logo 4" style="height:36px;width:auto" />
        </div>
    design:
      spacing:
        padding: ["12px","0","8px","0"]

  # CTA final — padding reducido
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
      spacing:
        padding: ["12px","0","8px","0"]
---
