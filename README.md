# General_Grid_Layout

An elegant solution for browsers which don't support grid layout. 

## Build

This project depends on Less.js. Detail can be found in [Less.js](http://lesscss.org/).
To generate css file, using `lessc simple_grid.less simple_grid.css`.

## Usage

Similar to the grid layout provided by common framework: 

- `.row` is the wrapper for `.column` 
- In a grid layout, content must be placed within `.column` and only `.column` may be immediate children of `.row`

You can also refer to `example.html` for further information.