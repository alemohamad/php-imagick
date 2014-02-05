# PHP + Imagick

Some image effects with PHP and Imagick.

## Original picture

![Original](http://alemohamad.com/github/imagick/summer.jpg)

## Blur

![Blur](http://alemohamad.com/github/imagick/summer-blur.jpg)

```php
$img = new Imagick('summer.jpg');
$img->blurImage(0,5);
$img->writeImage('summer-blur.jpg');
$img->clear(); 
$img->destroy();
```

## Black Threshold

![Black Threshold](http://alemohamad.com/github/imagick/summer-grey.jpg)

```php
$img = new Imagick('summer.jpg');
$img->blackThresholdImage('#888888');
$img->writeImage('summer-grey.jpg');
$img->clear(); 
$img->destroy();
```

## Charcoal

![Charcoal](http://alemohamad.com/github/imagick/summer-charcoal.jpg)

```php
$img = new Imagick('summer.jpg');
$img->charcoalImage(0,3);
$img->writeImage('summer-charcoal.jpg');
$img->clear(); 
$img->destroy();
```

## Colorize

![Colorize](http://alemohamad.com/github/imagick/summer-colorize.jpg)

```php
$img = new Imagick('summer.jpg');
$img->colorizeImage('#ffcc00',0.3);
$img->writeImage('summer-colorize.jpg');
$img->clear(); 
$img->destroy();
```

## Negate

![Negate](http://alemohamad.com/github/imagick/summer-negate.jpg)

```php
$img = new Imagick('summer.jpg');
$img->negateImage(0);
$img->writeImage('summer-negate.jpg');
$img->clear(); 
$img->destroy();
```

## Oil Paint

![Oil Paint](http://alemohamad.com/github/imagick/summer-oilPaint.jpg)

```php
$img = new Imagick('summer.jpg');
$img->oilPaintImage(0.3);
$img->writeImage('summer-oilPaint.jpg');
$img->clear(); 
$img->destroy();
```

## Radial Blur

![Radial Blur](http://alemohamad.com/github/imagick/summer-radialBlur.jpg)

```php
$img = new Imagick('summer.jpg');
$img->radialBlurImage(45);
$img->writeImage('summer-radialBlur.jpg');
$img->clear(); 
$img->destroy();
```

## Sepia Tone

![Sepia Tone](http://alemohamad.com/github/imagick/summer-sepiaTone2.jpg)

```php
$img = new Imagick('summer.jpg');
$img->sepiaToneImage(80);
$img->writeImage('summer-sepiaTone2.jpg');
$img->clear(); 
$img->destroy();
```

## Sketch

![Sketch](http://alemohamad.com/github/imagick/summer-sketch.jpg)

```php
$img = new Imagick('summer.jpg');
$img->sketchImage(0,3,10);
$img->writeImage('summer-sketch.jpg');
$img->clear(); 
$img->destroy();
```

## Wave

![Wave](http://alemohamad.com/github/imagick/summer-wave.jpg)

```php
$img = new Imagick('summer.jpg');
$img->waveImage(10,20);
$img->writeImage('summer-wave.jpg');
$img->clear(); 
$img->destroy();
```

![Ale Mohamad](http://alemohamad.com/github/logo2012am.png)