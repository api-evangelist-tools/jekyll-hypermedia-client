---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: Verbs
  description: Learn about, and put all HTTP verbs to use when designing APIs.There is more than just GET, and even more than just POST, PUT, and DELETE.
entities:
  - class:
      - image
    rel:
      - /rels/image
    properties:
      - name: path Image
        url: /image/
  - class:
      - video
    rel:
      - /rels/video
    properties:
      - name: path Video
        url: /video/
        embed: <embed>
    links:
      - rel:
          - self
        href: http://api.x.io/customers/pj123
actions:
  - name: view-item
    title: View Item
    method: POST
    href: /stop/view/
    type: application/x-www-form-urlencoded
    fields:
      - name: name
        type: hidden
        value: 'path'
      - name: user
        type: hidden
        value: ''        
links:
  - rel:
      - self
    href: /design/requests/path/
  - rel:
      - area
    href: /design/area/      
  - rel:
      - line
    href: /design/requests/          
  - rel:
      - previous
    href: /design/requests/action/
  - rel:
      - next
    href: /design/requests/parameters/
---