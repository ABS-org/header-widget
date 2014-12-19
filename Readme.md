## header-widget
> header padrão para os serviços da CdP

### Como usar
- Incluir ```sqwidget.js```
- Adicionar o Widget:
```<div data-sqwidget="/dist/cdp-header-widget"></div>```

- #### usando bower
  - To do

### Exemplo
```html
<!doctype html>
<html>
<head>
  <meta charset=utf-8>
  <meta name="viewport" content="width=device-width">

  <!-- tupi: header-widget.css -->
  <link rel="stylesheet" href="src/lib/tupi/css/header-widget.css">
  <link rel="stylesheet" href="src/lib/tupi/css/icon/tupi-icon.cdp.css">
  <link rel="stylesheet" href="src/lib/tupi/css/icon/tupi-icon.awesome.css">

  <style type="text/css">
    @font-face {
      font-family: 'icons-cdp';
      src: url('/CDN/bower_components/tupi/icon/cdp/icons-cdp.eot');
      src: url('/CDN/bower_components/tupi/icon/cdp/icons-cdp.eot') format('embedded-opentype'),
      url('/CDN/bower_components/tupi/icon/cdp/icons-cdp.woff') format('woff'),
      url('/CDN/bower_components/tupi/icon/cdp/icons-cdp.ttf') format('truetype'),
      url('/CDN/bower_components/tupi/icon/cdp/icons-cdp.svg') format('svg');
    }
    @font-face {
      font-family: 'FontAwesome';
      src: url('/CDN/bower_components/tupi/icon/awesome/fontawesome-webfont.eot');
      src: url('/CDN/bower_components/tupi/icon/awesome/fontawesome-webfont.eot') format('embedded-opentype'),
      url('/CDN/bower_components/tupi/icon/awesome/fontawesome-webfont.woff') format('woff'),
      url('/CDN/bower_components/tupi/icon/awesome/fontawesome-webfont.ttf') format('truetype'),
      url('/CDN/bower_components/tupi/icon/awesome/fontawesome-webfont.svg') format('svg');
    }
  </style>
</head>
<body>

  <!-- cdp-header-widget -->
  <div data-sqwidget="/dist/cdp-header-widget"></div>
  <!-- /cdp-header-widget -->

</body>

<script src="src/lib/sqwidget/sqwidget.js"></script>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="src/lib/bootstrap/dist/js/bootstrap.min.js"></script>

</html>
```

**© ABS-org** - [Comunidade de Práticas](http://atencaobasica.org.br/)
