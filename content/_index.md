---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 
          icon: r-project
          icon_pack: fab
        - name: Biostatistics
          description: 
          icon: chart-line
          icon_pack: fas
        - name: Geographic Information Systems
          description: 
          icon: map
          icon_pack: fas
        - name: Python
          description: 
          icon: python
          icon_pack: fab 
        - name: SQL
          description: 
          icon: postgresql
          icon_pack: fas 
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Research Assistant 
          company: GIS Health and Hazards Lab, Department of Population and Quantitative Health Sciences, Case Western Reserve University
          company_url: ''
          company_logo: 
          location: Cleveland, Ohio
          date_start: '2022-05-01'
          date_end: ''
          description: |2-
              Responsibilities included:
              
              * Coding Python scripts to obtain GPS data from GPX files of       geospatial video feed from refugee camp sites located in the
              Democratic Republic of Congo utilizing Python.
              * Utilizing Machine Learning Algorithms to detect tents in refugee camps from video feed frame-by-frame.
              * Combining the GPS coordinate data with the tent detections to generate maps of refugee camps and their
              locations within the campsites in the DRC.
        - title: Medical Observer
          company: Kauvery Hospitals
          company_url: ''
          company_logo: 
          location: Chennai, India
          date_start: '2020-10-01'
          date_end: '2021-03-01'
          description: |2-
              
        - title: Junior Resident Doctor
          company: Department of Psychiatry, Saveetha Medical College, India
          company_url: ''
          company_logo: 
          location: Chennai, India
          date_start: '2020-07-01'
          date_end: '2020-09-01'
          description: |2-
              Responsibilities included:

              * Diagnosed and managed patients with psychiatric illnesses.
              * Learned to evaluate and diagnose patients in stressful environments.
              * Was assigned a goal of management of five patients per day, which was met.
              * Learned diagnostic criteria for common psychiatric illnesses.
        - title: Intern Doctor
          company: Madras Medical College, Chennai, India
          company_url: ''
          company_logo: 
          location: Chennai, India 
          date_start: '2019-03-01'
          date_end: '2020-03-01'
          description: |2-
              Rotated through the following departments : 
              
              * Internal Medicine    
              * General Surgery 
              * Obstetrics and Gynecology
              * Community Medicine Psychiatry
              * Emergency Trauma Ward
              * Labor Ward
    design:
      columns: '2'
  
  - block: collection
    content:
      title: Publications
      text:
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation 
  
      
---
