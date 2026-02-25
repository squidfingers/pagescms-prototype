---
title: Home
params:
  pageHeader:
    enabled: true
    condensed: false
    heading: Home
    subheading: This is a subheading.
  components:
    - type: heading
      level: "3"
      text: Requirements
    - type: accordion
      exclusive: true
      details:
        - summary: Graduation Requirements
          content: Requires 40 credits, including a passing grade in health, geography,
            history, economics, and wood shop.
          open: true
        - summary: System Requirements
          content: Requires a computer running an operating system. The computer must have
            some memory and ideally some kind of long-term storage. An input
            device as well as some form of output device is recommended.
          open: false
        - summary: Job Requirements
          content: Requires knowledge of HTML, CSS, JavaScript, accessibility, web
            performance, privacy, security, and internationalization, as well as
            a dislike of broccoli.
          open: false
    - type: alert
      variant: success
      content: "**Success!** Your changes have been saved."
    - type: cards
      cardlist:
        - {}
        - {}
    - type: tabs
      tablist:
        - tab: Account
          tabpanel: |-
            ### Account Settings

            Manage your account information here.
        - tab: Password
          tabpanel: |-
            ### Password Settings

            Change your password here.
        - tab: Notifications
          tabpanel: |-
            ### Notification Settings

            Configure your notification preferences.
    - type: content
      content: |-
        # Heading 1

        ## Heading 2

        ### Heading 3

        #### Heading 4

        ##### Heading 5

        ###### Heading 6

        This is a paragraph with **bold text**, _italic text_, and [a link](#).

        Here's some `inline code` and a code block:

        ```javascript
        function hello() {
          console.log('Hello, World!');
        }
        ```

        > This is a blockquote. It's styled automatically.
---
