# &lt;nvd3-stacked-area&gt;
Stacked area chart element for [Polymer](https://www.polymer-project.org) using [nvd3](http://nvd3.org/). It's part of [nvd3 charting elements](https://github.com/saeidzebardast/nvd3-elements).

## Install

```
bower install nvd3-stacked-area
```

## Usage
### Tag

```
<nvd3-stacked-area data="[[data]]"></nvd3-stacked-area>
```

### Data Format

```
[
    {
      "key" : "North America" ,
      "values" : [ [ 1 , 23.041422681023] , [ 2 , 19.854291255832] , [ 3 , 21.02286281168] , [ 4 , 22.093608385173]]
    },

    {
      "key" : "Africa" ,
      "values" : [ [ 1 , 7.9356392949025] , [ 2 , 7.4514668527298] , [ 3 , 7.9085410566608] , [ 4 , 5.8996782364764]]
    },

    {
      "key" : "Asia" ,
      "values" : [ [ 1 , 13.153938631352] , [ 2 , 12.456410521864] , [ 3 , 12.537048663919] , [ 4 , 13.947386398309] ]
    } ,

    {
      "key" : "Europe" ,
      "values" : [ [ 1 , 9.3433263069351] , [ 2 , 8.4583069475546] , [ 3 , 8.0342398154196] , [ 4 , 8.1538966876572]]
    }
]
```

## License
MIT © [Saeid Zebardast](http://zebardast.com)
