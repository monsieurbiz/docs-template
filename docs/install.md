# Installation

You have to copy all the content of the `docs/` directory into your own `docs/` directory.

Then you have to change the `head` tag into the `index.html` file:

```html
<!-- TITLE OF YOUR DOCUMENTATION -->
<title>Docs Template - Monsieur Biz</title>

<!-- DESCRIPTION OF YOUR DOCUMENTATION -->
<meta name="description" content="">

<!-- Keep it -->
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
<meta name="viewport" content="width=device-width, user-scalable=no, initial-scale=1.0, maximum-scale=1.0, minimum-scale=1.0">

<!-- ANDROID APP CONFIGURATION -->
<meta name="theme-color" content="#5d44dc">
<meta name="msapplication-config" content="https://monsieurbiz.com/assets/favicons/browserconfig.xml">
<link rel="mask-icon" href="https://monsieurbiz.com/assets/favicons/safari-pinned-tab.svg">

<!-- OPEN GRAPH INFO -->
<meta property="og:title" content="Docs Template - Monsieur Biz">
<meta property="og:description" content="">
<meta property="og:url" content="https://monsieurbiz.com/">
<meta property="og:site_name" content="Docs Template documentation">
<meta property="og:type" content="website">
<meta property="og:image" content="https://monsieurbiz.com/assets/images/og-image.png">
<meta property="og:image:type" content="image/png">
<meta property="og:image:width" content="350">
<meta property="og:image:height" content="350">

<!-- SEO -->
<meta name="robots" content="index,follow">

<!-- FAVICONS -->
<link rel="apple-touch-icon" sizes="180x180" href="https://monsieurbiz.com/assets/favicons/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="32x32" href="https://monsieurbiz.com/assets/favicons/favicon-32x32.png">
<link rel="icon" type="image/png" sizes="16x16" href="https://monsieurbiz.com/assets/favicons/favicon-16x16.png">
<link rel="shortcut icon" href="https://monsieurbiz.com/assets/favicons/favicon.ico">
<link rel="manifest" href="https://monsieurbiz.com/assets/favicons/manifest.json">
```



You can also update the `style` tag in the `head` to make some CSS changes.

*Note: The first `script` tag is the only one which is executed by the page. So if you want to make some JS changes, update it or follow docsify documentation.*