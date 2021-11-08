---
title: This is a new page
sections:
  - type: HeroSection
    title: All about the art of selling fish
    subtitle: Fresh. Better. Faster
    text: >
      ###### Aenean eros ipsum, interdum quis dignissim non, sollicitudin vitae
      nisl. Aenean vel aliquet elit, at blandit ipsum. Sed eleifend felis sit
      amet erat molestie, hendrerit malesuada justo ultrices. Nunc volutpat at
      erat vitae interdum. Ut nec massa eget lorem blandit condimentum et at
      risus.
    feature:
      type: ImageBlock
      url: /images/hero-image.png
      altText: Hero section image
    backgroundImage:
      altText: ''
      url: ''
      caption: ''
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: left
        margin:
          - mb-12
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: left
        margin:
          - mb-8
          - mt-8
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    backgroundWidth: inset
  - elementId: ''
    variant: variant-b
    colors: colors-a
    backgroundWidth: full
    title: About us
    subtitle: Meet the team
    actions: []
    people:
      - content/data/team/desmond-eagle.json
      - content/data/team/dianne-ameter.json
      - content/data/team/hilary-ouse.json
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
      actions:
        justifyContent: center
    type: FeaturedPeopleSection
  - elementId: ''
    variant: variant-a
    colors: colors-a
    backgroundWidth: full
    title: Latest posts
    subtitle: ''
    actions:
      - type: Button
        label: View all
        url: /
        style: primary
    posts:
      - content/pages/blog/post-three.md
      - content/pages/blog/post-two.md
      - content/pages/blog/post-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
        padding:
          - pt-12
          - pb-12
        alignItems: center
        justifyContent: center
      title:
        fontWeight: 700
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-2
      subtitle:
        fontWeight: 400
        fontStyle: normal
        textAlign: center
        margin:
          - mt-0
          - mb-12
      actions:
        justifyContent: center
        margin:
          - mt-12
          - mb-0
    type: FeaturedPostsSection
layout: PageLayout
_slug: pleasant-oak-257
---
