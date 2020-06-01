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
        by: folder
        dir: dsc
metadata:
    'twitter:card': summary
    'twitter:site': '@hibbittsdesign'
    'twitter:title': 'CMPT-363 User Interface Design'
    'twitter:description': 'Course Hub for CMPT 363 User Interface Design at Simon Fraser University'
    'twitter:image': 'https://paulhibbitts.net/cmpt-363/193/headerimage/8447615314_85ba7d2b70_o.jpg'
feed:
    limit: 10
    description: 'Course Hub for CMPT 363 User Interface Design at Simon Fraser University'
---
