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
    subtitle: My story
    text: >
      I've always been interested in how design can help people live better
      lives. 


      Working as a graphic designer for half a decade and now as a mechanical
      engineer in medical device product development, I've had the privilege of
      applying my design skills to address real-world problems.
    actions: []
    media:
      type: ImageBlock
      url: /images/PXL_20221221_21351180ddw9 (2).jpg
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        margin:
          - mb-0
          - mt-0
          - ml-0
          - mr-0
        justifyContent: center
        flexDirection: '-reverse'
  - type: GenericSection
    subtitle: How it all started
    text: >
      I was just 10 years old when I had the chance to use a device that would
      change my life for years to come. It was having an insulin pump - a pocket
      sized device that allowed me to dose a continuous flow of insulin - that
      fundamentally changed the way I could eat, sleep and live life as a kid
      with type-1 diabetes. This taught me how a well designed device could
      improve my life in every way.
    actions: []
    media:
      type: ImageBlock
      url: /images/421421321321321.jpg
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        margin:
          - mb-0
          - mt-0
          - ml-0
          - mr-0
        justifyContent: center
        flexDirection: '-reverse'
        padding:
          - pt-0
          - pl-0
          - pb-0
          - pr-0
  - type: GenericSection
    subtitle: Pivoting industries
    text: >
      Working as a graphic designer for several years, I happened onto a TED
      Talk given by the engineer who designed the first insulin pump prototype,
      and knew the next step in my career was to pursue mechanical engineering.


      My award winning final year project in mechanical engineering involved
      designing custom variable density shoe insoles for patients suffering from
      diabetic neuropathy, by harnessing the 3D printing of soft materials into
      field-driven lattice structures.
    actions: []
    media:
      type: ImageBlock
      url: /images/PXL_20230503_012713105~2-01.jpeg
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        margin:
          - mb-0
          - mt-0
          - ml-0
          - mr-0
        justifyContent: center
        flexDirection: '-reverse'
  - type: GenericSection
    subtitle: Honing in on my passion
    text: >+
      My passion for product design and healthcare has led me to work in
      research and development in medical devices, whilst continuing my
      volunteer work at Diabetes New Zealand. It is through design innovation
      that I hope I can make a positive difference in the lives of others.

    actions: []
    media:
      type: ImageBlock
      url: /images/IMG_2022050csacxz5_183545.jpg
      altText: Fun feature preview
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        margin:
          - mb-0
          - mt-0
          - ml-0
          - mr-0
        justifyContent: center
        flexDirection: '-reverse'
  - type: GenericSection
    title:
      type: TitleBlock
      text: Want to get in touch?
      color: text-dark
    subtitle: Flick me a message
    text: ''
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
      label: ''
      color: text-primary
    colors: bg-light-fg-dark
slug: about
seo:
  type: Seo
  metaTitle: About Me
  metaDescription: Here's a little about me
  metaTags: []
  addTitleSuffix: true
---
