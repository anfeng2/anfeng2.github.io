---
layout: page
title: World
description: Built a 2D tile-based world exploration engine with the ability to load, replay, and save the world generated from a seed. Ensured that each new iteration of a world generates a randomized maze with randomized themes, randomized hallways, and randomized rooms where an avatar can move with WASD 
img: assets/img/project_world/home_screen.png
importance: 2
---


<div class="row">
    {% include figure.html path="assets/img/project_world/home_screen.png" title="black screen with N, L, R, and Q" class="img-fluid rounded z-depth-1" %}
</div>
<div class="caption"> 
    Home Page
</div>

#### Themes

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_world/water.png" title="blue maze" class="img-fluid rounded z-depth-1" %}
        <div class="caption"> 
            Ocean
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_world/grass.png" title="green maze" class="img-fluid rounded z-depth-1" %}
        <div class="caption"> 
            Prairie
        </div>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/project_world/desert.png" title="brown maze" class="img-fluid rounded z-depth-1" %}
        <div class="caption"> 
            Desert
        </div>
    </div>
</div>

###### Each new iteration of a game generates a randomized maze with:
- randomized themes
- randomized hallways
- randomized rooms

#### Commands
- New Game (N) - To generate a new world, type in “N” and then you choice of a sequence of numbers and finally “S” *(can either be uppercase or lowercase)*
- Load Game (L) - Loads your last saved game
- Replay (R) - Replays your last saved game
- Quit (Q) - Exits game
- :q - Saves the game
- WASD - Moves up, left, down, right
- Move the mouse over specific tiles and it’ll show what that tile is 

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/project_world/new_game_demo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption"> 
    Generating a New World
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/project_world/moving_demo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption"> 
    Moving using WASD
</div>

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.html path="assets/video/project_world/mouse_hover_demo.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
    </div>
</div>
<div class="caption"> 
    Hovering over different tiles using the mouse tells us what part of the maze each tile is
</div>


