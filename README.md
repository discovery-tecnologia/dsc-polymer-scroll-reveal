# dsc-polymer-parallax

[![Build Status](https://travis-ci.org/discovery-tecnologia/dsc-polymer-parallax.svg?branch=master)](http://travis-ci.org/#!/discovery-tecnologia/dsc-polymer-parallax)

Sections with background image with parallax effect when page scrolling.

Custom content.

## Demo

```
git clone https://github.com/discovery-tecnologia/dsc-polymer-parallax.git
cd dsc-polymer-parallax
bower install
node install -g polymer-cli
polymer serve
```
Open browser: http://localhost:8080/components/dsc-polymer-parallax/demo/

## Usage

Install with:

```
$ bower i https://github.com/discovery-tecnologia/dsc-polymer-parallax.git --save
```

Example usage:

```html
<dsc-polymer-parallax background="images/img.jpg">
  <h1>Section title</h1>
  <p>Nam mattis porta mattis. Donec et neque scelerisque, pretium arcu sed, vehicula diam. Nam a arcu eu sapien porta<br>posuere id id arcu. Fusce rhoncus erat ut nisl pharetra.</p>
  <a href="#">View more</a>
</dsc-polymer-parallax>
```

## API

| Property       | Description                    | Default       |
|:---------------|--------------------------------|---------------|
| background     | optional "background" attribute of the section defines the background image. | null |

The content can be any HTML element or other polymer component.

| Custom property |	Description                       | Default |
|:----------------|-----------------------------------|---------|
| --dsc-polymer-parallax | Overhide element style     | {}      |
