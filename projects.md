---
layout: page
title: Projects
permalink: /projects/
images:
  - image_path: /projects/img/speakcolors.png
    title: SpeakColors
    link: /projects/speakcolors/
  - image_path: /projects/img/speechcards.png
    title: Speech Cards
    link: /projects/speech-cards/
  - image_path: /projects/img/beat-tracker.png
    title: Beat Tracker
    link: /projects/beat-tracker/
  - image_path: /projects/img/liftup.png
    title: Lift Up
    link: /projects/lift-up/ 
  - image_path: /projects/img/mysdmobile.png
    title: MySDMobile
    link: /projects/mysdmobile/
  - image_path: /projects/img/usd-kiosk.png
    title: USD Kiosk
    link: /projects/usd-kiosk/
  - image_path: /projects/img/usd-checkin.png
    title: USD Event Check-In
    link: /projects/usd-event-check-in/
  - image_path: /projects/img/artikpixlevels.png
    title: ArtikPix Levels
    link: /projects/artikpix-levels/
  - image_path: /projects/img/percentallypro2.png
    title: Percentally Pro 2
    link: /projects/percentally-pro-2/
  - image_path: /projects/img/raffleway.png
    title: Raffleway
    link: /projects/raffleway/
---

<h2>iOS Apps</h2>

<center>
    <ul class="photo-gallery">
        {% for image in page.images %}
            <li>
                <figure>
                    <a href="{{ image.link }}"><img src="{{ image.image_path  }}" alt="{{ image.title }}" border="0"/></a>
                    <figcaption><a href="{{ image.link }}">{{ image.title }}</a></figcaption>
                </figure>
            </li>
        {% endfor %}
    </ul>
</center>
