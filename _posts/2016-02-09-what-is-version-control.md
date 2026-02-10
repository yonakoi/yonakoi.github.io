---
title: Hanako Taeko
tags: [Hamori]
style: 
color: dark
description: A strange, yet alluring woman you can't help but be drawn to.
---

WIP

## Hanako Taeko

![preview](../images/characters/character-thumbnail-hanako.png)

Nicknames/Alias: Bloody Mary <br>
Age: 22ish – exact age unknown <br>
Birthday: ?? <br>
Height: 5’9 <br>
Gender: Female <br>
Sexuality: ?? <br>
Species/Race: Human <br>

Affiliation(s): <br>
Hamori <br>

Occupation(s): <br>
Hamori Executive <br>

Relatives:<br>
Himiko Taeko - Twin sister, deceased<br>
Older brother - deceased<br>
Parents- deceased<br>

Relationships:<br>
Nagori - A kid Hanako found on a job. She took her in as an apprentice, but isn't the ideal parent...<br>
Gaki - Interested in his story, finds it amusing to tease him. The two of them parallel each other, which is why Gaki hates her so much; Gaki isn’t fully human but feels everything, and Hanako is one who feels nothing.<br>

Lore: Hanako is currently one of the strongest executives in Hamori, on par with Gaki. She is feared due to this, because she is an ordinary human being. She is often sent on intel gathering or assassin missions, due to her ability to analyze and manipulate. 

Personality: Since birth, Hanako has been unable to feel emotions. She always has a smile on her face, and will even be silly at times, but it’s all an act. She is evil, psychotic, and a sociopath. She’s incredibly manipulative, but people can't help but be drawn to her. She is like this both because of her upbringing, and because of the violent environment she had been in her whole life. Since she can't judge things emotionally, she studies human behavior to "replicate" being a human.

Backstory: Hanako was born into Hamori. Her parents were valued executives of Hamori, however, they kept the details from their kids. Growing up, Hanako quickly realized she was different. She saw other kids express constant high emotions, and thought it was strange. She also noticed other adults grow concerned about her, so she quickly learned how to act like everyone else around her. She pretended to feel joy, sadness, frustration, etc., but the truth was she felt nothing. Not until a certain incident. Before this, since her parents are from Hamori, they’ve always taught her to deal with things through violence. They told her to be the strongest, and to take advantage of other people’s emotions. They basically taught her to take what she wants, with whatever means necessary. Her parents didn’t necessarily raise her and her siblings with love, but with logic. They were emotionally neglectful. The closest person she had to her was her twin sister, Himiko. Himiko was the only person who truly showed Hanako affection, another thing she didn’t understand. Hanako mirrored Himiko’s behaviors, giving Himiko affection back. Back to that incident, in her school days she found an interest in some person in her class. Obviously, not a romantic interest, but she studied them because they were different. Her classmates didn't know this of course, so girls didn’t like that she paid attention to this person, which ended up in them confronting her about it with a heated argument and attempts to bully her. But… remember what Hanako’s parents taught her. This broke out into a fight, where Hanako firsthand felt violence for the first time. What she felt during this was… ecstasy. The person she fought ended up having severe injuries, and of course, Hanako got suspended. But this was the first time Hanako actually felt anything in her life. From then, she would occassionaly experiment, but it wasn’t the same. 
At some point, Hanako’s home gets set on fire, killing everyone except her brother who was MIA. Himiko sacrificed herself to save Hanako… It was believed that this happened because of the many enemies Hanako’s parents made, until Hanako reunited with her older brother.

Powers/Abilities: None. She is completely and 100% a regular human being, which makes her all the more terrifying.

Character Inspirations: Douma (Demon Slayer), Junko Enoshima (Danganronpa) <br>
Voice Claim: Chloe D’Apchier Japanese Voice <br>
Currently Listening To: Echo Remix - The Living Tombstone <br>

## Gallery

<div class="artworks-gallery">
    {% for file in site.static_files %}
        {% if file.path contains "images/characters/hanako-taeko" %}
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