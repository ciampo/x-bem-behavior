##&lt;x-bem-behavior&gt;

**Polymer** behavior. Use `<x-bem-behavior>` to quickly compute BEM classnames.

```html
<div class$="{{bemClass('block-name')}}">
Default block text is black.

  <div class$="{{bemClass('block-name', 'element-name')}}">
    Block children text is blue.
  </div>
</div>

<div class$="{{bemClass('block-name', '', 'modifier')}}">
Special block text is green.
</div>
```

##Install

`bower install --save x-bem-behavior`