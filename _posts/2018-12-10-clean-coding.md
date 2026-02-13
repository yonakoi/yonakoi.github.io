---
title: Bonnie Montclair
tags: [No Place to Lie]
style: 
color: 
description: A girl who always has a smile on her face. The bigger the secret, the bigger the smile.
---

This has spoilers to my game No Place to Lie! It is recommended to play the game first and then continue on!

<p class="text-center">⋆𐙚₊˚⊹♡
{% include elements/button.html link="https://yonakoi.itch.io/no-place-to-lie" text="Play the Game!" %}
⋆𐙚₊˚⊹♡</p>

![preview](../images/characters/character-sheet-bonnie.png)

Nicknames/Alias: N/A<br>
Age: 23<br>
Gender: Female<br>
Sexuality: Lesbian<br>

Occupation(s):<br>
Assistant Investigator<br>

Relatives:<br>
Mother - a soft spoken but kind woman. She’s very paranoid about Bonnie’s health<br>
Father - the kind of guy that calls bonnie kiddo. Became closed off and silent when Bonnie died<br>

Relationships:<br>
Evelyn - High school sweethearts. Bonnie was too afraid to open up to Evelyn. If she did, and Evelyn treated her just like everyone else did, it would be too much for her to bear. So, the closer they got, the more Bonnie hid. <br>

Lore: Bonnie got into a car accident. She had an attack from her health (coughing fit, heart problem, etc) that distracted her from the wheel causing the accident with her death and the other person still living.

Personality: She is always seen as someone who is bright and smiling. However, she has a clear wall that doesn't allow her to let anyone into her life, not even her girlfriend. She doesn't let her true self shine because she’s afraid of rejection, and hides her ‘ugly’ emotions – she wants to be flawless. She's a strong willed and stubborn girl who doesn’t like admitting weakness because of how she’s been treated as fragile her whole life.

Backstory: She’s always been sick her whole life. Because of this, her parents were extra doting and caring towards her. To Bonnie’s dismay, they treated her like she could break at any moment, so she hid her weaknesses to avoid similar treatment from others. Some time in elementary school, her condition wasn’t hidden - it was out in the open. Because of this, the adults around her would act like her parents, and the kids would generally stay away from her so as not to be held responsible if something did happen.

Character Inspirations: Mari (Omori)<br>
Currently Listening To: Back to Me - The Marias<br>

## Gallery

<div class="artworks-gallery">
    {% for file in site.static_files %}
        {% if file.path contains "images/characters/bonnie-montclair" %}
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