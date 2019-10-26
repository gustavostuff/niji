[![niji.png](https://i.postimg.cc/9MQPFT5t/niji.png)](https://postimg.cc/XZtBsrvp)

## Non-serious styling for HTML elements

[![License](http://img.shields.io/:license-MIT-blue.svg)](https://github.com/tavuntu/niji/blob/master/LICENSE.md)

### Screenshots

[![1.png](https://i.postimg.cc/MZDsX95B/labels.png)](https://i.postimg.cc/MZDsX95B/labels.png)

Code:
```html
<h3 class="niji lbl w-100 text-center">Labels</h3>

<p>
    <label class="niji lbl">Default label</label>
</p>
<p>
    <label class="niji lbl lbl-green">Green label</label>
</p>
<p>
    <label class="niji lbl lbl-blue">Blue label</label>
</p>
<p>
    <label class="niji lbl lbl-red">Red label</label>
</p>
<p>
    <label class="niji lbl lbl-orange">Orange label</label>
</p>
```
---
[![buttons.gif](https://i.postimg.cc/GtcqqDL9/buttons.gif)](https://i.postimg.cc/GtcqqDL9/buttons.gif)

Code:
```html
<h3 class="niji lbl w-100 text-center">Buttons</h3>

<p>
    <button class="niji btn">Default button</button>
    <input type="button" class="niji btn btn-green" value="Green button"></input>
    <button class="niji btn btn-blue">Blue button</button>
    <p>
        <button class="niji btn btn-red">Red button</button>
    </p>
    <p>
        <button class="niji btn btn-orange">Orange button</button>
    </p>
</p>
```
---
[![radio.gif](https://i.postimg.cc/nhsTRpJK/radio.gif)](https://i.postimg.cc/nhsTRpJK/radio.gif)

Code:
```html
<h3 class="niji lbl w-100 text-center">Radio buttons</h3>

<label class="niji lbl"> <u>Select your favorite color:</u></label>

<div class="niji rad rad-green">
    <input id="green" type="radio" name="favorite-color" value="green">
    <label for="green">Green</label>
</div>
<div class="niji rad rad-blue">
    <input id="blue" type="radio" name="favorite-color" value="blue" checked="checked">
    <label for="blue">Blue</label>
</div>
<div class="niji rad rad-red">
    <input id="red" type="radio" name="favorite-color" value="red">
    <label for="red">Red</label>
</div>
<div class="niji rad rad-orange">
    <input id="orange" type="radio" name="favorite-color" value="orange">
    <label for="orange">Orange</label>
</div>
<div class="niji rad">
    <input id="default" type="radio" name="favorite-color" value="default">
    <label for="default">None of the above</label>
</div>
```
---
[![text-boxes.gif](https://i.postimg.cc/P5By09Xg/text.gif)](https://i.postimg.cc/P5By09Xg/text.gif)

Code:
```html
<h3 class="niji lbl w-100 text-center">Text boxes</h3>

<p>
    <input type="text" name="default" class="niji text" placeholder="placeholder" />
</p>
<p>
    <input type="text" name="default" class="niji text text-green" placeholder="placeholder" />
</p>
<p>
    <input type="text" name="default" class="niji text text-blue" placeholder="placeholder" />
</p>
<p>
    <input type="text" name="default" class="niji text text-red" placeholder="placeholder" />
</p>
<p>
    <input type="text" name="default" class="niji text text-orange" placeholder="placeholder" />
</p>
```
---
[![5.png](https://i.postimg.cc/2y2TJ5yG/helpers.png)](https://i.postimg.cc/2y2TJ5yG/helpers.png)

Code:
```html
<h3 class="niji lbl w-100 text-center">Box containers and some helper classes</h3>

<div class="box">
    <label class="niji lbl lbl-blue">Header line</label>
    <button class="niji btn">Action</button>
    <div class="box mt-2 mb-2">
        <label class="niji lbl">Some field</label>
        <input type="text" class="niji text text-blue" placeholder="type here">
    </div>
    <label class="niji lbl lbl-blue">Footer</label>
</div>
```
