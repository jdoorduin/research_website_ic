---
title: STUDY-NAME
summary: Study summary
date: 2026-01-01
authors:
  - jonne-doorduin
type: landing
tags:
image:
  caption:

sections:
  - block: hero
    content: 
      title: |
      image:
        filename: featured.png
      text: |   
        **Welcome to the NEW study page** <br><br>
        Here you can read more about our NEW study.
          
  - block: markdown
    id: NEW_news_1
    content:
      title: Latest News
      subtitle:
      text: |
        **July 2025** New project started!

  - block: features
    content:
      title: Currently Recruiting Centers
      text: |
        Centers currently including patients.

        <br>
      items:
        - name: "Radboudumc, Nijmegen"
          icon_pack: "fas"
          icon: "hospital"
          description: "Coordinating center, located in Nijmegen."
        - name: "Other hospital, City"
          icon_pack: "far"
          icon: "hospital"
          description: "hospital in city."

  - block: markdown
    content:
      title: "Study Summary"
      text: |


  - block: people
    id: team_1
    content:
      title: Steering Committee
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
      sort_by: Params.last_name
    design:
      columns: '1'
      sort_ascending: true
      show_interests: false
      show_role: false
      show_organizations: true

  - block: markdown

  - block: files
    content:
      title: "Important Documents"
      items:
        - name: "file number 1"
          url: "/files/placeholder.pdf"
          description: "One"
          icon: "far fa-file"
        - name: "file number 2"
          url: "/files/placeholder.pdf"
          description: "Two"
          icon: "far fa-file"
        - name: "file number 3"
          url: "/files/placeholder.pdf"
          description: "Three"
          icon: "far fa-file"
        - name: "file number 4"
          url: "/files/placeholder.pdf"
          description: "Four"
          icon: "far fa-file"


---