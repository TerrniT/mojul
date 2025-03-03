# Padding Utilities

Mojul provides a comprehensive set of padding utilities to control internal spacing within elements.

## Basic Padding Classes

Mojul uses a simple naming convention for padding utilities:

- `p-{value}` - padding on all sides
- `pt-{value}` - padding-top
- `pr-{value}` - padding-right
- `pb-{value}` - padding-bottom
- `pl-{value}` - padding-left
- `px-{value}` - padding on left and right sides
- `py-{value}` - padding on top and bottom sides

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

### All Sides Padding

```html
<div class="p-4">
  This element has padding of 16px (1rem) on all sides.
</div>
```

### Directional Padding

```html
<div class="pt-2 pb-4">
  This element has padding-top of 8px (0.5rem) and padding-bottom of 16px (1rem).
</div>
```

### Horizontal and Vertical Padding

```html
<div class="px-4 py-2">
  This element has horizontal padding of 16px (1rem) and vertical padding of 8px (0.5rem).
</div>
```

## Combining Padding Utilities

You can combine different padding utilities to create complex layouts:

```html
<div class="p-4 pt-6">
  This element has padding of 16px (1rem) on all sides, but the top padding is overridden to 32px (2rem).
</div>
```

## Responsive Padding

Mojul also provides responsive padding utilities with breakpoint prefixes:

```html
<div class="p-2 sm:p-3 md:p-4 lg:p-5">
  This element has different padding at different screen sizes.
</div>
```

This creates a responsive element with:
- 8px padding on all sides by default
- 12px padding on small screens and up
- 16px padding on medium screens and up
- 24px padding on large screens and up

## Common Use Cases

### Card Component

```html
<div class="p-4 pb-6">
  <h2 class="mb-2">Card Title</h2>
  <p class="mb-4">Card content goes here.</p>
  <button class="px-4 py-2">Action Button</button>
</div>
```

### Form Elements

```html
<form class="p-4">
  <label class="mb-1">Username</label>
  <input type="text" class="p-2 mb-4">
  
  <label class="mb-1">Password</label>
  <input type="password" class="p-2 mb-4">
  
  <button type="submit" class="px-4 py-2">Submit</button>
</form>
```