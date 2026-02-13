---
title: Jin Kang
tags: [Nanasaki]
style: 
color: info
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

Affiliation(s):<br>
Haneul College of Law<br>

Occupation(s):<br>
Law Student<br>

Relatives:<br>
Sua Kang - Younger sister<br>
Jiho Kang - Twin brother<br>
Mother - Good standing<br>
Father - Not talking to<br>

Relationships:<br>
Minjee Choi - Lover<br>
Sora Kazuya - Best friend<br>

Lore: When the performance games began, Jin desperately fought to save Mina. However, he was too late. When he arrived, he was in the crowd of people cheering her on, trying to shove past people as fast as possible. Once he reaches the first row, he attempts to climb on the stage. However, a loud noise rings throughout the stage, and blood starts to spill. Minjee has died, and she died to protect someone. Jin was also hurt for breaking the rules, and as he lays dying and desperately grasping for Minjee, a strange pocket watch gets thrown on the stage. Jin instinctively reaches out for it, and as he squeezes it, he goes unconscious. When he wakes up... He's on the day everything started again.

Personality: He's quiet, but not cold. At first, he was a very loving person, however, as he goes through more and more timelines, he becomes more unforgiving. He starts to prioritize the lives of others less, as his one goal remains unchanged, no matter who the sacrifice is.

Backstory: When he was a kid, he had a twin brother, Jiho. They were the sons of a rich man, along with their younger sister, Sua. At a young age, Sua and Jin got seperated from Jiho and their father. Their father took Jiho and seperated from their mother. Shortly after that, Sua met Minjee, and the two became inseperable best friends until Minjee moved away. During this time, Jin had always watched Minjee from a distance, blinded by her radiance. When she moved, he would think about her frequently, and when he thought he had finally moved on, she appeared in his life again as an idol. This time, he wasn't going to let her go.

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