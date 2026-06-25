---
layout: page
title: Bionicle Destiny of the Toa
permalink: /BionicleDOTT/
description: A procedurally generated open-world RPG made in Monogame / C#
image: assets/images/bio.png
show_tile: false
nav-menu: false
---

<div id="main" class="alt">

    <section id="Title">
        <div class="inner">
            <header class="major">
                <h1>Bionicle Destiny of the Toa</h1>
                (May, 2023)
            </header>

            <p>
                A procedurally generated open-world RPG made in Monogame / C#, made as part of my AP in Computer Science.<br>
            </p>
        </div>
    </section>

    <section id="Video">
        <div class="inner">
            <header class="major">
                <h2>Trailer</h2>
            </header>

            <div style="position: relative; padding-top: 50%;">
                <iframe
                    src="https://www.youtube.com/embed/oL-UjJF-JFA"
                    style="position:absolute;top:0;left:0;width:100%;height:100%;">
                </iframe>
            </div>
        </div>
    </section>

    <section id="About">
        <div class="inner">
            <header class="major">
                <h2>About Bionicle DOTT</h2>
            </header>

            <p>
                Bionicle: Destiny of the Toa' is a LEGO Bionicle fangame, which was made in a couple of weeks as a 
                finals project during my AP in CS.<br><br> It was made by me and 2 of my classmates. We had long joked about
                making our next game a procedurally generated RPG game, but we actually ended up doing it.<br><br> I came up
                with the idea of borrowing the Bionicle franchise as the setting, and helped design the gameplay.
                I was responsible for making the art assets, and implementing core combat and player systems such
                as mask powers, weapons, elemental attacks and more.<br><br>

                My specific contributions were:
            </p>

             <div class="table-wrapper">
                <table>
                    <thead>
                        <tr>
                            <th>Feature</th>
                            <th>Description</th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td>Mask Powers and Abilities</td>
                            <td>Had the responsibility of implementing all the unique powers, and did so by using a modular component system.
                            Each mask is a component, and they can have unique code individually. They either modify stats, such as speed and strength,
                            or grant unique abilities like X-Ray vision and flight.</td>
                        </tr>
                        <tr>
                            <td>Combat Systems</td>
                            <td>The game features ranged and melee combat, but both technically use collider based projectiles.
                            I was responsible for making each type, and ensuring their functionality. To ensure they remain performant,
                            a object-pooling system was used, where a projectile of type and elemental damage could be easily requested,
                            and retrieved.</td>
                        </tr>
                        <tr>
                            <td>Art Assets</td>
                            <td>For a project where deadlines are tight and I myself have many hats, it's important to move quick.
                            For a project intended for hardcore fans of a franchise, it's important to get the details right.
                            To ensure speed and accuracy, the LEGO models were built in the digital software Stud.io, then imported into Blender.
                            Here models could be textured and rigged for simple animation. The model was then rendered from eight directions
                            for each keyframe of their animation, to ensure they would have a pseudo 3D look in the 2D game.
                            The animation controllers I made in the code would then reconcile the objects direction, animation set, and current frame
                            and display the correct sprite based on this, allowing for easy use of the otherwise many sprites.</td>
                        </tr>
                        <tr>
                            <td>Direction & Design</td>
                            <td>In the team, I was the only one experienced with Bionicle, so I ensured that ideas we came up with
                            for gameplay would fit in and be believable, or suggest how the existing world could be put into the game.
                            Otherwise direction was given on world generation, HUD icons and colors, quest types, and more.</td>
                        </tr>
                    </tbody>
                    <tfoot>
                        <tr>
                            <td colspan="2"></td>
                        </tr>
                    </tfoot>
                </table>
            </div>
        </div>
    </section>

    <section id="Links">
        <div class="inner">
            <header class="major">
                <h2>Links</h2>
            </header>

            <ul class="actions">
                <li>
                    <a href="https://ripofirm.itch.io/bionicle-destiny-of-the-toa" class="button special">
                        Itch.io page
                    </a>
                </li>
                <li>
                    <a href="https://youtu.be/oL-UjJF-JFA" class="button special">
                        YouTube Video
                    </a>
                </li>
            </ul>
        </div>
    </section>
</div>