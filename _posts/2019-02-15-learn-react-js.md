---
title: Jin Kang
tags: [Nanasaki]
style: 
color: danger
description: A cold hearted law student who would do anything for his love.
---

## Jin Kang

Nicknames/Alias: N/A <br>
Age: 24 <br>
Birthday: June 16th <br>
Height: 5'9 <br>
Gender: Male <br>
Sexuality: Bi <br>
Species/Race: Human <br>

Affiliation(s):


Occupation(s):
Law Student

Relatives:
Sua - Younger sister
Jiho - Twin brother
Mother - Good standing
Father - Not talking to

Relationships:
Minjee - Lover
Sora - Best friend

Lore:

Personality:

Backstory:

Powers/Abilities: He can turn back time to the day before the games began using a pocket watch he was given.

Voice Claim: Akugetsu <br>
Currently Listening To: Shoot Your Head - FatDog<br>

## Gallery

<div class="artworks-gallery">
    {% for file in site.static_files %}
        {% if file.path contains "images/characters/jin-kang" %}
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