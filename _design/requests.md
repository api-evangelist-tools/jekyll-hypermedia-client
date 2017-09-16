---
layout: line
class:
  - line
rel:
  - /rels/line  
properties:
  name: Design
  description: This is an API transit line for learning, applying, and developing an API design strategy, that allows anyone to walk through web API design concepts.
entities:
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: SSL
    links:
      - rel:
          - stop
        href: /design/requests/ssl/        
links:
  - rel:
      - self
    href: /design/
---