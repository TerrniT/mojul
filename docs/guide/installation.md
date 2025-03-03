# Installation

You can add Mojul to your project in several ways.

## Using NPM

```bash
npm install mojul-css
```

Then import it in your main JavaScript file:

```js
import 'mojul-css';
```

## Using CDN

Add the following link tag to your HTML:

```html
<link rel="stylesheet" href="https://cdn.example.com/mojul/latest.css">
```

## Manual Download

You can also download the CSS file directly and include it in your project:

```html
<link rel="stylesheet" href="path/to/mojul.css">
```

## Basic Setup

Once installed, you can start using Mojul's utility classes in your HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Mojul Project</title>
  <link rel="stylesheet" href="path/to/mojul.css">
</head>
<body class="m-0 p-4 bg-light">
  <header class="mb-4">
    <h1 class="mt-0">Hello Mojul!</h1>
  </header>
  <main class="p-2">
    <p>This is a paragraph with some padding.</p>
  </main>
</body>
</html>
```