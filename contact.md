---
title: Contact
hide_title: false
sections:
  - type: form_section
    section_id: contact-form
    content: >-
      Let’s build something great together.<br>

      Complete our contact form or send us an email at
      [paoleno21@gmail.com](mailto:paoleno21@gmail.com).


      ***

      ## Where we are

      Weybridge, Surrey, Kt15 2ss<br>

      ## Phone

      [+44 7402052652]()<br>

      ## Our social contact
    form_id: contactForm
#[Get directions &rarr;](https://goo.gl/maps/eh6fn7JjMS4vYs337) to put 
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: What services are you looking for?
        default_value: Please select
        options:
          - Drywall feature works
          - Painting and decorating
          - Bespoke Internal Design
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Your message
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
    submit_label: Send Message
seo:
  title: Contact
  description: Let's Connect with Remida Property Solutions
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contact
      keyName: property
    - name: 'og:description'
      value: Let's Connect with Remida Property Solutions
      keyName: property
    - name: 'twitter:card'
      value: summary
    - name: 'twitter:title'
      value: Contact
    - name: 'twitter:description'
      value: Let's Connect with Remida Property Solutions
layout: advanced
---
