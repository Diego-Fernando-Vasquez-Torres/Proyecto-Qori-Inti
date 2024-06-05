---
title: 'Inmobiliaria Qori Inti'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: La mejor manera de vivir tu sueño
      text: Somos una inmobiliaria en la ciudad de Juliaca y ofrecemos lotes a precios asequibles para toda la población.
      primary_action:
        text: Contactate con un asesor
        url: https://hugoblox.com/templates/
        icon: rocket-launch
      secondary_action:
        text: Lee nuestras reseñas
        url: https://docs.hugoblox.com
      announcement:
        text: "Da el primer paso, nosotros te ayudamos a encontrar tu lote"
        link:
          text: "Ver más"
          url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: banner.jpg
          filters:
            brightness: 0.5
  - block: stats
    content:
      items:
        - statistic: "100+"
          description: |
            Lotes vendidos    
            En toda la regióm
        - statistic: "100+"
          description: |
            stats  
            stats
        - statistic: "100+"
          description: |
            stats   
            stats   
            stats
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: ["1rem", 0, "1rem", 0]
  - block: features
    id: features
    content:
      title: "Qori Inti: Grupo Inmobiliario & Constructor"
      text: Conoce mas sobre nosotros, nuestro compromiso con el cliente.
      items:
        - name: Nuestro servicio
          icon: magnifying-glass
          description: Qori Inti aspira a expandir 
                      su alcance más allá de la venta de lotes. Nuestro objetivo es desarrollar 
                      proyectos inmobiliarios completos, desde la adquisición de terrenos 
                      hasta la construcción de urbanizaciones, reflejando nuestra misión y 
                      visión de innovación y excelencia.
                      
        - name: Misión
          icon: bolt
          description: "'' En Qori Inti, nos dedicamos a transformar el mercado inmobiliario del sur 
                      del Perú. Nos esforzamos por la transparencia, la innovación y un 
                      compromiso incansable con mejorar la calidad de vida de nuestros clientes. 
                      Nuestra misión es ofrecer un servicio de calidad excepcional, asegurando 
                      que cada interacción con nuestros clientes aporte valor y satisfacción.''"
        - name: Visión
          icon: sparkles
          description: "''Aspiramos a convertirnos en líderes del mercado inmobiliario del altiplano 
                        peruano, diferenciándonos por nuestra capacidad innovadora, la calidad 
                        superior de nuestros proyectos y un servicio al cliente insuperable. Nos 
                        enfocamos en ser guías confiables para nuestros clientes, ayudándoles a 
                        encontrar su espacio ideal y contribuyendo significativamente a su 
                        bienestar y satisfacción.''"
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: Empieza a ver nuestros lotes disponibles
          text: Es hora de dar el primer paso, no te arrepentirás!
          feature_icon: check
          features:
            - "Lotes desde 35,000 nuevos soles"
            - "Ubicados en áreas estratégicas"
            - "Dimensiones acordes para ti y tu familia"
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
          button:
            text: Conocer Lotes
            url: https://hugoblox.com/templates/
        - title: Large Community
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          features:
            - "Dedicated support channel"
            - "3,000+ users on Discord"
            - "Share your site and get feedback"
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Join Discord
            url: https://discord.gg/z8wNYzb
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Ana Vargas"
          role: "Madre de familia..."
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Una experiencia grata, excelente atención durante el proceso de compra, no dudo que fue un paso hacia adelante para mi familia y yo"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
  - block: cta-card
    content:
      title: Build your future-proof website
      text: As easy as 1, 2, 3!
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
