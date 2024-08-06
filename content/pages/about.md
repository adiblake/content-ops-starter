---
type: PageLayout
title: About Me
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Here's a little about me
      color: text-light
      styles:
        self:
          textAlign: center
    subtitle: ''
    text: ''
    actions: []
    colors: bg-dark-fg-light
    backgroundImage:
      type: BackgroundImage
      url: /images/PXL_20221221_202609418.jpg
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
    subtitle: My Story
    text: >
      I've always been interested in how design can help people live better
      lives. 


      Working as a graphic designer for half a decade and now as a mechanical
      engineer in medical device product development, I've had the privilege of
      applying my design skills to address real-world problems.
    actions: []
    media:
      type: ImageBlock
      url: /images/KBAmy001836--000028.jpg
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
  - type: GenericSection
    title:
      type: TitleBlock
      text: ''
      color: text-dark
    subtitle: My Story
    text: >+
      I was just 10 years old when I had the chance to use a device that would
      change my life for years to come. It was having an insulin pump - a pocket
      sized device that allowed me to dose a continuous flow of insulin - that
      fundamentally changed the way I could eat, sleep and live life as a kid
      with type-1 diabetes.

    actions: []
    media:
      type: ImageBlock
      url: /images/KBAmy001836--000028.jpg
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
      text: Social Media Management
      color: text-dark
    subtitle: Increase your reach
    text: >
      A service that helps businesses to manage their social media accounts and
      posts.
    actions:
      - type: Link
        label: See Tutorials
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
    media:
      type: ImageBlock
      url: /images/hero2.svg
      altText: Fun feature preview
    badge:
      type: Badge
      label: This is a badge
      color: text-primary
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
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
