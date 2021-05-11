name: 🐛 Report a bug
about: Create a bug report to help improve pynab
labels: "bug"
body:
  - type: markdown
    attributes:
      value: >
        **Thank you for wanting to report a bug in pynab!**


        If this is the first time you are doing this, please take a few moments to read through
        the [Contribution Guidelines](CONTRIBUTING.md).
        Also check out [the Discussion](discussions) and
        [the Forum](http://tagtagtag.fr/forum/) if your problem is maybe already covered there.


        You are about to report a bug in **pynab**. Do not seek support here ("I need help with ...", "I have a
        question ...", "Can someone walk me through ..."), that belongs into the
        [Discussion](discussions) or on the
        [community forum at tagtagtag.fr](http://tagtagtag.fr/forum/).


        And finally, make sure any bug you want to report is still present with the **current**
        pynab version.


        Thank you for your collaboration!
  - type: textarea
    attributes:
      label: The problem
      description: >-
        Describe the issue you are experiencing here. Tell us what you were trying to do
        step by step, and what happened that you did not expect.

        Provide a clear and concise description of what the problem is and include as many
        details as possible.
      placeholder: |
        1. ...
        2. ...
        3. ...
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        ## Environment
  - type: input
    attributes:
      label: Version of pynab
      description: >-
        How to know my pynab version, please see [here](#).
  - type: dropdown
    attributes:
      label: Version of Nabaztag
      description: >-
        How to know my Nabaztag version, please see [here](#).
      options:
        - Nabaztag (v1)
        - Nabaztag:Tag (v2)
    validations:
      required: true
  - type: dropdown
    attributes:
      label: Version of TagTagTag
      description: >-
        How to know my TagTagTag version, please see [here](#).
      options:
        - Maker Faire 2018
        - Campagne Ulule en mai 2019
    validations:
      required: true
  - type: input
    attributes:
      label: Browser and version of browser, operating system running browser
      description: If applicable, always include if unsure

  - type: markdown
    attributes:
      value: |
        ## Other files needed for analysis
  - type: checkboxes
    attributes:
      label: Checklist of files to include below
      options:
        - label: Screenshots and/or videos showing the problem (always include in case of issues with the user interface)
  - type: textarea
    attributes:
      label: Additional information & file uploads
