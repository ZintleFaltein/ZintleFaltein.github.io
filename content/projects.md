---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'
  background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: pink.JPG
          filters:
            brightness: 0.5
          size: cover
          position: left
          parallax: false

# Page sections
sections:
  - block: collection
    content:
      title: Projects I've worked on
      text: Here you’ll find a selection of projects that showcase my skills in data science, analytics, and problem-solving. Each project reflects my passion for using data to answer meaningful questions, tell compelling stories, and deliver practical solutions.

      filters:
        folders:
          - project
    design:
      view: compact
      fill_image: false
      #columns: 3
---
