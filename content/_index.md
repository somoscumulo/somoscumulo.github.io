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
      title: ""
      text: |
        <div class="text-center">
          <img src="/media/cumulo.png" alt="Cúmulo" class="mx-auto h-20 md:h-24 mb-3" loading="eager">
          <p class="text-lg md:text-xl font-semibold" style="color:#3F393B;">
            agencia y productora de contenidos educativos
          </p>
        </div>
      primary_action:
        text: "Trabajemos en conjunto"
        url: "mailto:somoscumulo@gmail.com?subject=Quiero%20trabajar%20con%20C%C3%BAmulo"
      secondary_action:
        text: "Ver trabajos"
        url: "#que-hacemos"
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]
      background:
        color: "#FCF1B1"
      text_color_light: false

  # ======================
  # QUÉ HACEMOS (reemplazo seguro del cta-image-paragraph)
  # ======================
  - block: cta-card
    id: que-hacemos
    content:
      title: "Qué hacemos"
      text: |
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
          <div>
            <p>Diseñamos y producimos recursos para la enseñanza y el aprendizaje en diversos formatos y plataformas.</p>
            <p class="mt-3">Trabajamos acompañando a docentes y organizaciones para fortalecer sus propuestas de formación, seleccionar los formatos más adecuados para cada contenido, estructurar guiones para clases y crear materiales visuales, audiovisuales y escritos que enriquezcan sus iniciativas y las acerquen a sus estudiantes.</p>
            <p class="mt-3">Desde nuestra experiencia en comunicación, cine, artes visuales y diseño gráfico, ofrecemos un enfoque que integra diversas disciplinas para dar vida a proyectos educativos innovadores, creativos y accesibles.</p>
            <a class="btn btn-primary mt-4 inline-block" href="mailto:somoscumulo@gmail.com">Escribinos</a>
          </div>
          <div class="flex justify-center md:justify-end">
            <img src="/media/logo1.jpg" alt="Cúmulo" class="max-h-64 w-auto rounded-lg shadow-sm" loading="lazy">
          </div>
        </div>
    design:
      card:
        css_class: "bg-white text-[#3F393B]"

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
          text: "Asesoría y acompañamiento para planificar formaciones efectivas y medibles."
        - name: "Guiones para clases en video"
          icon: "document-text"
          icon_pack: "hero"
          text: "Estructura, storyboard y narrativa pensada para captar y mantener la atención."
        - name: "Videos educativos"
          icon: "video-camera"
          icon_pack: "hero"
          text: "Producción integral: pre, rodaje y post con foco pedagógico."
        - name: "Videos institucionales"
          icon: "building-office"
          icon_pack: "hero"
          text: "Piezas claras, inspiradoras y alineadas a tu identidad."
        - name: "Corrección y diseño editorial"
          icon: "pencil-square"
          icon_pack: "hero"
          text: "Textos, fichas y materiales de lectura con tono y diseño consistentes."
        - name: "Ilustración y comunicación visual"
          icon: "paint-brush"
          icon_pack: "hero"
          text: "Gráficas y recursos visuales que explican ideas complejas."
        - name: "Presentaciones efectivas"
          icon: "presentation-chart-bar"
          icon_pack: "hero"
          text: "Asesoría, guionado y armado para presentaciones memorables."
        - name: "Murales institucionales"
          icon: "rectangle-group"
          icon_pack: "hero"
          text: "Diseño y realización de murales para espacios educativos y culturales."
    design:
      columns: 3

  # ======================
  # LOGOS (fondo oscuro para contraste) — usa logo1–logo4.jpg
  # ======================
  - block: cta-card
    id: logos
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        <div class="grid grid-cols-2 sm:grid-cols-4 gap-6 items-center justify-items-center">
          <img src="/media/logo1.jpg" alt="Logo 1" class="max-h-12 opacity-90" loading="lazy">
          <img src="/media/logo2.jpg" alt="Logo 2" class="max-h-12 opacity-90" loading="lazy">
          <img src="/media/logo3.jpg" alt="Logo 3" class="max-h-12 opacity-90" loading="lazy">
          <img src="/media/logo4.jpg" alt="Logo 4" class="max-h-12 opacity-90" loading="lazy">
        </div>
    design:
      card:
        css_class: "bg-gray-900 text-gray-100"

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
        css_class: "bg-blue-700 text-white"
---
