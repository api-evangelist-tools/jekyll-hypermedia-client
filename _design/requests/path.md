---
layout: stop
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: Path
  description: Consider how you craft your resources across all API operations. I do not subscribe to specific philosophies around this, just trying to provide a framework to think about this in.
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
      - service
    href: /design/      
  - rel:
      - line
    href: /design/requests/          
  - rel:
      - previous
    href: /design/requests/host/
  - rel:
      - next
    href: /design/requests/path/
---