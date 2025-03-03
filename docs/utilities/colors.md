# Color Utilities

Mojul provides a set of color utilities for text, backgrounds, and borders.

## Color System

Mojul uses a semantic color system with a consistent naming convention:

- `text-{color}` - Sets the text color
- `bg-{color}` - Sets the background color
- `border-{color}` - Sets the border color

## Available Colors

Mojul comes with a carefully selected palette of colors:

### Base Colors

| Class Suffix | Color Value | Description |
|--------------|-------------|-------------|
| `primary`    | `#3B82F6`   | Primary brand color |
| `secondary`  | `#6B7280`   | Secondary brand color |
| `success`    | `#10B981`   | Success state color |
| `danger`     | `#EF4444`   | Error/danger state color |
| `warning`    | `#F59E0B`   | Warning state color |
| `info`       | `#3B82F6`   | Information state color |

### Neutral Colors

| Class Suffix | Color Value | Description |
|--------------|-------------|-------------|
| `black`      | `#000000`   | Pure black |
| `white`      | `#FFFFFF`   | Pure white |
| `light`      | `#F3F4F6`   | Light background |
| `dark`       | `#1F2937`   | Dark background |
| `gray-100`   | `#F3F4F6`   | Lightest gray |
| `gray-200`   | `#E5E7EB`   | Light gray |
| `gray-300`   | `#D1D5DB`   | Gray |
| `gray-400`   | `#9CA3AF`   | Medium gray |
| `gray-500`   | `#6B7280`   | Medium-dark gray |
| `gray-600`   | `#4B5563`   | Dark gray |
| `gray-700`   | `#374151`   | Darker gray |
| `gray-800`   | `#1F2937`   | Very dark gray |
| `gray-900`   | `#111827`   | Nearly black |

## Examples

### Text Colors

```html
<p class="text-primary">This text is in the primary color.</p>
<p class="text-success">This text indicates success.</p>
<p class="text-danger">This text indicates danger or an error.</p>
<p class="text-gray-500">This text is in a medium gray color.</p>
```

### Background Colors

```html
<div class="bg-primary p-4">
  <p class="text-white">This is a primary background with white text.</p>
</div>

<div class="bg-light p-4">
  <p class="text-dark">This is a light background with dark text.</p>
</div>

<div class="bg-gray-800 p-4">
  <p class="text-white">This is a dark gray background with white text.</p>
</div>
```

### Border Colors

```html
<div class="border border-primary p-4">
  This element has a border in the primary color.
</div>

<div class="border border-danger p-4">
  This element has a border indicating danger.
</div>
```

## Combining Color Utilities

You can combine different color utilities to create visually appealing components:

```html
<div class="bg-light border border-gray-300 p-4">
  <h3 class="text-primary mb-2">Card Title</h3>
  <p class="text-gray-700">Card content with a slightly darker text.</p>
  <button class="bg-primary text-white px-4 py-2 mt-4">Action</button>
</div>
```

## Color Opacity

For some color utilities, you can specify opacity:

```html
<div class="bg-primary-50">
  This has the primary color with 50% opacity.
</div>

<div class="text-danger-75">
  This text is the danger color with 75% opacity.
</div>
```

The available opacity values are: 25, 50, 75, and 100 (default).