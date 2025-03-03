# Margin Utilities

Mojul provides a comprehensive set of margin utilities to control spacing around elements.

## Basic Margin Classes

Mojul uses a simple naming convention for margin utilities:

- `m-{value}` - margin on all sides
- `mt-{value}` - margin-top
- `mr-{value}` - margin-right
- `mb-{value}` - margin-bottom
- `ml-{value}` - margin-left
- `mx-{value}` - margin on left and right sides
- `my-{value}` - margin on top and bottom sides

Where `{value}` is a number from 0 to 8, representing the following spacing scale:

| Value | Pixels | Rems |
|-------|--------|------|
| 0     | 0      | 0    |
| 1     | 4px    | 0.25rem |
| 2     | 8px    | 0.5rem |
| 3     | 12px   | 0.75rem |
| 4     | 16px   | 1rem |
| 5     | 24px   | 1.5rem |
| 6     | 32px   | 2rem |
| 7     | 48px   | 3rem |
| 8     | 64px   | 4rem |

## Examples

### All Sides Margin

```html
<div class="m-4">
  This element has a margin of 16px (1rem) on all sides.
</div>
```

### Directional Margins

```html
<div class="mt-2 mb-4">
  This element has a margin-top of 8px (0.5rem) and a margin-bottom of 16px (1rem).
</div>
```

### Horizontal and Vertical Margins

```html
<div class="mx-auto my-4">
  This element is horizontally centered with auto margins and has vertical margins of 16px (1rem).
</div>
```

## Negative Margins

For negative margins, use the `-` prefix:

```html
<div class="mt-n2">
  This element has a negative margin-top of 8px (0.5rem).
</div>
```

## Auto Margins

You can use `auto` as a value for centering elements:

```html
<div class="mx-auto" style="width: 200px;">
  This element is centered horizontally.
</div>
```

## Responsive Margins

Mojul also provides responsive margin utilities with breakpoint prefixes:

```html
<div class="m-2 sm:m-3 md:m-4 lg:m-5">
  This element has different margins at different screen sizes.
</div>
```

This creates a responsive element with:
- 8px margin on all sides by default
- 12px margin on small screens and up
- 16px margin on medium screens and up
- 24px margin on large screens and up