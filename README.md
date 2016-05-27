# Griddd

A light weight, mobile first, simple and fully nestable 12 column grid for responsive web pages.

[View Demo](http://danielmdesigns.github.io/griddd/)

### Getting Started
Fast set up! Download Griddd and simply include the stylesheet into the head of your document file, like shown below. Minified and/or production CSS included.

#####Production
```
<link rel="stylesheet" href="griddd.min.css" type="text/css">
```

#####Development
```
<link rel="stylesheet" href="griddd.css" type="text/css">
```

### Introduction
1. Begin by choosing a proper grid container. ```.container``` _(fixed width)_ has a maximum width of 1024px or ```.container-full``` _(fluid width)_.
2. Add an element with a class of ```.row``` to create a horizontal column group nested inside the container class.
3. Then add elements with a ```.col-$``` class within that ```.row```. Substitute ```$``` for the total number of columns you want for that ```.row```.
4. Grid also includes a custom reset for browser consistency.

### Basic Usage
```
<div class="container">
  <div class="row">
    <div class="col-1">
      <div class="fill">.col-1</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-2">
      <div class="fill">.col-2</div>
    </div>
    <div class="col-2">
      <div class="fill">.col-2</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-3">
      <div class="fill">.col-3</div>
    </div>
    <div class="col-3">
      <div class="fill">.col-3</div>
    </div>
    <div class="col-3">
      <div class="fill">.col-3</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-4">
      <div class="fill">.col-4</div>
    </div>
    <div class="col-4">
      <div class="fill">.col-4</div>
    </div>
    <div class="col-4">
      <div class="fill">.col-4</div>
    </div>
    <div class="col-4">
      <div class="fill">.col-4</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-5">
      <div class="fill">.col-5</div>
    </div>
    <div class="col-5">
      <div class="fill">.col-5</div>
    </div>
    <div class="col-5">
      <div class="fill">.col-5</div>
    </div>
    <div class="col-5">
      <div class="fill">.col-5</div>
    </div>
    <div class="col-5">
      <div class="fill">.col-5</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-6">
      <div class="fill">.col-6</div>
    </div>
    <div class="col-6">
      <div class="fill">.col-6</div>
    </div>
    <div class="col-6">
      <div class="fill">.col-6</div>
    </div>
    <div class="col-6">
      <div class="fill">.col-6</div>
    </div>
    <div class="col-6">
      <div class="fill">.col-6</div>
    </div>
    <div class="col-6">
      <div class="fill">.col-6</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-7">
      <div class="fill">.col-7</div>
    </div>
    <div class="col-7">
      <div class="fill">.col-7</div>
    </div>
    <div class="col-7">
      <div class="fill">.col-7</div>
    </div>
    <div class="col-7">
      <div class="fill">.col-7</div>
    </div>
    <div class="col-7">
      <div class="fill">.col-7</div>
    </div>
    <div class="col-7">
      <div class="fill">.col-7</div>
    </div>
    <div class="col-7">
      <div class="fill">.col-7</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-8">
      <div class="fill">.col-8</div>
    </div>
    <div class="col-8">
      <div class="fill">.col-8</div>
    </div>
    <div class="col-8">
      <div class="fill">.col-8</div>
    </div>
    <div class="col-8">
      <div class="fill">.col-8</div>
    </div>
    <div class="col-8">
      <div class="fill">.col-8</div>
    </div>
    <div class="col-8">
      <div class="fill">.col-8</div>
    </div>
    <div class="col-8">
      <div class="fill">.col-8</div>
    </div>
    <div class="col-8">
      <div class="fill">.col-8</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
    <div class="col-9">
      <div class="fill">.col-9</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
    <div class="col-10">
      <div class="fill">.col-10</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
    <div class="col-11">
      <div class="fill">.col-11</div>
    </div>
  </div>
  
  <div class="row">
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
    <div class="col-12">
      <div class="fill">.col-12</div>
    </div>
  </div>
</div>
```

### Media Queries
**Small:** Any screen size

**Medium:** 40em/800px or wider

**Large:** 60em/480px or wider

### Helpers
Add a class of ```.fill``` to any ```.col-$``` element to visually see initial layout & structure
