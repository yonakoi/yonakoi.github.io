---
title: Junichiro Ueno
tags: [Hamori]
style: 
color: danger
description: A detective who specializes in yokai cases.
---

WIP

Nicknames/Alias: Jun, Detective<br>
Age: 24<br>
Birthday: February 14th<br>
Height: 6’0<br>
Gender: Male<br>
Sexuality: “Straight”<br>
Species/Race: Human<br>

Affiliation(s):<br>
Tsukiyo Detective Bureau<br>

Occupation(s):<br>
Detective<br>

Relatives:<br>
Father - Cold and distant. Only sees Jun as a tool.<br>
Mother: Deceased<br>
Uncle: Deceased; was more like a father than his actual father. He passed away due to a job accident at the agency.<br>
First Sibling: Deceased. Couldn't handle the pressure his father put on him.<br>
Second Sibling: Distant, hates Jun because she blames him for the death of her "sister" and mother.<br>
The two siblings are twins.<br>

Relationships:<br>
Gaki - Jun can’t help but hope for the person Gaki once was before they split up. After all, that’s who he’s been searching for this whole time. Gaki is fully aware of this, but can never go back to the way he was. Because of this, Gaki doesn’t think Jun is ever capable of seeing the current him, but a ghost of him.<br>
Chiemi - Close friends; they banter like siblings do<br>
Nagori - found family little sister<br>

Lore:

Personality: Seems very distant and cold, however once you talk to him he is a very gentle person. Only seems to lose his composure around Gaki. Despite this, he’s too kind and naïve for his own good.

Backstory: 

Powers/Abilities: N/A

Voice Claim: Himmel the Hero -- Nobuhiko Okamoto<br>
Currently Listening To: Take Me to Church - Hozier<br>

## Gallery

<div class="artworks-gallery">
    {% for file in site.static_files %}
        {% if file.path contains "images/characters/junichiro-ueno" %}
        {% if file.extname == '.png' or file.extname == '.PNG' or file.extname == '.jpeg' or file.extname = '.JPEG' %}
            
            {% assign filenameparts = file.path | split: "/" %}
            {% assign filename = filenameparts | last | replace: file.extname,"" %}
    
            <a href="{{ file.path }}" title="{{ filename }}">
                <img src="//wsrv.nl/?url=yonakoi.github.io{{ file.path }}&w=300&h=300&output=jpg&q=50&t=square" alt="{{ filename }}" />
                <span>{{ filename }}</span>
            </a>
            {% endif %}
        {% endif %}
    {% endfor %}
</div>

<style>
    .artworks-gallery {
        display: flex;
        flex-wrap: wrap;
        gap: 15px;
        justify-content: center;
        margin-top: 30px;
    }

    .artworks-gallery a {
        display: block;
        text-align: center;
        text-decoration: none!important;
        max-width: 400px;
    }

    .artworks-gallery img {
        width: 100%;
        height: auto;
        border-radius: 10px;
    }
</style>