---
title: "Cúmulo"
type: landing

design:
  spacing: "3rem"

sections:
  # ======================
  # HERO (angosto, logo centrado, fondo #FCF1B1, texto oscuro)
  # ======================
  - block: hero
    content:
      title: ""  # dejamos vacío y componemos con HTML en 'text'
      text: |
        <img src="/media/cumulo.png" alt="Cúmulo"
             class="mx-auto h-20 md:h-24 mb-3" loading="eager">
        <p class="text-center text-lg md:text-xl font-semibold text-[#3F393B]">
          agencia y productora de contenidos educativos
        </p>
      primary_action:
        text: "Trabajemos en conjunto"
        url: "mailto:somoscumulo@gmail.com?subject=Quiero%20trabajar%20con%20C%C3%BAmulo"
      secondary_action:
        text: "Ver trabajos"
        url: "#portfolio"
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]  # más angosto
      css_style: "background-color:#FCF1B1;color:#3F393B;"
      text_color_light: false

  # ======================
  # QUÉ HACEMOS (imagen a la par + texto)
  # ======================
  - block: cta-image-paragraph
    id: que-hacemos
    content:
      items:
        - title: "Qué hacemos"
          text: |
            Diseñamos y producimos recursos para la enseñanza y el aprendizaje en diversos formatos y plataformas.
            Trabajamos acompañando a docentes y organizaciones para fortalecer sus propuestas de formación, seleccionar los formatos más adecuados para cada contenido, estructurar guiones para clases y crear materiales visuales, audiovisuales y escritos que enriquezcan sus iniciativas y las acerquen a sus estudiantes.
            Desde nuestra experiencia en comunicación, cine, artes visuales y diseño gráfico, ofrecemos un enfoque que integra diversas disciplinas para dar vida a proyectos educativos innovadores, creativos y accesibles.
          image: "cumuloilus-07.png"   # subir a assets/media/
          button:
            text: "Escribinos"
            url: "mailto:somoscumulo@gmail.com"
    design:
      css_style: "background-color:#FFFFFF;color:#3F393B;"

  # ======================
  # SERVICIOS (grid 3x)
  # ======================
  - block: features
    id: servicios
    content:
      title: "Servicios"
      text: "Soluciones integrales para formación, guionado, producción audiovisual y diseño."
      items:
        - name: "Diseño de propuestas de formación"
          icon: "sparkles"
          icon_pack: "hero"
          description: "Asesoría y acompañamiento para planificar formaciones efectivas y medibles."
        - name: "Guiones para clases en video"
          icon: "document-text"
          icon_pack: "hero"
          description: "Estructura, storyboard y narrativa pensada para captar y mantener la atención."
        - name: "Videos educativos"
          icon: "video-camera"
          icon_pack: "hero"
          description: "Producción integral: pre, rodaje y post con foco pedagógico."
        - name: "Videos institucionales"
          icon: "building-office"
          icon_pack: "hero"
          description: "Piezas claras, inspiradoras y alineadas a tu identidad."
        - name: "Corrección y diseño editorial"
          icon: "pencil-square"
          icon_pack: "hero"
          description: "Textos, fichas y materiales de lectura con tono y diseño consistentes."
        - name: "Ilustración y comunicación visual"
          icon: "paint-brush"
          icon_pack: "hero"
          description: "Gráficas y recursos visuales que explican ideas complejas."
        - name: "Presentaciones efectivas"
          icon: "presentation-chart-bar"
          icon_pack: "hero"
          description: "Asesoría, guionado y armado para presentaciones memorables."
        - name: "Murales institucionales"
          icon: "rectangle-group"
          icon_pack: "hero"
          description: "Diseño y realización de murales para espacios educativos y culturales."
    design:
      columns: 3

  # ======================
  # TRABAJOS (colección automática desde content/project/)
  # ======================
  - block: collection
    id: portfolio
    content:
      title: "Trabajos realizados"
      text: "Una selección de proyectos recientes."
      filters:
        folders:
          - "project"   # crea tus proyectos en content/project/<proyecto>/_index.md
      count: 6
      sort_by: "date"
      view: "card"
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"

  # ======================
  # LOGOS (fondo oscuro para asegurar contraste)
  # ======================
  - block: cta-card
    id: logos
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-6 items-center justify-items-center">
          <img src="/media/logos/cumulo/logo1.png" alt="Logo 1" class="max-h-12 opacity-90" loading="lazy">
          <img src="/media/logos/cumulo/logo2.png" alt="Logo 2" class="max-h-12 opacity-90" loading="lazy">
          <img src="/media/logos/cumulo/logo3.png" alt="Logo 3" class="max-h-12 opacity-90" loading="lazy">
          <img src="/media/logos/cumulo/logo4.png" alt="Logo 4" class="max-h-12 opacity-90" loading="lazy">
          <img src="/media/logos/cumulo/logo5.png" alt="Logo 5" class="max-h-12 opacity-90" loading="lazy">
        </div>
    design:
      card:
        css_style: "background-color:#3F393B;color:#FCF1B1;"  # ← fondo oscuro + texto claro

  # ======================
  # CTA FINAL (azul marca + redes)
  # ======================
  - block: cta-card
    id: contacto
    content:
      title: "¿Trabajamos en conjunto?"
      text: |
        Escribinos a **somoscumulo@gmail.com**  
        Seguinos en redes: **@somoscumulo**
      button:
        text: "Contactar por email"
        url: "mailto:somoscumulo@gmail.com?subject=Contacto%20desde%20la%20web"
    design:
      card:
        css_style: "background-color:#3E6FBA;color:#FFFFFF;"
---
