# Pendeza

Pendeza, the intuitive css framework.

It is entirely written in [sass](https://sass-lang.com).

---

### Why Pendeza?

- Intuitive
- Lightweight
- Build web pages faster
- Written in [sass](https://sass-lang.com)
- Highly customizable
- Multiple themes to pick
- Good documentation
- Uses modern css features

---

### Getting started

###### cdn

pendeza.min.css
```css
<link href="https://res.cloudinary.com/mkoloni/raw/upload/v1654776537/pendeza_hkqoex.css" rel="stylesheet">
```
pendeza.css
```css
<link href="https://res.cloudinary.com/mkoloni/raw/upload/v1654776537/pendeza_hkqoex.css" rel="stylesheet">
```

###### git clone
```sh
git clone https://github.com/mkoloni/pendeza.git
```

###### npm
```sh
npm install pendeza
```
---

### Example

Lorem ipsum dolor sit amet, officia excepteur ex fugiat reprehenderit enim labore culpa sint ad nisi Lorem pariatur mollit ex esse exercitation amet.

sample:

```html
<header class="wrapper backg-color:purple">
  <h1 class="title text-transform:capitalize">Lorem</h1>
  <p class="lead-text color:green font-family:lato"> Lorem ipsum dolor sit amet, officia excepteur ex fugiat reprehenderit enim labore culpa sint ad nisi Lorem pariatur mollit ex esse exercitation amet. </p>
  <button class="btn">lorem</button>
</header>
```
---

### Browser Support

Pendeza is compatible with the following browser.

- Chrome
- Firefox
- Edge
- Safari
- Opera

---

### Classes

Alert
- alert
  - alert-wrapper
    - alert-title
    - alert-subtitle
    - alert-text
  - alert-toggle

Animation
- fade
- spin
- bounce
- pulse
- animation-iteration-count:1
- animation-iteration-count:10
- animation-iteration-count:infinite

Background
- backg-color:primary
- backg-color:secondary
- backg-color:success
- backg-color:danger
- backg-color:warning
- backg-color:muted
- backg-color:dark
- backg-color:light
- backg-color:blue

Border
- border
- border-style:none
- border-style:dotted
- border-style:dashed
- border-style:solid
- border-style:groove
- border-style:ridge
- border-style:double
- border-style:inset
- border-style:outset
- border:1
- border:1.5
- border:15
- border:primary
- border:primary:hover
- border:primary:focus
- border-top-radius:1
- border-bottom-radius:1
- border-top-left-radius:1
- border-top-right-radius:1
- border-bottom-left-radius:1
- border-bottom-right-radius:1

Bottom
- bottom:0
- bottom:0.5
- bottom:30
- bottom:auto

Button
- btn
- btn:link
- btn.active
- btn.disabled
- btn-group
- btn-group-item

Box
- box
  - box-wrapper
    - box-title
    - box-subtitle
    - box-text
    - box-image
    - box-video
- box-group
- box-group-item

Carousel
- carousel
  - carousel-item
  - carousel-item-slide

Cursor
- cursor:help
- cursor:wait
- cursor:crosshair
- cursor:not-allowed
- cursor:zoom-in
- cursor:zoom-out
- cursor:grab
- cursor:auto
- cursor:progress
- cursor:pointer
- cursor:none

Display
- dis:block
- dis:none
- dis:flex
- dis:grid
- dis:inline
- dis:inline-block
- dis:inline-flex
- dis:table

Dropdown
- dropdown
  - dropdown-item
- dropdown-show

Dropend
- dropend
  - dropend-item
- dropend-show

Dropstart
- dropstart
  - dropstart-item
- dropstart-show

Dropup
- dropup
  - dropup-item
- dropup-show

Embed
- img-responsive
- video-responsive
- circle
- oval
- img-circle
- img-oval

Flex
- flex-wrap:wrap
- flex-wrap:wrap-reverse
- flex-direction:row
- flex-direction:column
- justify-content:flex-start
- justify-content:center
- justify-content:flex-end
- order:1
- order:12

Float
- float:left
- float:right
- float:none
- clear:both

Footer
- footer
  - footer-wrapper
    - footer-brand
    - footer-button
    - footer-input

Form
- label
- input
- input-success
- input-warning
- input-danger
- input.active
- input.disabled
- message-success
- message-warning
- message-error
- message-success.message-show

Pendeza Grid
- row
  - column
  - column:4
  - column:8

Height
- h:0
- h:0.5
- h:30
- h:10%
- h:100%
- h:25vh
- h:50vh
- h:75vh
- h:100vh
- h:125vh
- h:150vh

Left
- left:auto
- left:0
- left:0.5
- left:30
- left:10%
- left:100%

List
- list
  - list-item
- list:unstyled
- list:disc
- list:decimal
- list:circle
- list:square
- list:style-position:inside
- list-style-position:outside

Margin
- m:auto
- m:0
- m:0.5
- m:30
- m-top:0
- m-bottom:0
- m-left:0
- m-right:0
- m-x:0
- m-y:0

Modal
- modal
  - modal-wrapper
    - modal-title
    - modal-subtitle
    - modal-text
    - modal-toggler
- modal-show

Panel
- panel
  - panel-wrapper
    - panel-brand
    - panel-button
    - panel-input

Notepad
- notepad
  - notepad-text
- notepad.notepad-primary

Notification
- notification
  - notification-wrapper
    - notification-title
    - notification-subtitle
    - notification-text

Opacity
- opac:0.1
- opac:0.9
- opac:1
- opac:1:hover
- opac:1:focus
- opac:10%
- opac:100%
- opac:10%:hover
- opac:10%:focus

Overflow
- overflow:scroll
- overflow:hidden
- overflow:visible
- overflow:auto
- overflow-x:scroll
- overflow-x:hidden
- overflow-x:visible
- overflow-x:auto
- overflow-y:scroll
- overflow-y:hidden
- overflow-y:visible
- overflow-y:auto

Padding
- p:auto
- p:0
- p:0.5
- p:30
- p-top:0
- p-bottom:0
- p-left:0
- p-right:0
- p-x:0
- p-y:0

Pagination
- pagination
- pagination-item
- pagination-item.active
- pagination-item.disabled

Parallax
- parallax
- parallax-item

Position
- pos:static
- pos:relative
- pos:absolute
- pos:fixed
- pos:sticky
- sticky-top
- sticky-bottom
- fixed-top
- fixed-bottom

Progess Bar
- progress-bar
  - progress-bar-meter
  - progress-bar-meter.fill-10%
  - progress-bar-meter.fill-100%
  - progress-bar-meter.fill-100%.slow
  - progress-bar-meter.fill-100%.fast
  - progress-bar-meter.fill-100%.slower
  - progress-bar-meter.fill-100%.faster

Responsive
- responsive

Right
- right:auto
- right:0
- right:0.5
- right:30
- right:10%
- right:100%

Shadow
- shadow
- shadow:extrasmallX2
- shadow:extrasmall
- shadow:small
- shadow:medium
- shadow:large
- shadow:extralarge
- shadow:extralargeX2
- shadow:none
- shadow:large:hover
- shadow:large:focus

Sidebar
- sidebar
  - sidebar-title
  - sidebar-subtitle
  - sidebar-toggler
- sidebar-show

Table
- table
- table-responsive

Text
- lead-text
- text-link
- font-family:sans-serif
- font-family:serif
- font-family:helvetica
- font-family:monospace
- font-family:roboto
- font-family:montserrat
- font-family:lato
- font-family:poppins
- font-family:oswald
- font-family:dancing_script
- font-size:0.5
- font-size:3
- text-align:left
- text-align:center
- text-align:right
- text-align:justify
- text-transform:uppercase
- text-transform:lowercase
- text-decoration:underline
- color:primary
- color:primary:hover
- color:primary:focus
- letter-spacing:normal
- letter-spacing:1
- letter-spacing:15
- line-height:10%
- line-height:200%
- line-break:loose
- line-break:normal
- line-break:strict
- line-break:anywhere

Title
- h1
- h2
- h3
- h4
- h5
- h6
- title
- subtitle

Tooltip
- tooltip
- tooltip.primary

Top
- top:0
- top:0.5
- top:30
- top:auto

Width
- w:0
- w:0.5
- w:30
- w:10%
- w:100%
- w:25vw
- w:50vw
- w:75vw
- w:100vw
- w:125vw
- w:150vw

Wrapper
- wrapper
- wrapper:responsive
- wrapper:extrasmallX2
- wrapper:extrasmall
- wrapper:small
- wrapper:large
- wrapper:extralarge
- wrapper:extralargeX2

Z Index
- z-index:100
- z-index:200
- z-index:1000
# pendeza
