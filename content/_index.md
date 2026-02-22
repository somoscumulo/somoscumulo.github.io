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
          button:
            text: "Conversemos"
            url: "/#cta-final"
    design:
      background:
        color: "#FCF1B1"

  # 2) Video destacado
  - block: markdown
    id: video-destacado
    content:
      text: |
        <div style="max-width:1100px;margin:0 auto;padding:3rem 1rem;text-align:center;">
          <h2 style="color:#FFFFFF;">Producción de videos educativos</h2>
          <p style="color:#FFFFFF;max-width:800px;margin:0 auto 2rem auto;">
            Creamos clases en video que convierten el contenido en experiencias de aprendizaje.
            Desde la idea y el guion hasta la producción y la edición, integramos recursos audiovisuales
            en múltiples formatos para comunicar con claridad e impacto.
          </p>

          <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:1rem;">
            <iframe 
              src="https://www.youtube.com/embed/-P2pp6QCjX8" 
              title="Producción de videos educativos - Cúmulo"
              frameborder="0"
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
              allowfullscreen
              style="position:absolute;top:0;left:0;width:100%;height:100%;">
            </iframe>
          </div>

          <div style="margin-top:2rem;">
            <a href="/videos" 
               style="background:#FFFFFF;color:#3E6FBA;padding:.7rem 1.6rem;border-radius:.6rem;text-decoration:none;font-weight:600;">
              Ver más
            </a>
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
          text: "<span style='color:#FFFFFF'>Desarrollamos recursos visuales que complementan materiales en proyectos de formación e investigación...</span>"
          image: "stickers-cumulo1-05.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "width:56%;max-width:56%;height:auto;"
        - title: "<span style='color:#FFFFFF'>Acompañamiento y asesoramiento pedagógico</span>"
          text: "<span style='color:#FFFFFF'>Antes de producir contenidos, ofrecemos asesoramiento para diseñar la propuesta...</span>"
          image: "stickers-cumulo1-01.png"
          image_alt: "Ilustración Cúmulo"
          image_style: "width:56%;max-width:56%;height:auto;"
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

        /* === FIX MODO OSCURO === */
        @media (prefers-color-scheme: dark) {

          /* Forzar texto oscuro en banner */
          #aviso-wip .wip-inner,
          #aviso-wip .wip-inner strong {
            color:#3F393B !important;
          }

          /* Forzar texto oscuro en hero amarillo */
          #solutions h1,
          #solutions h2,
          #solutions h3,
          #solutions p,
          #solutions strong,
          #solutions span {
            color:#3F393B !important;
          }

        }

        </style>
    design:
      spacing:
        padding: ["0","0","0","0"]

---
