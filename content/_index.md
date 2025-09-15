---
title: "Cúmulo"
type: landing

design:
  spacing: "3rem"

sections:
  # ======================
  # HERO corto (logo centrado + tagline)
  # ======================
  - block: hero
    content:
      title: ""
      text: |
        <img src="/media/cumulo.png" alt="Cúmulo" class="mx-auto mb-4 max-h-24" loading="eager">
        <p class="text-center text-lg md:text-xl font-semibold text-gray-900">
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
        padding: ["2rem", 0, "2rem", 0]   # hero más bajo/angosto
      css_style: "background-color:#FCF1B1;"
      # Texto oscuro sobre fondo claro (no activar text_color_light)

  # ======================
  # QUÉ HACEMOS (imagen + texto)
  # ======================
  - block: cta-image-paragraph
    id: que-hacemos
    content:
      items:
        - title: "Qué hacemos"
          text: |
            Diseñamos y producimos recursos para la enseñanza y el aprendizaje en diversos formatos y plataformas.  
            Trabajamos acompañando a docentes y organizaciones para fortalecer sus propuestas de formación, seleccionar los formatos más adecuados para cada contenido, estructurar guiones para clases y crear materiales visuales, audiovisuales y escritos que enriquezcan sus iniciativas y las acerquen a sus estudiantes.
          image: "cumuloilus-09.png"  # colocar el archivo en assets/media/cumuloilus-09.png
          button:
            text: "Escribinos"
            url: "mailto:somoscumulo@gmail.com"
    design:
      css_style: "color:#3F393B;"   # texto legible

  # ======================
  # LOGOS (banda oscura para alto contraste)
  # ======================
  - block: cta-card
    id: logos
    content:
      title: "Organizaciones que confían en Cúmulo"
      text: |
        <div class="grid grid-cols-2 sm:grid-cols-4 gap-6 items-center justify-items-center mt-4">
          <img src="/media/logo1.jpg" alt="Logo 1" class="max-h-12 opacity-95" loading="lazy">
          <img src="/media/logo2.jpg" alt="Logo 2" class="max-h-12 opacity-95" loading="lazy">
          <img src="/media/logo3.jpg" alt="Logo 3" class="max-h-12 opacity-95" loading="lazy">
          <img src="/media/logo4.jpg" alt="Logo 4" class="max-h-12 opacity-95" loading="lazy">
        </div>
    design:
      card:
        css_style: "background-color:#3F393B;color:#FCF1B1;"  # fondo oscuro, texto claro
      spacing:
        padding: ["2rem", "0", "2rem", "0"]

  # (Opcional) Portfolio si ya tenés proyectos en content/project/
  - block: collection
    id: portfolio
    content:
      title: "Trabajos"
      text: "Una selección de proyectos recientes."
      filters:
        folders: ["project"]
      count: 6
      sort_by: "date"
      view: "card"
    design:
      css_class: "bg-gray-50 dark:bg-gray-900"
---
