---
type: PageLayout
title: Landing
sections:
  - type: HeroSection
    title: >-
      I'm a developer, digital artist, consultant and a bunch of other
      impressive titles and buzz words.
    subtitle: I am a front-end focused full stack developer.
    text: >
      To learn more about me as a developer from a code stand point take a look
      at some of my projects down below.
    actions: []
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
  - type: FeaturedProjectsSection
    title: ''
    subtitle: Recent projects
    actions:
      - type: Link
        label: See all projects
        altText: ''
        url: /projects
        showIcon: false
        icon: arrowRight
        iconPosition: right
        elementId: ''
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    colors: colors-f
    variant: variant-b
    elementId: ''
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
addTitleSuffix: true
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 80
---
