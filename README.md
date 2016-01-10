# &lt;nvd3-stacked-area&gt; [![Build Status](https://travis-ci.org/saeidzebardast/nvd3-stacked-area.svg?branch=master)](https://travis-ci.org/saeidzebardast/nvd3-stacked-area)
Stacked area chart element for [Polymer](https://www.polymer-project.org) using [nvd3](http://nvd3.org/). It's part of [nvd3 charting elements](https://github.com/saeidzebardast/nvd3-elements).

## Install

```
bower install nvd3-stacked-area
```

## Usage
### Tag

```
<nvd3-stacked-area data="[[data]]" auto-resize></nvd3-stacked-area>
```

### Data Format

```
[
  {
    "key": "North America",
    "values": [
      [1, 23.041422681023],
      [2, 19.854291255832],
      [3, 21.02286281168],
      [4, 22.093608385173]
    ]
  },

  {
    "key": "Africa",
    "values": [
      [1, 7.9356392949025],
      [2, 7.4514668527298],
      [3, 7.9085410566608],
      [4, 5.8996782364764]
    ]
  },

  {
    "key": "South America",
    "values": [
      [1, 7.9149900245423],
      [2, 7.0899888751059],
      [3, 7.5996132380614],
      [4, 8.2741174301034]
    ]
  }
]
```

## Demo and Options
See the [component page](http://saeidzebardast.github.io/nvd3-stacked-area) for demo and options.

## License
MIT © [Saeid Zebardast](http://zebardast.com)
