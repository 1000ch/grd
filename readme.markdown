# Grd

A CSS grid framework using Flexbox.

## Installation

```bash
$ npm install grd
```

## Usage

Grd provides 2 classes as base, `Grid` and `Cell`.

```html
<div class="Grid">
  <div class="Cell --3of12">3of12</div>
  <div class="Cell --9of12">9of12</div>
</div>
```

### `Grid` modifiers

- `--top`: Align items to top
- `--middle`: Align items to middle
- `--bottom`: Align items to bottom
- `--left`: Layout items to left
- `--center`: Layout items to center
- `--right`: Layout items to right

### `Cell` modifiers

- `--fill`: Set item width to left width of parent
- `--1of12`: Set item width to 8.3% of parent
- `--2of12`: Set item width to 16.7% of parent
- `--3of12`: Set item width to 25% of parent
- `--4of12`: Set item width to 33% of parent
- `--5of12`: Set item width to 41.7% of parent
- `--6of12`: Set item width to 50% of parent
- `--7of12`: Set item width to 58.3% of parent
- `--8of12`: Set item width to 66.7% of parent
- `--9of12`: Set item width to 75% of parent
- `--10of12`: Set item width to 83.3% of parent
- `--11of12`: Set item width to 91.7% of parent
- `--12of12`: Set item width to 100% of parent

## License

MIT: http://1000ch.mit-license.org
