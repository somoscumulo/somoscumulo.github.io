---
title: "Cúmulo"
type: landing

image:
  filename: images/og-cumulo.jpg
  alt_text: "Cúmulo — Agencia y productora de contenidos educativos"

sections:

  # 0) Aviso WIP — cartel minimalista arriba de todo
  - block: markdown
    id: aviso-wip
    content:
      text: |
        <div style="max-width:1100px;margin:0 auto;">
          <div style="background:#FFFCEE;border:1px solid #F1E6B8;color:#3F393B;border-radius:10px;padding:.65rem 1rem;text-align:center;font-size:.95rem;">
            <strong>Página web en proceso de producción</strong> — versión work in progress
          </div>
        </div>
    design:
      spacing:
        padding: ["10px","0","6px","0"]

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
          text: "<span style='color:#FFFFFF'>Creamos clases en video que convierten el contenido en experiencias de aprendizaje. Desde la idea y el guion hasta la producción y la edición, integramos recursos audiovisuales en múltiples formatos para comunicar con claridad e impacto.</span>"
          image: "stickers-cumulo1-03.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "width:56%;max-width:56%;height:auto;"
          button:
            text: "Ver más"
            url: "/videos"
        - title: "<span style='color:#FFFFFF'>Facilitación visual e ilustración para divulgación y formación</span>"
          text: "<span style='color:#FFFFFF'>Desarrollamos recursos visuales que complementan materiales en proyectos de formación e investigación, para que cada imagen refuerce el contenido y mejore la experiencia de aprendizaje.<br>Trabajamos en distintos formatos: presentaciones para clases o eventos, pósters científicos, materiales de lectura, entre otros.</span>"
          image: "stickers-cumulo1-05.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "width:56%;max-width:56%;height:auto;"
        - title: "<span style='color:#FFFFFF'>Acompañamiento y asesoramiento pedagógico</span>"
          text: "<span style='color:#FFFFFF'>Antes de producir contenidos, ofrecemos asesoramiento para diseñar la propuesta según el perfil de las y los estudiantes y los temas a desarrollar.<br>Nos involucramos desde el inicio en la selección de formatos, recursos y modalidades del contenido a producir.<br>Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto mantenga coherencia.</span>"
          image: "stickers-cumulo1-01.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "width:56%;max-width:56%;height:auto;"
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

  # 4.5) Quiénes somos — responsive 2 columnas en mobile
  - block: markdown
    id: quienes-somos
    content:
      title: "Quiénes somos"
      text: |
        <div class="people-wrap">
          {{< people_list group="equipo" columns=2 gapx="6rem" gapy="2.5rem" >}}
        </div>
    design:
      background:
        color: "#FCF1B1"
      spacing:
        padding: ["28px","0","22px","0"]

  # 4.6) Colaboran — UNA SOLA FILA EN DESKTOP (2 columnas en mobile)
  - block: markdown
    id: colaboran
    content:
      title: "Colaboran"
      text: |
        <div class="people-wrap people-wrap--colaboran">
          {{< people_list group="colaboran" columns=5 gapx="6rem" gapy="2.5rem" >}}
        </div>
    design:
      background:
        color: "#FCF1B1"
      spacing:
        padding: ["22px","0","30px","0"]

  # 5) Organizaciones (usa people_list con user_group "confian" + fondo amarillo)
  - block: markdown
    id: confian
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        <div class="people-wrap">
          {{< people_list group="confian" columns=4 gapx="6rem" gapy="2.5rem" >}}
        </div>
    design:
      background:
        color: "#FCF1B1"
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

  # 7) CTA final — cta-card (mailto)
  - block: cta-card
    id: cta-final
    content:
      title: "¿Arrancamos?"
      text: |
        Contanos tu idea y te ayudamos a convertirla en un recorrido claro para tus estudiantes.
      button:
        text: "Conversemos"
        url: "mailto:somoscumulo@gmail.com"
    design:
      card:
        css_class: "shadow-sm"
        css_style: "background-color:#F4A26D;color:#3F393B;text-align:center; padding: 2.5rem; border-radius: 1rem;"

  # 8) CSS puntual (people_list responsive + UNA FILA en Colaboran + estilos)
  - block: markdown
    id: style-fixes
    content:
      text: |
        <style>
          /* Contenedor centrado para people_list */
          .people-wrap {
            max-width: 1100px;
            margin-left: auto;
            margin-right: auto;
          }

          /* Layout base: dos por fila en mobile */
          .people-wrap .people-grid {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 2.5rem 6rem; /* gapy/gapx */
            justify-items: center;
            align-items: start;
          }

          /* Desktop general (equipo/confían): 4 por fila */
          @media (min-width: 1024px) {
            #quienes-somos .people-wrap .people-grid,
            #confian .people-wrap .people-grid {
              grid-template-columns: repeat(4, minmax(0, 1fr));
              gap: 3rem 8rem;
            }
          }

          /* === UNA SOLA FILA EN DESKTOP para Colaboran === */
          @media (min-width: 1024px) {
            #colaboran .people-wrap--colaboran .people-grid {
              grid-template-columns: none !important;
              grid-auto-flow: column;
              grid-auto-columns: max-content;
              justify-content: center;
              column-gap: 6rem; /* separación horizontal */
              row-gap: 0;
            }
            /* Avatares un poco más chicos para que entren todos si son muchos */
            #colaboran .people-wrap--colaboran .avatar,
            #colaboran .people-wrap--colaboran .avatar img {
              width: 8.5rem;
              height: 8.5rem;
            }
          }

          /* Avatares centrados y recortados */
          .people-wrap .avatar,
          .people-wrap .avatar img {
            border-radius: 9999px;
            object-fit: cover;
            object-position: center;
            width: 10rem;
            height: 10rem;
            display: block;
          }

          /* Tipografía compacta en nombres y rol */
          .people-wrap .name {
            line-height: 1.2;
            margin-top: .4rem;
            font-weight: 600;
            text-decoration: none !important;
          }
          .people-wrap .role {
            margin-top: .1rem;
            font-size: .9rem;
            opacity: .8;
          }

          /* Testimonios centrados */
          #testimonios, #testimonios * { text-align: center !important; }

          /* Servicios destacados: tamaño refuerzo y botones invertidos */
          #servicios-destacados img {
            width: 56% !important;
            max-width: 56% !important;
            height: auto !important;
            margin-left: auto !important;
            margin-right: auto !important;
            display: block !important;
          }
          @media (max-width: 640px) {
            #servicios-destacados img { width: 70% !important; max-width: 70% !important; }
          }
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
