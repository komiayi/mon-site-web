---
date: "2023-03-01"
sections:

- block: about.avatar
  content:
    text: null
    username: admin
  id: acceuil
- block: features
  content:
    items:
    - description: 90%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 100%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 10%
      icon: camera-retro
      icon_pack: fas
      name: Photography
    title: Compétences
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Certificats
  design:
    columns: "2"
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: R package
      tag: R package
    - name: R Shiny
      tag: R Shiny
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projets
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projets
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Publications
  design:
    columns: "2"
    view: citation
  id: publication
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: blog
- block: collection
  content:
    filters:
      folders:
      - event
    title: Recent & Upcoming Talks
  design:
    columns: "2"
    view: compact
  id: blog
- block: contact
  content:
    address:
      city: Montréal
      country: Canada
      country_code: CA
      postcode: "H2X 3Y7"
      region: Qc
      street: Département de mathématiques 
    email: ayi.komi_roger@courrier.uqam.ca
    phone: 1(438)882-6791
    title: Contact
  id: contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
