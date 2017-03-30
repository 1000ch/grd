![Grd](logo.png)

![](https://badge-size.herokuapp.com/1000ch/grd/master/dist/grd.css.svg?compression=gzip)
[![devDependency Status](https://david-dm.org/1000ch/grd/dev-status.svg)](https://david-dm.org/1000ch/grd?type=dev)

A CSS grid framework using Flexbox.

- **Simple**: Provides just 2 base classes `Grid` and `Cell` and some modifiers.
- **Light-weight**: Only 321 bytes (Gzipped).
- **Flexible**: Easy to use Flexbox features.

[Flexible Box Layout Module](http://caniuse.com/#search=flex) and [`calc()` as CSS unit value](http://caniuse.com/#search=calc) used in Grd are available on modern browsers (Chrome, Firefox, Safari, Opera, Edge and IE11).

If you want to use Grd with Sass, you can choose [grd-sass](https://github.com/1000ch/grd-sass) as Sass port.

## Install

### npm

```bash
$ npm install grd
```

### bower

```bash
$ bower install grd
```

## Usage

```html
<div class="Grid">
  <div class="Cell -3of12">3of12</div>
  <div class="Cell -9of12">9of12</div>
</div>
```

### `Grid` modifiers

| Vertical layout | Description |
|---|---|
| `-top` | Pull items to top |
| `-middle` |  Pull items to middle |
| `-bottom` |  Pull items to bottom |
| `-stretch` | Stretch items |
| `-baseline` |  Pull items to baseline |

| Horizontal layout | Description |
|---|---|
| `-left` | Layout items to left |
| `-center` | Layout items To center |
| `-right` | Layout items to right |
| `-between` | Add spaces between items |
| `-around` | Add spaces around items |

### `Cell` modifiers

| Cell width | Description |
|---|---|
| `-fill` | Set item width to left |
| `-1of12` | Set item width to 8.3% |
| `-2of12` | Set item width to 16.7% |
| `-3of12` | Set item width to 25% |
| `-4of12` | Set item width to 33% |
| `-5of12` | Set item width to 41.7% |
| `-6of12` | Set item width to 50% |
| `-7of12` | Set item width to 58.3% |
| `-8of12` | Set item width to 66.7% |
| `-9of12` | Set item width to 75% |
| `-10of12` | Set item width to 83.3% |
| `-11of12` | Set item width to 91.7% |
| `-12of12` | Set item width to 100% |

## License

[MIT](https://1000ch.mit-license.org) © [Shogo Sensui](https://github.com/1000ch)
