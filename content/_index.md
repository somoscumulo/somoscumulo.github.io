---
title: "Cúmulo"
type: landing

image:
  filename: images/og-cumulo.jpg
  alt_text: "Cúmulo — Agencia y productora de contenidos educativos"

sections:

  # 0) Aviso WIP
  - block: markdown
    id: aviso-wip
    content:
      text: |
        <div class="wip-banner">
          <div class="wip-inner">
            <strong>Página web en proceso de producción</strong> — versión work in progress
          </div>
        </div>
    design:
      spacing:
        padding: ["10px","0","6px","0"]

  # 1) Hero institucional
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: "Agencia y productora de contenidos para la educación y la ciencia"
          text: "Diseñamos y producimos recursos para la <strong>enseñanza y el aprendizaje</strong> en diversos formatos y plataformas. Acompañamos a <strong>docentes y organizaciones</strong> para fortalecer sus propuestas, elegir el formato adecuado para cada contenido, <strong>estructurar guiones</strong> de clases y crear materiales <strong>visuales, audiovisuales y escritos</strong> que acerquen sus iniciativas a las y los estudiantes."
          image: "cumulo.png"
          image_alt: "Logotipo Cúmulo"
          image_style: "max-width:42%"
    design:
      background:
        color: "#FCF1B1"

  # 2) Video destacado
  - block: markdown
    id: video-destacado
    content:
      text: |
        <div class="video-destacado-wrap">
          <h2 class="video-destacado-title">Producción de videos educativos</h2>
          <p class="video-destacado-text">
            Creamos clases en video que convierten el contenido en experiencias de aprendizaje.
            Desde la idea y el guion hasta la producción y la edición.
            Según el contenido a enseñar y las condiciones de producción, elegimos entre múltiples formatos
            para comunicar con claridad e impacto: entrevistas, presentaciones animadas, clases con avatares
            de inteligencia artificial, entre otros.
          </p>

          <div class="video-embed">
            <iframe
              src="https://www.youtube.com/embed/RqBUfsU4av4"
              title="Producción de videos educativos - Cúmulo"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
              allowfullscreen>
            </iframe>
          </div>
        </div>
    design:
      background:
        color: "#3E6FBA"

  # 3) Servicios
  - block: cta-image-paragraph
    id: servicios-destacados
    content:
      title: "Nuestros servicios"
      items:
        - title: "<span style='color:#FFFFFF'>Facilitación visual e ilustración para divulgación y formación</span>"
          text: "<span style='color:#FFFFFF'>Desarrollamos recursos visuales que complementan materiales en proyectos de formación e investigación, para que cada imagen refuerce el contenido y mejore la experiencia de aprendizaje.<br>Trabajamos en distintos formatos: presentaciones para clases o eventos, pósters científicos, materiales de lectura, entre otros.</span>"
          image: "stickers-cumulo1-05.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "height:auto;"
        - title: "<span style='color:#FFFFFF'>Acompañamiento y asesoramiento pedagógico</span>"
          text: "<span style='color:#FFFFFF'>Antes de producir contenidos, ofrecemos asesoramiento para diseñar la propuesta según el perfil de las y los estudiantes y los temas a desarrollar.<br>Nos involucramos desde el inicio en la selección de formatos, recursos y modalidades del contenido a producir.<br>Co-diseñamos rutas claras para que cada pieza cumpla un rol y el conjunto mantenga coherencia.</span>"
          image: "stickers-cumulo1-01.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "height:auto;"
    design:
      background:
        color: "#3E6FBA"

  # 4) Métricas
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

  # 6) Testimonios
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

  # CTA final
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
        css_style: "background-color:#F4A26D;color:#3F393B;text-align:center;padding:2.5rem;border-radius:1rem;"

  # Estilos
  - block: markdown
    id: style-fixes
    content:
      text: |
        <style>

        /* WIP */
        .wip-banner {
          max-width:1100px;
          margin:0 auto;
        }
        .wip-inner {
          background:#FFFCEE;
          border:1px solid #F1E6B8;
          color:#3F393B;
          border-radius:10px;
          padding:.65rem 1rem;
          text-align:center;
          font-size:.95rem;
        }

        /* FIX modo oscuro */
        @media (prefers-color-scheme: dark) {
          #aviso-wip .wip-inner,
          #aviso-wip .wip-inner strong {
            color:#3F393B !important;
          }
          #solutions h1,
          #solutions h2,
          #solutions h3,
          #solutions p,
          #solutions strong,
          #solutions span {
            color:#3F393B !important;
          }
        }

        /* ===== VIDEO DESTACADO ===== */
        .video-destacado-wrap{
          max-width:1100px;
          margin:0 auto;
          padding:3.5rem 1rem;
          text-align:center;
        }
        .video-destacado-title{
          color:#FFFFFF;
          font-size:2rem;
          font-weight:700;
          margin-bottom:1.2rem;
        }
        .video-destacado-text{
          color:#FFFFFF;
          max-width:820px;
          margin:0 auto 2.5rem auto;
          font-size:1.05rem;
        }
        .video-embed{
          position:relative;
          padding-bottom:56.25%;
          height:0;
          overflow:hidden;
          border-radius:1rem;
        }
        .video-embed iframe{
          position:absolute;
          top:0; left:0;
          width:100%;
          height:100%;
        }

        /* ===== PEOPLE LIST: centrado + responsive + colaboran en una fila ===== */
        .people-wrap {
          max-width: 1100px;
          margin-left: auto;
          margin-right: auto;
        }

        /* Base: 2 columnas mobile */
        .people-wrap .people-grid {
          display: grid;
          grid-template-columns: repeat(2, minmax(0, 1fr));
          gap: 2.5rem 6rem;
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

        /* Colaboran: una sola fila en desktop */
        @media (min-width: 1024px) {
          #colaboran .people-wrap--colaboran :is(.people-grid, ul, .hb-people, .people-list) {
            display: flex !important;
            flex-wrap: nowrap !important;
            justify-content: center !important;
            align-items: center !important;
            gap: 0 6rem;
            max-width: 1100px;
            margin: 0 auto;
            list-style: none;
          }

          #colaboran .people-wrap--colaboran :is(.people-grid, ul, .hb-people, .people-list) > * {
            flex: 0 0 11.5rem;
            width: 11.5rem;
            text-align: center;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: .4rem;
          }

          #colaboran .people-wrap--colaboran .avatar {
            width: 8.5rem;
            height: 8.5rem;
          }
        }

        /* Avatares: círculo y mostrar imagen completa */
        .people-wrap .avatar {
          border-radius: 9999px;
          width: 10rem;
          height: 10rem;
          overflow: hidden;
          display: flex;
          align-items: center;
          justify-content: center;
          margin: 0 auto;
          background: #fff;
        }
        .people-wrap .avatar img {
          display: block;
          width: 100%;
          height: 100%;
          object-fit: contain;
          object-position: center;
        }

        .people-wrap .name {
          line-height: 1.2;
          margin-top: .4rem;
          font-weight: 600;
          text-decoration: none !important;
          text-align: center;
        }
        .people-wrap .role {
          margin-top: .1rem;
          font-size: .9rem;
          opacity: .8;
          text-align: center;
        }

        /* ===== SERVICIOS - IMÁGENES +30% ===== */
        #servicios-destacados img {
          width: 62% !important;
          max-width: 62% !important;
          height: auto !important;
          margin: 0 auto !important;
          display: block !important;
        }
        @media (max-width: 640px) {
          #servicios-destacados img {
            width: 78% !important;
            max-width: 78% !important;
          }
        }

        /* Testimonios centrados */
        #testimonios, #testimonios * { text-align: center !important; }

        </style>
    design:
      spacing:
        padding: ["0","0","0","0"]

---
