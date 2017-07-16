# Building an Image Carousel Element with Polymer 2.0

These are the resource files needed for the [Building an Image Carousel Element with Polymer 2.0](https://codelabs.developers.google.com/codelabs/polymer-2-carousel/) codelab.

In this codelab, you’ll learn how to build a simple image carousel element with Polymer 2.0. You’ll learn how to use ES2015 syntax to write a Polymer 2.0 element, changes in Custom Elements V1 and Shadow DOM V1, using mixins to factor out common code, and considerations to make when designing your element’s API.

`The finished and enhanced my-caroussel Element is defined in the ./work folder`

#### Enhancement
	1. add custom-style
	2. add  autoscroll  <autoscroll>
	3. add  autoscroll interval <interval=3000>
   	3.1. increase interval by 1000
		3.2. decrease interval by 1000
  4. add icons for jumping to the first/last images

#### API

next_image()	
previous_image()
increase()
decrease()
first_image()
last_image()


## Clone it

  git clone  https://github.com/PaulMatencio/polymer-2-caroussel

## Installation

 The finished and enhanced my-caroussel element is  ./work folder   


 	`cd work`
 	`bower install`

## Demo

	`cd  work`
	`polymer serve`


## Examples


```html
<my-caroussel>
  <!--  Lazy-load images -->
  <img data-src="https://app-layout-assets.appspot.com/assets/bg1.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg2.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg3.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg4.jpg">
</my-caroussel>

<my-caroussel autoscroll>
  <!--  default autoscrolling interval=3000 -->
  <img data-src="https://app-layout-assets.appspot.com/assets/bg1.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg2.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg3.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg4.jpg">
</my-caroussel>

<my-caroussel autoscroll interval=2000 actions_bar>
  <!--  autoscrolling interval= 3000 actions_var -->
  <img data-src="https://app-layout-assets.appspot.com/assets/bg1.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg2.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg3.jpg">
  <img data-src="https://app-layout-assets.appspot.com/assets/bg4.jpg">
</my-caroussel>
```
