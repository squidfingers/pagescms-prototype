---
title: Home
params:
  components:
    - type: hero
      title: Headline
      subtitle: This is a [subtitle](https://example.com).
      image: /media/image.jpg
    - type: cards
      cards:
        - title: Section One
          image: /media/opossum.jpg
          content: This is section one.
          buttons:
            - label: Learn more
              link: https://example.com
            - label: Another button
              link: https://example.com
              variant: secondary
        - title: Section Two
          content: This is section two.
        - title: Section Three
          content: This is section three.
    - type: accordion
      details:
        - summary: Item one
          content: This is **content** for item one.
        - summary: Item two
          content: This is content for item two.
        - summary: Item three
          content: This is content for item three.
        - summary: Item four
          content: This is content for item four.
    - type: text
      content: |-
        ### Heading

        This is a text block.
    - type: cards
      cards:
        - title: Another card
          content: foo 123
---
