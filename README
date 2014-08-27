# Optimizer

Optimizar imagenes JPG, PNG.

## Instalar

```shell
npm install image-optimizer
```

## Como usar

```coffee
Optimizer = require 'optimizer'
optimizer = new Optimizer
  src: '/path/to/src.ext'
  dest: '/path/to/dest.ext'
  options:
    pngquant: true, optipng: true, advpng: true, zopflipng: true,
    pngcrush: true, pngout: true, jpegRecompress: true, mozjpeg: true,
    jpegoptim: true

optimizer.optimize (error, data) ->
  if data.isOptimized
    console.log 'ok'
```

