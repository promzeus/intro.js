# Intro.js v3

[![Build Status](https://travis-ci.org/usablica/intro.js.svg?branch=master)](https://travis-ci.org/usablica/intro.js)
[![](https://data.jsdelivr.com/v1/package/npm/intro.js/badge)](https://www.jsdelivr.com/package/npm/intro.js)
[![npm](https://img.shields.io/npm/dm/intro.js)](https://www.jsdelivr.com/package/npm/intro.js)

> Better introductions for websites and features with a step-by-step guide for your projects.

## Where to get
You can obtain your local copy of Intro.js from:

**1)** This github repository, using ```git clone https://github.com/usablica/intro.js.git```

**2)** Using bower ```bower install intro.js --save```

**3)** Using npm ```npm install intro.js --save```

**4)** Download it from CDN ([1](http://www.jsdelivr.com/projects/intro.js), [2](https://cdnjs.com/libraries/intro.js))

## How to use
Intro.js can be added to your site in three simple steps:

**1)** Include `intro.js` and `introjs.css` (or the minified version for production) in your page. Use `introjs-rtl.min.css` for Right-to-Left language support.

> CDN hosted files are available at [jsDelivr](http://www.jsdelivr.com/projects/intro.js) (click Show More) & [cdnjs](https://cdnjs.com/libraries/intro.js).

**2)** Add `data-intro` and `data-step` to your HTML elements. To add hints you should use `data-hint` attribute.

For example:

```html
<a href='http://google.com/' data-intro='Hello step one!'></a>
````

See all attributes [here](https://introjs.com/docs/intro/attributes/).

**3)** Call this JavaScript function:
```javascript
introJs().start();
````

Optionally, pass one parameter to `introJs` function to limit the presentation section.

**For example** `introJs(".introduction-farm").start();` runs the introduction only for elements with `class='introduction-farm'`.

<p align="center"><img src="https://raw.githubusercontent.com/usablica/intro.js/gh-pages/img/introjs-demo.png"></p>

## Documentation

Please visit [Documentation](http://introjs.com/docs).

## Using with:

Intro.js has many wrappers for different purposes. Please visit [Documentation](http://introjs.com/docs) for more info.

## Build

First you should install `nodejs` and `npm`, then first run this command: `npm install` to install all dependencies.

Now you can run this command to minify all static resources:

    npm run build

## Instant IntroJs

Want to learn faster and easier? Here we have **Instant IntroJs**, Packt Publishing.

<p align="center">
  <a target='_blank' href="https://www.packtpub.com/eu/application-development/instant-introjs-instant">
    <img src='https://www.packtpub.com/media/catalog/product/cache/4cdce5a811acc0d2926d7f857dceb83b/2/5/2517os_instant20introjs20starter.jpg' />
  </a>
</p>

<p align="center">
  <a target='_blank' href="https://www.packtpub.com/eu/application-development/instant-introjs-instant">Buy and Download</a>
</p>

## <a href="https://github.com/usablica/intro.js/blob/master/changelog.md">Release History</a>

## Authors

<table>
  <tbody>
    <tr>
      <td align="center" valign="top">
        <img width="100" height="100" src="https://github.com/afshinm.png?s=150">
        <br>
        <a href="https://github.com/afshinm">Afshin Mehrabani</a>
      </td>
      <td align="center" valign="top">
        <img width="100" height="100" src="https://github.com/bozdoz.png?s=150">
        <br>
        <a href="https://github.com/bozdoz">Benjamin J DeLong</a>
      </td>
      <td align="center" valign="top">
        <img width="100" height="100" src="https://github.com/jalalazimi.png?s=150">
        <br>
        <a href="https://github.com/jalalazimi">Jalal Azimi</a>
      </td>
      <td align="center" valign="top">
        <img width="100" height="100" src="https://github.com/github.png?s=150">
        <br>
        <a href="https://github.com/usablica/intro.js/graphs/contributors">Other contributors</a>
      </td> 
     </tr>
  </tbody>
</table>

## Support/Discussion
- [Stackoverflow](http://stackoverflow.com/questions/tagged/intro.js)

## License

### Commercial license

If you want to use Intro.js for a commercial application, theme or plugin the commercial license is the appropriate license. With this option, your source code is kept proprietary. Purchase a commercial license at [introjs.com](http://introjs.com/#commercial)

### Open-source license

GNU AGPLv3
