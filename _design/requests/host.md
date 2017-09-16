---
layout: stop
---
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: Host
  description: Put sufficient thought into what the baseURL will be for making API calls. Increasingly this element can also be dynamic, like other aspects of API design.
entities:
  - class:
      - image
    rel:
      - /rels/image
    properties:
      - name: SSL Image
        url: /image/
  - class:
      - video
    rel:
      - /rels/video
    properties:
      - name: SSL Video
        url: /video/
        embed: <embed>
    links:
      - rel:
          - self
        href: /design/requests/host/
actions:
  - name: view-item
    title: View Item
    method: POST
    href: /stop/view/
    type: application/x-www-form-urlencoded
    fields:
      - name: name
        type: hidden
        value: 'SSL'
      - name: user
        type: hidden
        value: ''        
links:
  - rel:
      - self
    href: /design/requests/host/
  - rel:
      - previous
    href: /design/requests/stop/
  - rel:
      - next
    href: /design/requests/stop/