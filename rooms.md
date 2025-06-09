---
title: "Rooms to rent"
layout: page
description: Rent a Room
intro_image: "images/illustrations/reading.svg"
intro_image_absolute: true
intro_image_hide_on_mobile: true
---

Looking for a space for your workshop, meeting, or social gathering? **Blixems** has you covered with comfortable, versatile rooms.

## Our spaces
{% for room in site.rooms %}
- {{ room.title }}, {{ room.description }}, [details »]({{ room.url }})
{% endfor %}

## Rates & Equipment
> **Note:** Neighborhood associations get a **56% discount**!

Here’s a quick overview of our equipment rentals:

| Equipment            | Price     |
|----------------------|-----------|
| Beamer               | €12,00    |
| Whiteboard           | Free      |
| Flipover             | €6,00     |
| Projectiescherm      | €6,00     |
| Muziek installatie   | €13,30    |
| Hang tafel           | €7,25     |
| Rok voor hangtafel   | €12,00    |
| Tapijt per evenement | €156,65   |



To book a room or inquire, please [contact us](/contact).
