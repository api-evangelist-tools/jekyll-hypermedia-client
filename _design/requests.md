---
layout: line
class:
  - stop
rel:
  - /rels/stop  
properties:
  name: Action
  description: Allow for standard actions to be taken across resource, but also reflect how APIs will be experienced, providing meaningful action to be taken around any API.
entities:
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: SSL
    links:
      - rel:
          - self
        href: /design/requests/ssl/      
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Host
    links:
      - rel:
          - self
        href: /design/requests/host/  
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Path
    links:
      - rel:
          - self
        href: /design/requests/path/  
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Action
    links:
      - rel:
          - self
        href: /design/requests/action/                             
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: verbs
    links:
      - rel:
          - self
        href: /design/requests/verbs/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Parameters
    links:
      - rel:
          - self
        href: /design/requests/parameters/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Headers
    links:
      - rel:
          - self
        href: /design/requests/headers/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Body
    links:
      - rel:
          - self
        href: /design/requests/body/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Versioning
    links:
      - rel:
          - self
        href: /design/requests/versioning/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Pagination
    links:
      - rel:
          - self
        href: /design/requests/pagination/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Filtering
    links:
      - rel:
          - self
        href: /design/requests/filtering/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Sorting
    links:
      - rel:
          - self
        href: /design/requests/sorting/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Field Selection
    links:
      - rel:
          - self
        href: /design/requests/field-selection/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Granularity
    links:
      - rel:
          - self
        href: /design/requests/granularity/           
  - class:
      - stop
    rel:
      - /rels/stop
    properties:
      - name: Relationships
    links:
      - rel:
          - self
        href: /design/requests/relationships/           
links:
  - rel:
      - self
    href: /design/requests/
  - rel:
      - area
    href: /design/      
---

