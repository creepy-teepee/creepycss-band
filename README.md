# Band

The band object adds vertical padding.

## Installation

    bower install --save creepycss-band

## Usage

```
@import 'bower_components/creepycss-band/objects.band';
```

```
<div class="o-band">
</div>
```

By default the band adds top and bottom padding equal to the base spacing unit, which can be changed by modifying the `$creepy-band-padding` variable.

There are also tiny, small, large and huge variants, enabled by changing the relevant flag variable and added as modifier classes, e.g. `o-band--large`.