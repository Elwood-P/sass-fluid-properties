# Sass Fluid Properties

> A Sass mixin to simplify using CSS fluid properties.  
> [Read blog post](#)

## Usage

Use with any unit based property. Compatible with either px or rem units.

```scss
p {
  @include fluid-property(font-size, 16px, 32px);
  @include fluid-property(margin-bottom, 1rem, 2rem);
}
```


