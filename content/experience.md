---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'
  background:
        color: rose
        image:
          # Add your image background to `assets/media/`.
          filename: pink.JPG
          filters:
            brightness: 0
            text_color_light: false
          size: cover
          position: left
          parallax: false

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
  - block: resume-skills
    content:
      title: SkillS
      username: admin
    design:
      show_skill_percentage: false
  - block: resume-certificates
    content:
      title: Certificates
      username: admin
#  - block: resume-languages
#    content:
#      title: Languages
#      username: admin
---
