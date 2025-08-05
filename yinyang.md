---
layout: page
title: YinYang Engine
description: A 3D rendering engine made in C#
image: assets/images/YinYang_Thumb.png
show_tile: true
nav-menu: false
---

<div id="main" class="alt">

<section id="one">
	<div class="inner">
		<header class="major">
			<h1>YinYang Engine</h1>
		</header>

<p>
    (April, 2025)<br>
    A 3D rendering engine made from scratch in C# using OpenTK, made as part of my Computer Graphics course during my Bachelor studies. 
<p>

<section id="two">
	<div class="inner">
		<header class="major">
			<h2>Showcase</h2>
		</header>

<p>
    <iframe width="1280" height="720"
    src = "https://www.youtube.com/embed/ogE9NTSlm88">
    </iframe>
<p>

<section id="three">
	<div class="inner">
		<header class="major">
			<h2>About YinYang</h2>
		</header>

<p>
    'YinYang Engine' was made in about a month, iterating on a lighting and model loading engine (Called Light & Shadow). YinYang extended the model loading, scene system, and graphic features to make even more realistic scenes. Also supporting basic run-time logic, such as linear animation on objects or cameras, as well as  a basic spherical collision system. This was made in partnership with my classmate Mpho, where I was responsible for lighting shaders, normal mapping, reflections, scene editor tools and colliders.<br><br> Graphical features include: <br>

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
                    <td>Blinn-Phong shading</td>
                    <td>Allows for realistic and cheap lighting and highlights on models.</td>
                </tr>
                <tr>
                    <td>Normal mapping</td>
                    <td>Gives models extra detail and interacts beautifully with lights.</td>
                </tr>
                <tr>
                    <td>Baked and Dynamic Cube map reflections</td>
                    <td>Cube map reflections allows for highly accurate and performant reflections. Has a update frequency, as well as static bake for performance.</td>
                </tr>
                <tr>
                    <td>Basic PBR for reflective surfaces</td>
                    <td>Able to control the reflection blurring with a roughness setting for materials.</td>
                </tr>
                <tr>
                    <td>Dynamic or static lighting</td>
                    <td>Scenes can be lit by light sources dynamically, or a light can be static to save on resources</td>
                </tr>
                <tr>
                    <td>Spot lights, point lights, directional lights</td>
                    <td>Many types of lights, all to make scenes more immersive</td>
                </tr>
                <tr>
                    <td>Basic particle rendering</td>
                    <td>Adding extra life and motion to scenes using compute shaders.</td>
                </tr>
                <tr>
                    <td>Bloom post processing effect</td>
                    <td>Makes scenes look less flat, and gives glowing objects more life</td>
                </tr>
            </tbody>
            <tfoot>
                <tr>
                    <td colspan="2"></td>
                </tr>
            </tfoot>
        </table>
    </div>

    Many many thanks to my project partner Mpho for the great help and dedication during this project!
<p>

<section id="two">
	<div class="inner">
		<header class="major">
			<h1>Links</h1>
		</header>

<ul class="actions">
<li><a href="https://github.com/AlexanderLind98/YinYang" class="button special">Github page</a></li>
<li><a href="https://youtu.be/ogE9NTSlm88" class="button special">Video on YouTube</a></li>
</ul>   

