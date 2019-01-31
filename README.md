# Niji

## Nice and non-serious web form controls (pure CSS)

[![License](http://img.shields.io/:license-MIT-blue.svg)](https://github.com/tavuntu/niji/blob/master/LICENSE.md)

### Screenshots

[![1.png](https://i.postimg.cc/bvZbGnJv/1.png)](https://postimg.cc/VSc5pdXy)

Code:
```html
<h3 class="niji lbl w-100 text-center">Labels</h3>

<p>
    <label class="niji lbl">Default label</label>
</p>
<p>
    <label class="niji lbl-green">Green label</label>
</p>
<p>
    <label class="niji lbl-blue">Blue label</label>
</p>
<p>
    <label class="niji lbl-red">Red label</label>
</p>
<p>
    <label class="niji lbl-orange">Orange label</label>
</p>
```
---
[![buttons.gif](https://i.postimg.cc/5yVFkkmH/buttons.gif)](https://postimg.cc/34tRk1V7)

Code:
```html
<h3 class="niji lbl w-100 text-center">Buttons</h3>

<p>
    <button class="niji btn">Default button</button>
    <input type="button" class="niji btn-green" value="Green button"></input>
    <button class="niji btn-blue">Blue button</button>
    <p>
        <button class="niji btn-red">Red button</button>
    </p>
    <p>
        <button class="niji btn-orange">Orange button</button>
    </p>
</p>
```
---
[![radio.gif](https://i.postimg.cc/qqxCfXm1/radio.gif)](https://postimg.cc/vxDmf9wn)

Code:
```html
<h3 class="niji lbl w-100 text-center">Radio buttons</h3>

<label class="niji lbl"> <u>Select your favorite color:</u></label>
<div class="niji rad-green">
    <input id="green" type="radio" name="favorite-color" value="green">
    <label for="green">Green</label>
</div>
<div class="niji rad-blue">
    <input id="blue" type="radio" name="favorite-color" value="blue" checked="checked">
    <label for="blue">Blue</label>
</div>
<div class="niji rad-red">
    <input id="red" type="radio" name="favorite-color" value="red">
    <label for="red">Red</label>
</div>
<div class="niji rad-orange">
    <input id="orange" type="radio" name="favorite-color" value="orange">
    <label for="orange">Orange</label>
</div>
<div class="niji rad">
    <input id="default" type="radio" name="favorite-color" value="default">
    <label for="default">None of the above</label>
</div>
```
---
[![text-boxes.gif](https://i.postimg.cc/W1Wgb8sK/text-boxes.gif)](https://postimg.cc/fVdJ8xtj)

Code:
```html
<h3 class="niji lbl w-100 text-center">Text boxes</h3>

<p>
    <input type="text" name="default" class="niji text" placeholder="placeholder" />
</p>
<p>
    <input type="text" name="default" class="niji text-green" placeholder="placeholder" />
</p>
<p>
    <input type="text" name="default" class="niji text-blue" placeholder="placeholder" />
</p>
<p>
    <input type="text" name="default" class="niji text-red" placeholder="placeholder" />
</p>
<p>
    <input type="text" name="default" class="niji text-orange" placeholder="placeholder" />
</p>
```
---
[![5.png](https://i.postimg.cc/8CxvLCJm/5.png)](https://postimg.cc/gwqrWmKx)

Code:
```html
<h3 class="niji lbl w-100 text-center">Box containers and some helper classes</h3>

<div class="box">
    <label class="niji lbl-blue">Header line</label>
    <button class="niji btn">Action</button>
    <div class="box mt-2 mb-2">
        <label class="niji lbl">Some field</label>
        <input type="text" class="niji text-blue" placeholder="type here">
    </div>
    <label class="niji lbl-blue">Footer</label>
</div>
```
