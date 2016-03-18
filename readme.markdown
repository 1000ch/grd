![Grd](logo.png)

A CSS grid framework using Flexbox.

- **Simple**: Provides just 2 base classes `Grid` and `Cell` and some modifiers.
- **Light-weight**: Only 512 bytes (Gzipped).
- **Flexible**: Easy to use Flexbox features.

[Flexible Box Layout Module](http://caniuse.com/#search=flex) and [`calc()` as CSS unit value](http://caniuse.com/#search=calc) used in Grd are available on modern browsers (Chrome, Firefox, Safari, Opera, Edge and IE11).

## Installation

```bash
# via npm
$ npm install grd

# via bower
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

- To align items with `align-items`
  - `-top`: To top
  - `-middle`: To middle
  - `-bottom`: To bottom
  - `-stretch`: Stretch items
  - `-baseline`: To baseline
- To layout contents with `justify-content`
  - `-left`: To left
  - `-center`: To center
  - `-right`: To right
  - `-between`: Add spaces between items
  - `-around`: Add spaces around items

### `Cell` modifiers

- `-fill`: Set item width to left width of parent
- `-1of12`: Set item width to 8.3% of parent
- `-2of12`: Set item width to 16.7% of parent
- `-3of12`: Set item width to 25% of parent
- `-4of12`: Set item width to 33% of parent
- `-5of12`: Set item width to 41.7% of parent
- `-6of12`: Set item width to 50% of parent
- `-7of12`: Set item width to 58.3% of parent
- `-8of12`: Set item width to 66.7% of parent
- `-9of12`: Set item width to 75% of parent
- `-10of12`: Set item width to 83.3% of parent
- `-11of12`: Set item width to 91.7% of parent
- `-12of12`: Set item width to 100% of parent

## License

MIT: http://1000ch.mit-license.org
