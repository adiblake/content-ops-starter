---
type: PageLayout
title: About Me
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Here's a little about me
      color: text-primary
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: >+
      I am a graphic designer turned mechanical engineer with over 5 years of
      design experience and a flourishing passion for product design. 

    actions: []
    colors: bg-neutral-fg-dark
    backgroundImage:
      type: BackgroundImage
      url: /images/KBAmy001836--000028.jpg
      altText: Placeholder image
      backgroundSize: cover
      backgroundPosition: center
      backgroundRepeat: no-repeat
      opacity: 100
    styles:
      self:
        padding:
          - pt-40
          - pl-4
          - pb-40
          - pr-4
        alignItems: center
        flexDirection: row-reverse
        justifyContent: center
      text:
        textAlign: center
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: ''
      color: text-dark
    subtitle: Here's a little about me...
    text: |
      I am a graphic designer turned mechanical engineer 
    actions: []
    media:
      type: ImageBlock
      url: /images/hero3.svg
      altText: Dope design preview
    badge:
      type: Badge
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row-reverse
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic Section With A Form
      color: text-dark
    subtitle: Section with a form subtitle
    text: |-
      Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae nisl.
      Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit amet
      erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at erat
      vitae interdum. Ut nec massa eget lorem blandit condimentum et at risus.
    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
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
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: about
seo:
  type: Seo
  metaTitle: Careers - Demo site
  metaDescription: This is the careers page built with Netlify.
  metaTags: []
---
