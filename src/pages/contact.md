---
title: Contacto
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: Escríbeme. ¡Prometo responderte en cuanto pueda!
    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        default_value: Tu nombre
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Tu dirección de email
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Elige uno
        options:
          - Quiero que colaboremos en un proyecto
          - Tengo alguna duda que quizás puedas resolverme
          - Me gustaría charlar contigo
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Tu mensaje
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario enviará mi información personal de cara a
          ser contactado
    submit_label: Enviar Mensaje
template: advanced
---
