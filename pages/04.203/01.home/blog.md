---
title: Home
published: true
visible: false
hide_page_title: true
post_icon: calendar-o
hide_post_summary: true
hide_post_date: true
hide_post_taxonomy: true
display_post_summary: true
child_type: item
content:
    items: '@self.children'
    limit: 20
    order:
        by: date
        dir: desc
    pagination: true
modular_content:
    items: '@self.modular'
    order:
        by: title
        dir: dsc
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': 'CMPT-363 User Interface Design'
    'twitter:description': 'The Course Hub for CMPT 363 User Interface Design at Simon Fraser University'
    'twitter:image': 'https://opencoursehub.cs.sfu.ca/paulh/cmpt-363/203/headerimage/melisa-hildt-aV2uMw3zfwQ-unsplash.jpg'
feed:
    limit: 10
    description: 'The Course Hub for CMPT 363 User Interface Design at Simon Fraser University'
---
