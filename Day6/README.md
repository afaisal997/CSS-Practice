# CSS Word-Wrap and Word-Break

Both Word-Wrap and word-break are properties that control how text behaves whe it reaches the edge of its container.
or when it overflows. these properties are particularly useful when dealing with long words or sentences that might not fit within a defined width.

## Word-Wrap
The `word-wrap` property is used to specify whether or not the browser should insert line breaks within
a word to prevent it from overflowing its container. It can take one of three values:
- `normal` (default): The browser will insert line breaks as needed to prevent overflow.
- `break-word`: The browser will insert line breaks within words if necessary to prevent overflow.  
- `initial`: Sets the property to its initial value, which is `normal`.
- `inherit`: Inherit the property from the parent element.
- `unset`: Unset the property.
- `none`: Do not break words.
- `break-all`: Break words at any point.
- `break-word`: Break words at any point.
- `break-spaces`: Break words at spaces.
- `break-strict`: Break words at strict points.

## Word-Break
The `word-break` property is used to specify how words should be broken when they reach the edge
of their container. It can take one of several values:
- `normal` (default): The browser will break words as needed to prevent overflow.
- `break-all`: The browser will break words at any point to prevent overflow.
- `break-word`: The browser will break words at any point to prevent overflow.
- `keep-all`: The browser will not break words.
- `initial`: Sets the property to its initial value, which is `normal`.
- `inherit`: Inherit the property from the parent element.
- `unset`: Unset the property.
- `break-spaces`: Break words at spaces.
- `break-strict`: Break words at strict points.
- `break-word`: Break words at any point.
- `break-all`: Break words at any point.


# Text-Shadow
The `text-shadow` property is used to add a shadow to text. It can take one or more values, each representing the offset and color of a shadow.

## Syntax

    text-shadow: h-shadow v-shadow blur-radius color;

# Gradient Background
A CSS gradient background is a way to creat a smooth transition between two or more colors in a background.

It can be used to create a variety of effects, from simple to complex.

### Example
    background:linear-gradient(to right, red, yellow);
This creates a gradient that goes from red to yellow 

# CSS Opacity
The `opacity` property is used to set the transparency of an element. It can take a value between 0 (fully transparent) and 1 (fully opaque).
- `0`: Fully transparent
- `1`: Fully opaque
- `0.5`: 50% opaque
- `0.2`: 20% opaque
- `0.8`: 80% opaque

- 
