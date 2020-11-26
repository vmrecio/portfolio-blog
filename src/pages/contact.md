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
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Asunto
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Mensaje
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          Entiendo que este formulario enviará mi información personal de cara a
          ser contactado
    submit_label: Send Message
template: advanced
---
