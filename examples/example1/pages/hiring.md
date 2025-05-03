---
layout: core/base
layoutConfiguration:
  size: small
title: Sitic - Hiring
---

```yaml components
- component: core/spacer
  data:
    height: 24
- component: core/articlelist
  data:
    title: RouteVN - Hiring
    subtitle: Are you interested in workng for RouteVN? We are hiring for the following positions.
    back:
      href: /
      text: Back
    items: {{ collections['hiring'] | json }}
- component: core/spacer
  data:
    height: 100
``` 