# Frame

A starting point for any project.

## Requirements

- SASS

## Usage

`git clone https://github.com/leonp/frame.git`

## How it works

- Calls the Pure CSS buttons, form and tables modules
- Simple CSS reset
- Sets font size and line height
- Sets some simple classes: .hide, .clearfix
- Sets a simple 6 column % grid at widescreen breakpoint

## SASS imports

`style.scss` imports:

- `_base.scss`
- `_grid.scss`

## SASS variables

### Size and ryhthm

`$base-line-height: 1.4;`
`$widescreen-font-size: 125%;`

### Breakpoint

`$widescreen-breakpoint: "screen and (min-width: 900px)";`

### Font

`$primary-font-stack: 'Fira Sans', sans-serif;`
`$secondary-font-stack: 'Droid Serif', georgia, serif;`

### Colours

`$black: #000;`
`$dark: #444;`
`$light: #FFF;`
`$grey: #AAA;`
`$lgrey: #F9F9F9;`
`$highlight: #FFD000;`
`$link: #0000FF;`
`$visited: #7F7FFF;`
`$active: #000;`
`$hover: #FFD000;`