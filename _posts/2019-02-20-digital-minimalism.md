---
title: Minjee Choi
tags: [Nanasaki]
style:
color: danger
description: A renowned genius in the entertainment industry, the idol MINA☆ !!
---
## ☆Minjee Choi☆ 

![preview](../images/characters/character-sheet-mina.png)

Nicknames/Alias: MINA𖤐<br>
Age: 22<br>
Birthday: May 16th<br>
Height: 5’7<br>
Gender: Female<br>
Sexuality: Bi<br>
Species/Race: Human<br>

Affiliation(s):<br>
Nanasaki <br>
USANG Entertainment<br>

Occupation(s):<br>
Celebrity/Idol<br>

Relatives:<br>
Father - deceased<br>
Mother - complicated<br>

Relationships:<br>
Jin Kang - Lover<br>
Sua Kang - Best friend<br>
Band members - Sora Kazuya, Ayako Saito, Nagisa Hanamine, Sua Kang<br>
Yuichiro Saotome - Close friend with a sibling like relationship<br>

Lore: As she’s built her reputation and become the #1 sensation across the world, she got invited to join a competition show with other famous celebrities from around the world. This show… turns out to be a death game that she can’t escape. When she arrives, something resembling a system window pops up in front of everyone in the world, announcing the death games, with this show being one of them. The only way to live is to outshine the others, so she performs to save her own life. Throughout the games, she gets less and less in touch with her humanity, losing her sanity from all the deaths she sees while also trying to keep it together and perform as the perfect angel everyone makes her out to be.

Personality: She acts like a very bubbly person and puts on a show for everyone, like an ‘angel.’ But she’s also very cunning, and knows how to get her way in the entertainment industry. She was a top student in her high school days. 

Backstory: Her father died when she was very young in an accident, and her mother, filled with grief, moved them to Japan. When her dad died, Mina wasn’t very kind to her mother. This causes a very strained relationship, as her mother doesn’t even look at her, much less acknowledge her as her daughter anymore. Once she graduates High School, she reunites with her childhood friend, Sua Kang, and her brother, Jin Kang. Minjee's passion for music becomes a reality as she creates a band with Sua and some old friends from her high school, and from there, she is known as a young talent with potential, and grows into the star she is today.

Powers/Abilities: Her "ability" is that she can trick people into loving her through her performances and the way she meticulously presents herself at every moment.

Character Inspirations: Ai Hoshino (Oshi no Ko)<br>
Voice Claim: Sumetal (lead vocalist) from Babymetal<br>
Currently Listening To: Megitsune - Babymetal<br>

<p class="text-center">⋆𐙚₊˚⊹♡
{% include elements/button.html link="https://vsona.co/minjee-mina-choi" text="Visit her VGen!" %}
⋆𐙚₊˚⊹♡</p>

## Gallery

<div class="artworks-gallery">
    {% for file in site.static_files %}
        {% if file.path contains "images/characters/minjee-choi" %}
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