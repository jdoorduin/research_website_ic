---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
      image:
        filename: 
      text: |   
        The Nijmegen Respiratory Failure and Mechanical Ventilation research group of the Radboudumc in the Netherlands is focused on reducing the harmful effects of mechanical ventilation in critically ill patients, by developing and applying novel technological innovations and integrative physiological approaches focused on the lung, brain, and respiratory muscles. To obtain this goal we combine preclinical research, clinical studies ranging from observational cohort studies, to diagnostic accuracy studies and randomized controlled trial and data from large registries.
          
  - block: markdown
    id: news_1
    content:
      title: Latest News
      subtitle:
      text: |
        **September 2024** - [Leo Heunks]({{< relref "/authors/leo-heunks" >}}) receives life-time achievement award from the European Respiratory Society 🙏<br>
        **August 2024** - We are happy to announce [Jonne Doorduin]({{< relref "/authors/jonne-doorduin" >}}) is appointed Assistant Professor in the Radboudumc Talent Track 😃 <br>
        **August 2024** - [Esther de Leijer]({{< relref "/authors/esther-de-leijer" >}}) joined our [team](#team_1) as PhD student to perform the [WEANLESS]({{< relref "/projects/WEANLESS" >}}) study 💪 Welcome Esther!
    design:
      columns: '1'

  - block: collection
    id: blog_1
    content:
      title: Blog
      subtitle: 
      text: 
      filters:
        folders:
          - blog
    design:
      columns: '1'
      view: compact

  - block: collection
    id: projects_1
    content:
      title: Projects
      subtitle: 
      text: 
      filters:
        folders:
          - projects
    design:
      columns: '1'
      view: compact

  - block: people
    id: team_1
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Principal Investigators
          - Researchers
          - Graduate Students
          - Administration
          - Visitors
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: true
      show_role: true
      show_social: true

  - block: collection
    id: publications_1
    content:
      title: Latest Publications
      text: |
        {{% callout note %}}
        Quickly discover relevant content by filtering [publications]({{< relref "/publication/" >}}).
        {{% /callout %}}
      count: 10
      filters:
        folders:
          - publication
        publication_type: 'article-journal'

    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Contact us →" %}}
    design:
      columns: '1'
---