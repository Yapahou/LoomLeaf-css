# LoomLeaf-css

LoomLeaf-css is a lightweight, modular CSS utility library designed to facilitate the development of modern web interfaces by providing a consistent set of predefined classes for typography, colors, spacing, shadows, animations, and cursor handling. It allows you to quickly and efficiently style HTML elements without writing custom CSS.

## Download

In your terminal type `npm init` to start a new npm project.

Then type `npm i loomleaf-css` to install the LoomLeaf-css pack.

## Use LoomLeaf

### Link to HTML

To link a HTML file to LoomLeaf put your html file next to the node_modules folder and type ```html <link href="./node_modules/LoomLeaf/LoomLeaf.css" rel="stylesheet"/>``` and if you put it in another directory make sure you just go to the node_modules folder.

### Learn

### first

- open a class `<h1 class"loomleaf-class" >hello world</h1>`
- tap the in class attribute to style your element
### Classes

#### Colors

- c-< your-color>: to change the font color.

- bg-< your-color>: to change the background color.
- **Exemples** : `c-red` ,`c-tomato` ,`c-blue` ,`c-silver`.

#### Display & Layout

- Type `d-<value>` the value is (grid, flex, block, ...).

- Flexbox:
  - to change the flex direction type `flex-<value>`the value can be (row, column, row-reverse, column-reverse).

  - Alignement : justify-center, items-start, etc.

  - Wrap : flex-wrap, flex-nowrap, etc.

#### Spacing
- margin: `m-<n>` the n should be anumber | **Warning**: to use the left margin ...etc you should put after m the first lettre of the direction, ex: `mr-5` the r after m is the right direction.

- padding: it's like the margin but instead of m we put p, ex: `p-3`.

#### The Fonts

- font family: to change the font family tap `ff-1family` there is 10 font

- font weight: to change the font weight tap `fw-<n>` the n value is a number there is 9.

- font size: to change the font size tap `fs-<n>` the n value is a number there is 15.

#### Borders & Shadows

- borders: to put a border to your element type `bd-<value>` there is 6 value (thin, thick, dotted, dashed, rounded, circle)

- shadows: type `shadow-<value>` then a value.

#### Effects & Transitions

- Hover effects: hover:bg-blue, hover-shine, hover-zoom.

- Transitions: transition, transition-colors, fx-fade, fx-slide.

- Filters: blur-sm, brightness-125.

#### Position & Z-Index

- position: type position thene a value ex:`position-absolute` | to use the top and left etc... type the direction then a number ex: `right-1` for all direction there is the number 0 or 1 or 2.

- z-index: type z then (0 or 10 or 20 or 30 or 40 or 50) ex: `z-30`.

#### Cursors

- To use the cursors type cursor then the name of the cursor ex: `cursor-grab`.

#### Animations

- To animate an element type anim then the name of animation ex: `anim-fadein`.

#### Helpers

- Centering : .center-it, .center-absolute.

- Stacking : col-stack, row-stack, wrap-items.

- Overflow : overflow-auto, overflow-x-scroll.

### Importent

Install the IntelliSense extention to autocomplete.

### Final

There is more classes to use there go to node moduls to LoomLeaf folder to LoomLeaf.css