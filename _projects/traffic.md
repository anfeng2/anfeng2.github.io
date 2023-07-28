---
layout: page
title: Traffic
description: The Implications of Bridges on Bay Area Traffic Predictions Before and After COVID Lockdowns
img: assets/img/heatmap.png
importance: 1
category: work
related_publications: 
---

<div class="post title font-weight-bold"> Open-Ended EDA </div>

From the two histograms below, we saw that the mean travel time decreased after COVID-19 restrictions began in San Francisco. It went from a max mean travel time of around 3750 seconds to a max mean travel time of around 2750 seconds. We thought that a potential reason for this was because less people are commuting to work, since most people are working from home with the COVID-19 restrictions going on in San Francisco. We then decided to plot out the differences in mean travel time from Hayes Valley pre and post COVID-19 restrictions to see which areas had a decrease/increase in mean travel time. Negative changes in travel time (blue/purple) represents a decrease in mean travel time from Hayes Valley and positive changes in travel time (light green, yellow) represents an increase in mean travel time from Hayes Valley.

In addition, we noticed that the north most part of the peninsula, around San Rafael, saw the greatest increase in travel time after COVID restrictions were put in place. This was a jarring observation because most of the other areas with data saw little change, hovering around zero difference in travel time (green), or a decrease, especially to areas outside of the immediate metropolitan area (East and South bay). We found it interesting that even though traveling to the Oakland and San Rafael areas both require crossing a bridge over the bay, only San Rafael saw an increase in travel times while the areas nearest to Oakland saw a decrease.


<div class="row">
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/img/hist_of_avg_travel_time.png" title="histogram of average travel time" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-2 mt-md-0">
        {% include figure.html path="assets/img/heatmap.png" title="heatmap of the peninsula" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, histograms of average travel time before and after lockdown. Right, a heatmap of the peninsula.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
