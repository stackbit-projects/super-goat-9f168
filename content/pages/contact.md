---
title: Conectar
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: |
      ¡Hey!

      Si tienes alguna duda o idea en la que podamos colaborar. 



      ¡Envíame un mensaje y hablemos!
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: Tu nombre
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu correo electrónico
        is_required: true
      - input_type: select
        name: subject
        options:
          - Saludo
          - Colaboración / Oferta laboral
          - Otro
        label: Asunto
      - input_type: textarea
        name: Mensaje
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario está almacenando mi información para que
          pueda ser contactado/a.
    submit_label: Enviar mensaje
seo:
  title: Contact
  description: This is the contact page
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: This is the contact page
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: This is the contact page
layout: advanced
---
