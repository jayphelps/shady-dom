# shady-dom
Shady under a tree, not sketchy.

<img src="https://cloud.githubusercontent.com/assets/762949/6996356/2fd7aaa4-db38-11e4-9d5e-a1c0d1613e13.jpg" width="383" height="357">

```js
import { registerElement } from 'shady-dom';

@registerElement()
class XFoo extends window.HTMLElement {
  createdCallback() {
    const root = this.createShadyRoot();
    root.innerHTML = '<a href="#">I\'m Shady</a><content></content>';
  }
}

```
# Credit
The "shady-dom" inspired by the awesome folks over at [Polymer](https://github.com/Polymer/polymer)
