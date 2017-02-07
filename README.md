# &#60;dsc-polymer-scroll-reveal&#62;

[![Build Status](https://travis-ci.org/discovery-tecnologia/dsc-polymer-scroll-reveal.svg?branch=master)](http://travis-ci.org/#!/discovery-tecnologia/dsc-polymer-scroll-reveal)

Provides animation effect when scrolling page. Elements are displayed when they enter the view port.

## Demo

```
$ git clone https://github.com/discovery-tecnologia/dsc-polymer-scroll-reveal.git
$ cd dsc-polymer-scroll-reveal
$ npm install
$ node install -g polymer-cli
$ polymer serve
```
Open browser: http://localhost:8080/components/dsc-polymer-scroll-reveal/demo/

## Usage

Install with:

```
$ bower i dsc-polymer-scroll-reveal --save
```

Example usage:

```html
<dsc-polymer-scroll-reveal repeat distance="500px" scale="1" origin="right" delay-show="0" delay-hide="0.5" time-show="1.5" time-hide="0.5">
  <h1>Section title</h1>
  <p>Nam mattis porta mattis. Donec et neque scelerisque.</p>
</dsc-polymer-scroll-reveal>
```

## API

| Property        | Description                    | Default       |
|:----------------|--------------------------------|---------------|
| origin          | Element deslocation origin. Values: 'bottom', 'left', 'top', 'right' | 'bottom' |
| distance        | Distance that the element must travel to the final position. Can be any valid CSS distance, e.g. '5rem', '10%', '20vw', etc. | '200px' |
| animation       | Specify the Speed Curve of the Animation. Values: 'ease', 'linear', 'ease-in', 'ease-out', 'ease-in-out'  | 'ease' |
| delayShow       | Delay time in secounds to start animation of reveal | 0 |
| delayHide       | Delay time in secounds to start animation of hiding | 0 |
| timeShow        | Duration time in seconds of the reveal animation    | 1 |
| timeHide        | Duration time in seconds of the hiding animation    | 1 |
| repeat          | Repeat effect when the element appears again        | false |
| scale           | Initial scale of element to animation. (0, 0.5, 1, 1.5 ...) | 1 |
| rotate-graus    | Rotation degrees, between 0 and 100.                | 0 |
| rotateDirection | Rotate direction. Represents sense of the clock, 'backward' or 'forward' | 'forward' |

The content can be any HTML element or other polymer component.

| Custom property                 |	Description                       | Default |
|:--------------------------------|-----------------------------------|---------|
| --scroll-reveal                 | Host element style                | {}      |
| --scroll-reveal-wrapper         | Wrapper when hide style           | {}      |
| --scroll-reveal-wrapper-visible | Wrapper when show style           | {}      |

## Test

Check sintax and execute selenium tests.

```
$ npm test
```

## TODO

 * tests
