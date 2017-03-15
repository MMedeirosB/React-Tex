
[![Build Status](https://travis-ci.org/dhruv004/React-Tex.svg?branch=master)](https://travis-ci.org/dhruv004/React-Tex)
[![npm version](https://badge.fury.io/js/react-tex.svg)](https://badge.fury.io/js/react-tex)
[![dependencies Status](https://david-dm.org/boennemann/badges/status.svg)](https://david-dm.org/boennemann/badges)


# React-Tex

## Install

```sh
$ npm install --save react-tex
```

## Using

1.In your component
```js
import Tex from 'react-tex';

class TexWrapper extends Component{
  render(){
    return(
      <div>
        <Tex texContent="\int_{a}^{b} f(x)dx = F(b) - F(a)"/>
      </div>
    )
  }
}
```
2. Include Katex CSS in your html

```html

<html>
    <head>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.6.0/katex.min.css">
    </head>
</html>

```
