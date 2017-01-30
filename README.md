# dsc-polymer-parallax

[![Build Status](https://travis-ci.org/discovery-tecnologia/dsc-polymer-scroll-reveal.svg?branch=master)](http://travis-ci.org/#!/discovery-tecnologia/dsc-polymer-scroll-reveal)

Provides animation effect when scrolling page. Elements are displayed when they enter the view port.

## Demo

```
git clone https://github.com/discovery-tecnologia/dsc-polymer-scroll-reveal.git
cd dsc-polymer-scroll-reveal
bower install
node install -g polymer-cli
polymer serve
```
Open browser: http://localhost:8080/components/dsc-polymer-scroll-reveal/demo/

## Usage

Install with:

```
$ bower i https://github.com/discovery-tecnologia/dsc-polymer-scroll-reveal.git --save
```

Example usage:

```html
<dsc-polymer-scroll-reveal>
  <h1>Section title</h1>
  <p>Nam mattis porta mattis. Donec et neque scelerisque, pretium arcu sed, vehicula diam. Nam a arcu eu sapien porta<br>posuere id id arcu. Fusce rhoncus erat ut nisl pharetra.</p>
  <a href="#">View more</a>
</dsc-polymer-scroll-reveal>
```

## API

| Property       | Description                    | Default       |
|:---------------|--------------------------------|---------------|
| origin         | Element deslocation origin. Values: 'bottom', 'left', 'top', 'right' | 'bottom' |
| distance       | Can be any valid CSS distance, e.g. '5rem', '10%', '20vw', etc       | '100px'  |
| repeat         | Repeat effect when the element appears again | false    |

The content can be any HTML element or other polymer component.

| Custom property |	Description                       | Default |
|:----------------|-----------------------------------|---------|
|                 |                                   | {}      |
