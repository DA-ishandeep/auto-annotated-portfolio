---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/post-3.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Hi! I'm Ishan
    subtitle: >-
      I have over 11+ years of experience in Data analytics and Business
      Intelligence. My proficiency extends to advanced Excel functionalities
      such as VBA Macros and Power Query. With a solid foundation in Python and
      SAS and experience with databases like SQL Server, PostgreSQL, and
      Teradata, I am adept at extracting, analyzing, and visualizing data to
      derive actionable insights. As a PL 300 certified Power BI professional, I
      thrive in transforming complex datasets into compelling visual narratives.
      My skills also encompass ETL processes using Informatica PowerCenter and
      IICS. I am passionate about leveraging data to drive informed
      decision-making and continuously seek opportunities to expand my knowledge
      and expertise in the evolving field of data analytics.
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
          - pt-36
          - pb-24
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
        borderRadius: xx-small
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
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: wide
        padding:
          - pt-2
          - pb-2
        justifyContent: center
        borderWidth: 1
  - type: LabelsSection
    title: Skills
    subtitle: ''
    items:
      - type: Label
        label: PYTHON
        url: ''
      - type: Label
        label: SQL
        url: ''
      - type: Label
        label: SAS
        url: ''
      - type: Label
        label: IICS ETL
        url: ''
      - type: Label
        label: TABLEAU
        url: ''
      - type: Label
        label: POWER BI
        url: ''
      - type: Label
        label: 'AWS ( GLUE, S3, REDSHIFT )'
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: wide
        padding:
          - pt-11
          - pb-11
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions: []
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
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
    subtitle: Projects
  - type: MediaGallerySection
    title: CERTIFICATIONS / TRAININGS
    subtitle: ''
    images:
      - type: ImageBlock
        url: /images/PL - 300.PNG
        altText: Power BI - PL 300
        caption: PL 300
        elementId: ''
      - type: ImageBlock
        url: /images/PCEP Cert.jpg
        altText: PCEP
        caption: PCEP
        elementId: ''
      - type: ImageBlock
        url: /images/CSM.jpeg
        altText: Image three
        caption: Image three caption
        elementId: ''
    colors: colors-f
    spacing: 9
    columns: 4
    aspectRatio: auto
    showCaption: false
    enableHover: true
    elementId: ''
    styles:
      self:
        height: auto
        width: full
        padding:
          - pt-3
          - pb-3
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: center
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    elementId: ''
    styles:
      self:
        width: narrow
        padding:
          - pt-1
          - pb-1
          - pl-4
          - pr-4
        justifyContent: center
        borderWidth: 1
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Need to connect with me...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
---
