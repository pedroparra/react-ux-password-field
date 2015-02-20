React UX Password Field
=============

Demo and full options: [https://seethroughtrees.github.io/react-ux-password-field/](https://seethroughtrees.github.io/react-ux-password-field/)

* * *

This react component aims to improve common issues in password field UX.

1.  **Password Strength Detection** - Using Dropbox's [zxcvbn](https://blogs.dropbox.com/tech/2012/04/zxcvbn-realistic-password-strength-estimation/) library in real-time, onChange.
2.  **Timed Password Masking** - Best explained in the [nngroup](http://www.nngroup.com/articles/stop-password-masking/) article: [Stop Password Masking](http://www.nngroup.com/articles/stop-password-masking/)
3.  **Stateful Class** - Know the HTML5 validity of your field by class.

## Install

```npm install react-ux-password-field```

## Use

``` javascript
// use it like any other react component.
// just require and place it inside your render function.

var InputPassword = require('react-ux-password-field');

...

render: function() {
  return (
    <InputPassword />
  )
}
```

## Options (props)

React UX Password Field will work fine with its defaults, but there is a lot
of configuration options.

Read them on the site: [https://seethroughtrees.github.io/react-ux-password-field/](https://seethroughtrees.github.io/react-ux-password-field/)
