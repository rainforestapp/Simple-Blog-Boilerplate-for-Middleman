This is a Middleman [project template](http://middlemanapp.com/getting-started/#toc_6).

This is for a blog or blog-like sites (ie. documentation). It's intended to have just the right amount of default styling. Most blog boilerplates are either too prescriptive or too unstructured in their layouts. Both extremes make you do unneccessary front-end work to get up and running. This is a happy medium:

![Screenshot](http://f.cl.ly/items/1Q0d0b3u3l1W0L3V1r3v/Screen%20Shot%202013-11-08%20at%2012.36.25.png)

## What does it come with?
Structure:
- Simple blog
- Pagination
- XML feed
- Tags
- Simple fluid layout with sidebar
- Minimal styling to be easily customizeable ([screenshot](http://cl.ly/image/460610072B2y))

Defaults:
- HAML
- SCSS
- Compass
- Susy for grids


## Installation:

To install middleman-blog-project-template as a template available to your user:

1. Clone the Git repository into ``~/.middleman``, like so ``git clone https://github.com/rainforestapp/middleman-blog-project-template.git ~/.middleman/blog-boilerplate```

## Setup: 

1. Use the new template argument for the ```middleman init``` command within your project folder: ``middleman init my_new_project --template=blog-boilerplate``

## Using Middleman:

1. Ensure you have Ruby + bundler installed
2. Run ``bundle install`` from within your project directory
3. Run ``bundle exec middleman server`` and go to http://0.0.0.0:4567/
