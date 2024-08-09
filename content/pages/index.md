---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'Hey, I''m Adi!'
      color: text-dark
      type: TitleBlock
    subtitle: Welcome to my portfolio.
    text: >
      I am a graphic designer turned mechanical engineer with over 5 years of
      design experience and a flourishing passion for product design. 
    actions:
      - label: See my work
        altText: ''
        url: /portfolio
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/adi image.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: ''
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-48
          - pb-16
          - pr-40
  - title:
      text: Want to get in touch?
      color: text-dark
      type: TitleBlock
    subtitle: Flick me a message
    text: ''
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: 'Adi Blake Bhattacharya - Designer, Engineer'
  metaDescription: ''
  socialImage: /images/AB LOGO 2024.png
  type: Seo
type: PageLayout
---
