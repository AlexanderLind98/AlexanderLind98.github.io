---
layout: page
title: CINIS
permalink: /CINIS/
description: A Retro FPS ARPG in ongoing development
image: assets/images/CINIS_RPG_Banner.PNG
nav-menu: false
show_tile: true
---

<div id="main" class="alt">

    <section id="Title">
        <div class="inner">
            <header class="major">
                <h1>CINIS</h1>
                (May, 2025 - Ongoing)
            </header>

            <p>
                A FPS ARPG, with a retro artstyle. It's been publically developed for about a year, and is intended to launch on Steam in the future.<br>
            </p>
        </div>
    </section>

    <section id="Video">
        <div class="inner">
            <header class="major">
                <h2>Game Preview video</h2>
            </header>

            <div style="position: relative; padding-top: 50%;">
                <iframe
                    src="https://www.youtube.com/embed/fVLE-0AJY1U"
                    style="position:absolute;top:0;left:0;width:100%;height:100%;">
                </iframe>
            </div>
        </div>
    </section>

    <section id="About">
        <div class="inner">
            <header class="major">
                <h2>About CINIS</h2>
            </header>

            <p>
                CINIS could be considered my 'Magnum Opus'. All my talents and knowledge is being put to use here. <br>
                Development for the game focuses on being performant, scalable and modular. It makes heavy use of Data-Driven design,
                and features specific to Unreal Engine 5, such as World Partitioning, to allow for a large seamless world. <br>
                <br>
                While mostly a solo project for me, I do recieve help and feedback from testers, and new to this project is
                collaboration with a musician, where I as a director convey the scenarios and major areas of the game,
                and give feedback to the music tracks that are delivered. Additional collaboration
                was done on deciding on how music would be implemented in the game, and when it should be used. <br>
                <br>
                More about the specific features, tech, and content of the game is found below.
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
                            <td>Data-Driven Weapons & Abilities</td>
                            <td>All weapons and abilities in the game are defined using Data Assets, which define their
                            individual traits and stats, allowing for easy modification and iteration.</td>
                        </tr>
                        <tr>
                            <td>Data-Driven AI</td>
                            <td>Enemy AI is also driven by Data Assets, each enemy having a unique "Profile" asset, which
                            determines their behavior in combat, while reusing the same Behavior Tree</td>
                        </tr>
                        <tr>
                            <td>Gravity Distortions / Custom Gravity</td>
                            <td>The game features the ability to change gravity for any and all living entities in a given area.
                            This can be challenging to handle in level layouts, but quite fun.</td>
                        </tr>
                        <tr>
                            <td>Custom Navigation Systems</td>
                            <td>Combining the default Nav-Meshes in Unreal with a custom node-based solution, for unique scenarios.
                            Because Nav-Meshes are not supported on walls or ceilings, or for flying, a custom solution was needed for
                            flying enemies, or in arenas where custom gravity allows for wall and ceiling traversal.</td>
                        </tr>
                        <tr>
                            <td>In-Engine Tools</td>
                            <td>Using the Scriptable Tools System, several editor tools were implemented to assist in the development.
                            Most notable is the Nav-Node Placement and generation tools, allowing for authoring paths in a visual way, or
                            mass-creation of nodes in a volume. Simpler tools like one to set and preview time of day were also made.</td>
                        </tr>
                        <tr>
                            <td>Customizable Characters</td>
                            <td>Players are able to customize their characters as they see fit, but even NPCs and random enemies
                            are able to randomize their looks, or utilize a  pre-defined look. This is handled with structs of data
                            and usage of soft reference pointers to assets, such as body models and hair.</td>
                        </tr>
                        <tr>
                            <td>Paritioned World</td>
                            <td>While a retro-styled game, CINIS does feature a seamless inter-connected open world, and as such
                            world partition is utilized. This requires game code to remain functional for objects only being loaded as needed,
                            and loose coupling of actors, as well as consistant handling of the Persistant World.</td>
                        </tr>
                        <tr>
                            <td>SteamWorks Integration</td>
                            <td>CINIS features several of the expected features from a Steam game, such as Achievements and tracking of
                            Stats relating to gameplay, such as secrets found..</td>
                        </tr>
                        <tr>
                            <td>Continous Delivery</td>
                            <td>After having configured SteamWorks, a CD pipeline running on GitHub Actions, on a Self-Hosted Runner
                            was setup. This pipeline automatically builds and deploys game builds to a testing branch on Steam, whenever
                            a merge has been made to the games Main Branch. This allows for swift delivery of builds to testers,
                            and reduces errors from manual work.</td>
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
                    <a href="https://store.steampowered.com/app/4586050/CINIS/" class="button special">
                        Steam Page
                    </a>
                </li>
                <li>
                    <a href="https://alexanderlind.itch.io/cinis" class="button special">
                        Itch page
                    </a>
                </li>
                <li>
                    <a href="https://youtu.be/fVLE-0AJY1U" class="button special">
                        YouTube Video
                    </a>
                </li>
            </ul>
        </div>
    </section>
</div>
