# toggleSwitch

## Installation

```sh
bower install trowel-switch
```

This is some css that allow you to style (in CSS3 and HTML5) the `input type=checkbox` elements as a toggle switch

## Getting Started
To enjoy it just link to your template or to your stylesheet the `css/style.css` file.

You can also use the less file available at `less/style.less`. With this file you can overide easily customize the Less variables listed below in order to define colors, sizes and more.

## Bower Usage
Install and manage Toggle Switch using Bower.
`$ bower install toggle-switch`

## The Markup
In order to enjoy the css designed, you just need an `input type=checkbox` with the class `.toggleSwitch` and just after as direct sibling a `label` element. Don't forget to link the label to you checkbox name or id.

###basic
     <input class="toggleSwitch" id="example-1" type="checkbox"> 
     <label for="example-1">Label</label> 

###checked
     <input class="toggleSwitch" id="example-2" type="checkbox" checked> 
     <label for="example-2">Label</label>

###disabled
     <input class="toggleSwitch" id="example-3" type="checkbox" disabled> 
     <label for="example-3">Label</label>

###checked & disabled
     <input class="toggleSwitch" id="example-4" type="checkbox" disabled checked> 
     <label for="example-4">Label</label>
     
## Less Variables
The variables are divided in two categories, the `modules` and the `themes`. The module variables change the structure and the behave of the component in your template. The theme just change the look without size or layout consequences. Those two kinds of variables are called `parameters` and you can find them in `/less/parameters`.

* @toggleSwitch-container_transitionDuration: 100ms
* @toggleSwitch-container_transitionAnimation: ease
* @toggleSwitch-container_width: 50px
* @toggleSwitch-container_height: 30px
* @toggleSwitch-container_borderWidth: 0
* @toggleSwitch-container_backgroundColor: #5e5d5d
* @toggleSwitch-container_backgroundColor-_checked: #e36566
* @toggleSwitch-container_borderColor: transparent
* @toggleSwitch-container_boxShadow: 0
* @toggleSwitch_opacity-_disabled: 0.25
* @toggleSwitch-button_margin: 2px
* @toggleSwitch-button_widthDiff-_transition: 10px
* @toggleSwitch-button-backgroundColor: white
* @toggleSwitch-button_boxShadow: 0 2px 5px 0 fade(#333, 25%)
* @toggleSwitch-button_animationDuration: 500ms;
* @toggleSwitch-label_marginLeft: 10px
* @toggleSwitch-label_marginRight: 0

designed by Clément Menant and Loïc Goyet for AppVentus. with love from Nantes
