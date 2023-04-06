# Sass Fluid Properties

> A Sass mixin to simplify using CSS fluid properties.  
> [Read blog post](https://elwoodp.dev/articles/flexible-sizing-in-css/)


## Usage
Use with any unit based property. Compatible with either px or rem units.

```scss
p {
  @include fluid-property(font-size, 16px, 32px);
  @include fluid-property(margin-bottom, 1rem, 2rem);
}
```


##  Customisation
Customise the variables `$min-vw` and `$max-vw` to set the minimum and maximum screen widths between which the fluid property interpolates. Add the desired values in  `_variables.scss`.

```scss
// Set minimum and maximum screen widths between which the fluid property interpolates

$min-vw: 400px;
$max-vw: 1400px;
```
