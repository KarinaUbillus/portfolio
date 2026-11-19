---
# Leave the homepage title empty to use the site title
title: ''
summary: 'Environmental economics research, academic program support, and project coordination.'
date: 2026-11-19
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Portfolio PDF
        url: uploads/portafolio-web.pdf
      headings:
        about: 'Professional Summary'
        education: 'Education'
        interests: 'Professional Interests'
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: lg # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: rounded # Options: circle (default), square, rounded
  - block: markdown
    id: research
    content:
      title: 'Research Portfolio'
      subtitle: 'Environmental economics, agricultural value chains, biodiversity, and public research administration.'
      text: |-
        My work connects empirical research with practical decision-making across rural development,
        environmental policy, protected natural areas, university programs, and publicly funded initiatives.
    design:
      columns: '1'
  - block: collection
    id: projects
    content:
      title: Selected Research & Projects
      text: 'Academic research and professional project coordination.'
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
      fill_image: true
      show_date: false
  - block: markdown
    id: impact
    content:
      title: 'Core Strengths'
      subtitle: 'Research administration · Grant coordination · Stakeholder engagement · Data analysis'
      text: |-
        - Research coordination and primary data collection

        - Agricultural, environmental, and natural resource economics

        - Grant administration and institutional collaboration

        - Statistical analysis and evidence-based recommendations

        - Academic program support and documentation management
    design:
      columns: '1'
  - block: cta-card
    content:
      title: Research, sustainability, or program coordination
      text: Interested in research coordination, environmental economics, sustainability initiatives, or university administration?
      button:
        text: View experience
        url: experience/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl'
        css_style: ''
---
