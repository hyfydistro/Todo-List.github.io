# Style Guide

- [x] Typography
- [x] Space
- [x] Color
- [x] Other UI Components


## Typography

- [x] Mobile (S)
- [x] Tablet (M)
- [x] Desktop (L)

**Design Goals**: General Public, Students, Office Worker theme.

Romanticize schedules, bullet-journals, todo lists; Office Romance.

Typeface: Serif, Modern

### Mobile
Apply to *SML Devices || MOBILE VIEW*

**Typeface**
> Notice Alert (*)

Font-family:
    headings:
        h1: Quicksand (-15% tracking)
        h2: Quicksand
        h3: Quicksand
    body-copy: Myanmar Text (+50% tracking)
    other (opt.): n/a
        caption:

**Font Sizes**

Modular Scale: 1.2
Font base: 15px (process: 20px / 1.333)

h1 - 25.92px | 1.728em
h2 - 21.6px | 1.44em
h3 - 18px | 1.2em
p - 15
caption -

Measure:
    - x char
    - width: 288px
Line-height (standard): 22.5px

**Other**

Tracking:
    * -15% for h1, h2, h3
    * +50% for body copy
Letter-spacing:
word-spacing:


### Tablet
Apply to *MED Devices || TABLET VIEW*

**Typeface**

(Same as above.)

**Font Sizes**

Reccoommended: Use em instead of pixels to respect users with screen size lower than 380w px

Modular Scale: 1.2
Font base: 20px

h1 - 34.56px | 1.728em
h2 - 28.8px | 1.44em
h3 - 24px | 1.2em
p - 20px | 1em
caption -

Measure:
    - x char
    - width: 288px
Line-height (standard): 30px

**Other**

(Same as above.)


### Desktop
Apply to *LGE Devices || DESKTOP VIEW*

**Typeface**

(Same as above.)

**Font Sizes**

(same as MED Devices.)

**Other**

(Same as above.)


## Space

*Any new variables should be divisble or multiple of the font base in order for it to be acceptable (in my terms [experimental]).

- [x] Mobile (S)
- [x] Tablet (M)
- [x] Desktop (L)

### Mobile
e.g.
font base = 12px
font base * 1.5 = Line height
12 * 1.5 = 18px (`space-lv-1`)
12 * 1.5 * 1.5 = 40.5px (`space-lv-2`)
12 / 1.5 = (`space-lv-half`)

font base: 15px
line height: 22.5px

`space-quarter`: 6.667
`space-half`: 10
`space-1`: 22.5
`space-2`: 33.75
`space-3`: 50.625
`space-4`: 75.9375
`space-5`: 113.90625

### Tablet

font base: 20px
line height: 30px

`space-quarter`: 8.889px
`space-half`: 13.333px
`space-1`: 30px
`space-2`: 45px
`space-3`: 67.5px
`space-4`: 101.25px
`space-5`: 151.875px

### Desktop

(same as MED Devices.)


### Space Guide

Apply to *SML Devices || MOBILE VIEW*

* `space-lv1`
- Between inputs and CTA buttons

* `space-lv2`
- Between headings


Apply to *MED Devices || TABLET VIEW*

(Same as above.)


Apply to *LGE Devices || DESKTOP VIEW*

(Same as above.)


## Color

[!] Update Template:
    - Exclude back ticks
    - Add $ suffix (?)

`primary-color`:
`secondary-color`:
`accent-color-1`:
`accent-color-2`:


### Primary Color Variations

From light to dark order.

"Ocean Blue"

`primary-color-05`: #EAF5FB (used)
`primary-color-10`: #D5ECF6
`primary-color-20`: #ABD8ED
`primary-color-30`: #80C5E4
`primary-color-40`: #56B2DC
`primary-color-50`: #2C9FD3
`primary-color-65`: #227CA5 (use; unique)
`primary-color-60`: #237FA9
`primary-color-70`: #164F69 (use; main)
`primary-color-80`: #123F54
`primary-color-90`: #09202A


### Secondary Color Variations

From light to dark order.

"Bright Yellow Orange"

`secondary-color-05`: #FCF5E3 (used; main)
`secondary-color-10`: #FAEFD1
`secondary-color-20`: #F5DEA3
`secondary-color-30`: n/a
`secondary-color-40`: n/a
`secondary-color-50`: n/a
`secondary-color-60`: n/a
`secondary-color-70`: n/a
`secondary-color-80`: n/a
`secondary-color-90`: n/a


### Text Color

`text-color-05`: #F2F2F2
`text-color-10`: #E5E5E5
`text-color-20`: #CCCCCC (used)
`text-color-30`: #B2B2B2
`text-color-40`: #999999 (used)
`text-color-50`: #7F7F7F
`text-color-60`: #666666
    - crossed sentence
`text-color-70`: #4C4C4C
`text-color-80`: #333333
`text-color-90`: #191919 (used)
    - body copy

### Information Color

#### Warning Color

warning-color-05: #FCEBE9
warning-color-10: #F9D7D2
warning-color-20: #F2B0A6
warning-color-30: #EC8879
warning-color-40: #E66451 (used; main)
warning-color-50: #DF3820
warning-color-60: #B22D19
warning-color-70: #862213
warning-color-80: #59170C
warning-color-90: #2D0B06

**Sticky Color**

sticky-color-1: #F2878A
sticky-color-2: #FFCC5C
sticky-color-3: #458FC0
sticky-color-4: #88D8B0

## UI Components

### Images

#### Guidelines

e.g.
Targeted Device Width (and Height):

*Small size*

max-width: 576px
height (optional):


*Medium size*

width: 768px
height (optional):


*Large size*

width: 992px
height (optional):


*Extra Large size*

width: 1200px
height (optional):


#### Source Checklist

- [x] icons
    - [x] plus icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [x] font awesome: plus
    - [x] bin icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [x] font awesome: trash-alt
    - [x] more option vertical icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [x] font awesome: ellipsis
    - [x] more option horizontal icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [x] font awesome: ellipsis-h
    - [x] memo / doc icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [ ] font awesome: file
        - [x] font awesome: sticky-note (180deg)
    - [x] color change icon
        - [x] S
        - [ ] M
        - [x] L
    - [x] calender icon
        - [x] S
        - [ ] M
        - [x] L
    - [x] pin icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [x] font awesome: thumbtack
    - [x] pencil icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [x] font awesome: pencil-alt
        - [x] font awesome: edit
    - [x] checkbox icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [x] font awesome 4.7: Check-square-0
    - [x] empty checkbox icon
        - [ ] S
        - [ ] M
        - [ ] L
        - [x] font awesome: square
        - [x] font awesome 4.7: square-0


### Nav Bar

Apply to *SML Devices || MOBILE VIEW*

height: 64 px

L / R Margin: 16 px


### Modules

**Form Task**,
**Edit Task**

Apply to *SML Devices || MOBILE VIEW*

width: auto
height: auto

 L/R Margin: 16px

padding-left: 1-space
padding-right: 1-space
padding-top: 2-space
padding-bottom: 2-space


Apply to *LGE Devices || DESKTOP VIEW*

max-width: 704px
height: auto

padding-left: 1-space
padding-right: 1-space
padding-top: 2-space
padding-bottom: 2-space


### Icons

**Plus "Form Task" Icon**

* From Font Awesome 4.7

Class: `fa fa-plus`
Unicode: `f067`

Color
Default
    - color: #227CA5 (primary-color-65)
    - background-color: #FFFFFF
On-Hover
    - color: #FFFFFF
    - background-color: #227CA5 (primary-color-65)


Apply to *SML Devices || MOBILE VIEW*

width: 16px
height: 16px

Boundary lines / padding: 36w x 36h


Apply to *LGE Devices || DESKTOP VIEW*

width: 22px
height: 22px

Boundary lines / padding: 37w x 37h

Difference from MOBILE VIEW to DESKTOP VIEW
width: +1 px
height: +1 px


**Plus "Add Task" Icon**

* From Font Awesome 4.7

Class: `fa fa-plus`
Unicode: `f067`

Color
Default
    - color: #EAF5FB (primary-color-05)
    - background-color: #164F69 (primary-color-70)
On-Hover
    - color: #237FA9 (primary-color-60)
    - background-color: #EAF5FB (primary-color-05)


Apply to *SML Devices || MOBILE VIEW*

width: 16px
height: 16px

Boundary lines / padding: 36w x 36h


Apply to *LGE Devices || DESKTOP VIEW*

width: 22px
height: 22px

Boundary lines / padding: 37w x 37h

Difference from MOBILE VIEW to DESKTOP VIEW
width: +1 px
height: +1 px


**Pencil Icon**

* From Font Awesome 4.7

Class: `fa fa-pencil`
Unicode: `f040 `

Color
Default
    - color: #666666 (text-color)


Apply to *SML Devices || MOBILE VIEW*

width: 15.1px
height: 16px


Apply to *LGE Devices || DESKTOP VIEW*

width: 16.1px
height: 17px


**Calandar Icon**

* Created

Color
Default
    - color: #666666 (text-color)


Apply to *SML Devices || MOBILE VIEW*

[!] Dimension may change if using fontAwesome CDN

width: 20.8px
height: 22px


Apply to *LGE Devices || DESKTOP VIEW*

width: +1px
height: +1px


**Memo Icon**

* From Font Awesome 4.7

Class: `fa fa-file`
Unicode: `f15b`

Color
Default
    - color: #666666 (text-color)


Apply to *SML Devices || MOBILE VIEW*

width: 13.3px
height: 16px


Apply to *LGE Devices || DESKTOP VIEW*

width: +1px
height: +1px


**Pin / Thumbtack Icon (Inside Module)**

* From Font Awesome 4.7

Color
Default
    - color: #666666 (text-color)


Apply to *SML Devices || MOBILE VIEW*

width: 13.2px
height: 18px


Apply to *LGE Devices || DESKTOP VIEW*

width: +1px
height: +1px


**Pin / Thumbtack Icon (Outside Module)**

* From Font Awesome 4.7

Class: `fa fa-thumb-tack`
Unicode: `f08d`

Color
Default
    - color: #E66451 (warning-color)


Apply to *SML Devices || MOBILE VIEW*

width: 13.1px
height: 17.5px


Apply to *LGE Devices || DESKTOP VIEW*

width: +1px
height: +1px

**Color Change Icon**

* Created

Color
Default
    - color #1: #666666 (text-color)
    - color #1: #CDCDCD (unique)


Apply to *SML Devices || MOBILE VIEW*

width: 22px
height: 22px


Apply to *LGE Devices || DESKTOP VIEW*

width: +1px
height: +1px


> Other Notes

Alternatively, we could use `paint-brush` from Font Awesome 4.7

**Sticky Color Circle Icon**

* Div Element

Color
Default
    - color #1: #F2878A (sticky-color)
    - color #2: #FFCC5C (sticky-color)
    - color #3: #458FC0 (sticky-color)
    - color #4: #88D8B0 (sticky-color)
    - background-color: #CCCCCC (text-color)
Active
    - background-color: #164F69 (primary-color)


Apply to *SML Devices || MOBILE VIEW*

width: 44px
height: 44px


Apply to *LGE Devices || DESKTOP VIEW*

width: +1px
height: +1px


**Sticky Color Rectange (on list line) DIV Element**

* Div Element

Color
Default
    - color #1: #F2878A (sticky-color)
    - color #2: #FFCC5C (sticky-color)
    - color #3: #458FC0 (sticky-color)
    - color #4: #88D8B0 (sticky-color)

width: 22.5px
height: 36px-46px ([!] May vary depending on main list height line and Responsive Design)


### CTA

**"+ Add Task" Text Input**

Effects:
Selected
    - border change color: #2C9FD3 (primary-color-50)
Unselected
    - bottom border default color : #999999 (text-color-40)

Apply to *SML Devices || MOBILE VIEW*

width: block - L/R Margins (16px)
height: 33px


Apply to *LGE Devices || DESKTOP VIEW*

width: max-width (576px) - L/R Margins (32px)
height: 45px


**"+ Add Task" Text Input (Inside Module)**

Effects:
Selected
    - border change color: #2C9FD3 (primary-color-50)
Unselected
    - bottom border default color : #999999 (text-color-40)

Apply to *SML Devices || MOBILE VIEW*

width: block - L/R Margins (1-space)
height: 33px


Apply to *LGE Devices || DESKTOP VIEW*

width: L/R Margins (1-space)
height: 45px


**Trash Icon**

* From Font Awesome 4.7

Class: `fa fa-trash`
Unicode: `f1f8`

Color
Default
    - color: #666666 (text-color)
    - background-color: n/a
On-Hover
    - color: #164F69 (primary-color)
    - background-color: #EAF5FB (primary-color)


Apply to *SML Devices || MOBILE VIEW*

width: 14.7px
height: 16px

Boundary lines / padding: 46w x 46h


Apply to *LGE Devices || DESKTOP VIEW*

width: 15.6px
height: 17px

Boundary lines / padding: 56w x 56h


**More Options Horizontal "..." Icon**

* From Font Awesome 4.7

Class: `fa fa-ellipsis-h`
Unicode: `f141`

Color
Default
    - color: #666666 (text-color)
    - background-color: n/a
On-Hover
    - color: #164F69 (primary-color)
    - background-color: #EAF5FB (primary-color)


Apply to *SML Devices || MOBILE VIEW*

width: 16px
height: 4px

Boundary lines / padding: 46w x 46h


Apply to *LGE Devices || DESKTOP VIEW*

width: 16px
height: 4px

Boundary lines / padding: 56w x 56h (?)


**Checkbox - empty**

* From Font Awesome 4.7

Class: `fa fa-square-o`
Unicode: `f096 `

Color
Default
    - color: #CCCCCC (text-color)
On-Hover
    - cursor: pointer


Apply to *SML Devices || MOBILE VIEW*

width: 24px
height: 24px

Boundary lines / padding: 46w x 46h (?)


Apply to *LGE Devices || DESKTOP VIEW*

width: 24px
height: 24px

Boundary lines / padding: 56w x 56h (?)

**Checkbox - checked (tick mark) ONLY**

* From Font Awesome 4.7

Class: `fa fa-check`
Unicode: `f00c`

or...

Class: `fa-check-square-o`
Unicode: `f046`

Border Color
Default
    - color: #CCCCCC (text-color)
On-Hover
    - cursor: pointer

Checkmark Color
Default
    - color: #2C9FD3 ($primary-color-50)


Apply to *SML Devices || MOBILE VIEW*

Checkmark Color
width: 24.9px
height: 19px

Border
width: 24px
height: 24px

Boundary lines / padding: 46w x 46h (?)


Apply to *LGE Devices || DESKTOP VIEW*

(same as above.)

Boundary lines / padding: 56w x 56h (?)


**"Pin To The Top" Toggle**

"On" Color
Default
    - background-color: #2C9FD3 (primary-color)
    - Circle color: #FFFFFF

"Off" Color
Default
    - background-color: #CCCCCC (text-color)
    - Circle color: #FFFFFF


Apply to *SML Devices || MOBILE VIEW*

width: 61.4px
height: 36px

Boundary lines / padding: 46w x 46h


Apply to *LGE Devices || DESKTOP VIEW*

width: 61.4px
height: 36px

Boundary lines / padding: 56w x 56h (?)


#### Buttons

**'+ Add Task' Button**,
**'Clear List' Button**

Apply to *SML Devices || MOBILE VIEW*

Color
    Default
        - text color:
        - background color:

Padding
Based on H3 height (dimension, not "font size") i.e. 14 px
height: +28px (2x of font dimension height)
width: +56px (4x) i.e. 28px each side

Effects
Click-on, Focus
    - Background color change (see above)
Default
    - Background color default color (see above)

Apply to *MED Devices || TABLET VIEW* and *LGE Devices || DESKTOP VIEW*

Padding
Based on H3 height (dimension, not "font size") i.e. 17 px
height: +34px (2x of font dimension height)
width: +68px (4x) i.e. 28px each side

Effects
Click-on, Focus
    - Background color change (see above)
Default
    - Background color default color (see above)
