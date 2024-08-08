---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/brick.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-c
    backgroundSize: inset
    title: >-
      Welcome to the Super Special Davis Ross-Boss Bachelor Weekend Fun
      Website!!1!
    subtitle: 'prepare thine self, fair maidens'
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-16
          - pb-16
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
  - type: MediaGallerySection
    title: Gallery
    subtitle: This is the subtitle
    images:
      - type: ImageBlock
        url: /images/nosebleed.PNG
        altText: Image one
        caption: Image one caption
        elementId: ''
      - type: ImageBlock
        url: /images/sick-shades.PNG
        altText: Image two
        caption: Image two caption
        elementId: ''
    colors: colors-f
    spacing: 16
    columns: 2
    aspectRatio: '4:3'
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-12
          - pb-12
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: QuoteSection
    quote: >
      “**People get built different. We don't need to figure it out, we just
      need to respect it.**”
    name: '-PB'
    title: '- - Davis'
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        justifyContent: center
      quote:
        textAlign: left
      name:
        fontWeight": 500
        textAlign: left
      title:
        fontWeight": 400
        textAlign: left
---
