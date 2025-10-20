---
title: "Cúmulo"
type: landing

image:
  filename: images/og-cumulo.jpg
  alt_text: "Cúmulo — Agencia y productora de contenidos educativos"

sections:

  # 1) CTA image + paragraph (fondo amarillo, logo reducido ~40%)
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Agencia y productora de contenidos para la educación y la ciencia"
          text: "Diseñamos y producimos recursos para la <strong>enseñanza y el aprendizaje</strong> en diversos formatos y plataformas. Acompañamos a <strong>docentes y organizaciones</strong> para fortalecer sus propuestas, elegir el formato adecuado para cada contenido, <strong>estructurar guiones</strong> de clases y crear materiales <strong>visuales, audiovisuales y escritos</strong> que acerquen sus iniciativas a las y los estudiantes."
          image: "cumulo.png"
          image_alt: "Logotipo Cúmulo"
          image_style: "max-width:42%"
          button:
            text: "Conversemos"
            url: "/#cta-final"
    design:
      background:
        color: "#FCF1B1"

  # 3) Servicios destacados (DOBLE de grandes, botones invertidos blanco/azul)
  - block: cta-image-paragraph
    id: servicios-destacados
    content:
      title: "Nuestros servicios"
      items:
        - title: "<span style='color:#FFFFFF'>Producción de videos educativos</span>"
          text: "<span style='color:#FFFFFF'>Creamos clases en video que convierten el contenido en experiencias de aprendizaje. Desde la ideación y el guion hasta la producción y la edición, integramos recursos audiovisuales en múltiples formatos para comunicar con claridad e impacto.</span>"
          image: "stickers-cumulo1-03.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "width:56%;max-width:56%;height:auto;"
          button:
            text: "Ver más"
            url: "/servicios/videos-educativos"
        - title: "<span style='color:#FFFFFF'>Ilustración científica y facilitación visual</span>"
          text: "<span style='color:#FFFFFF'>Desarrollamos recursos visuales que complementan materiales en proyectos de formación e investigación, para que cada imagen refuerce el contenido y mejore la experiencia de aprendizaje.<br>Trabajamos en distintos formatos: presentaciones para clases o eventos, pósters científicos, materiales de lectura, entre otros.</span>"
          image: "stickers-cumulo1-05.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "width:56%;max-width:56%;height:auto;"
          button:
            text: "Ver más"
            url: "/servicios/ilustracion-y-facilitacion-visual"
        - title: "<span style='color:#FFFFFF'>Acompañamiento y asesoramiento pedagógico</span>"
          text: "<span style='color:#FFFFFF'>Antes de producir contenidos, ofrecemos asesoramiento para diseñar la propuesta según el perfil de las y los estudiantes y los temas a desarrollar.<br>Nos involucramos desde el inicio en la ideación y en la selección de formatos, recursos y modalidades del contenido a producir.<br>Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto mantenga coherencia.</span>"
          image: "stickers-cumulo1-01.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "width:56%;max-width:56%;height:auto;"
          button:
            text: "Ver más"
            url: "/servicios/acompanamiento-pedagogico"
    design:
      background:
        color: "#3E6FBA"

  # 4) Métricas / Stats (SIN título)
  - block: stats
    id: metricas
    content:
      items:
        - statistic: "+170"
          description: "clases en formato video"
        - statistic: "+40"
          description: "docentes trabajaron con Cúmulo"
        - statistic: "10"
          description: "propuestas de formación acompañadas"
    design:
      spacing:
        padding: ["6px","0","2px","0"]

  # 4.5) Quiénes somos (centrado, mayor separación entre perfiles, fondo amarillo)
  - block: markdown
    id: quienes-somos
    content:
      title: "Quiénes somos"
      text: |
        <div style="max-width:1100px;margin:0 auto;">
          {{< people_list group="equipo" columns=4 gapx="8rem" gapy="3rem" >}}
        </div>
    design:
      background:
        color: "#FCF1B1"
      spacing:
        padding: ["36px","0","28px","0"]   # más margen sup/inf

  # 4.6) Colaboran (centrado, mayor separación, mismo fondo)
  - block: markdown
    id: colaboran
    content:
      title: "Colaboran"
      text: |
        <div style="max-width:1100px;margin:0 auto;">
          {{< people_list group="colaboran" columns=4 gapx="8rem" gapy="3rem" >}}
        </div>
    design:
      background:
        color: "#FCF1B1"
      spacing:
        padding: ["28px","0","36px","0"]   # un pelín más abajo

  # 5) Organizaciones (logos +10%)
  - block: markdown
    id: aliados
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        {{< logos_row_assets >}}
    design:
      spacing:
        padding: ["8px","0","10px","0"]

  # 6) Testimonios (centrado)
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
      align: center
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
        css_style: "background-color:#F4A26D;color:#3F393B;text-align:center; padding: 2.5rem; border-radius: 1rem;"

  # 8) CSS puntual (botones invertidos, refuerzo tamaños servicios, centrados)
  - block: markdown
    id: style-fixes
    content:
      text: |
        <style>
          /* Testimonios centrado total */
          #testimonios, #testimonios * { text-align: center !important; }

          /* Servicios destacados: tamaño refuerzo */
          #servicios-destacados img {
            width: 56% !important;
            max-width: 56% !important;
            height: auto !important;
            margin-left: auto !important;
            margin-right: auto !important;
            display: block !important;
          }
          @media (max-width: 640px) {
            #servicios-destacados img {
              width: 70% !important; max-width: 70% !important;
            }
          }

          /* Botones invertidos (blanco fondo / azul texto) en Servicios destacados */
          #servicios-destacados a.btn,
          #servicios-destacados a.btn-primary,
          #servicios-destacados .btn {
            background:#FFFFFF !important;
            color:#3E6FBA !important;
            border:2px solid #FFFFFF !important;
          }
          #servicios-destacados a.btn:hover,
          #servicios-destacados a.btn-primary:hover,
          #servicios-destacados .btn:hover {
            background:#EAF0FB !important;
            color:#2c5490 !important;
            border-color:#FFFFFF !important;
          }
        </style>
    design:
      spacing:
        padding: ["0","0","0","0"]
---
