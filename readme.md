# Creates a css file with css utility classes

## Source is css-utilities.js

## Run generate to create the css-utilities.css file.

Settings in css-utilties.js

* Breakpoints
* Prefixes for breakpoint classes
    * mobile: no prefix
    * 576: sm:
    * 768: md:
    * 992: lg:
    * 1200: xl:

* Default spacing (code actually uses rems)
    * 0: 0
    * 1: 4px
    * 2: 8px
    * 3: 16px;
    * 4: 24px;
    * 5: 48px
    * 6: 64px
    
e.g. p-0 no padding

pt-3 md:pt-0  Top padding of 16px for mobile. No padding at 768 & above.

m-x: left & right

m-y: top & bottom 

* Display & flex
  * d-none 
  * d-flex 
  * d-block 
  * d-inline 
  * d-inline-block 
  * flex-row 
  * flex-column 
  * flex-row-reverse 
  * flex-column-reverse 
  * flex-wrap 
  * flex-nowrap 
  * justify-between 
  * justify-start 
  * justify-center 
  * justify-end 
  * align-content-start 
  * align-content-center 
  * align-content-end 
  * align-items-stretch 
  * align-items-start 
  * align-items-center 
  * align-items-end 
  * align-self-start 
  * align-self-center 
  * align-self-end 

  eg 
  visible on desktop: d-none lg:d-flex
  visible on mobile only: sm:d-none

* Some typography
    * text-left
    * text-center
    * text-right
    * text-bold
    * text-normal
    * text-italic
    * text-lowercase
    * text-uppercase

* Width & height percentages
    * 25, 33, 50, 66, 75, 100
    * eg w-75, mh-100

* Responsive images    
    * img-responsive 
    * img-height-full 
    * img-height-auto 
    * img-contain 
