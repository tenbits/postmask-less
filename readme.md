[PostMask Less Compiler](https://github.com/atmajs/postmask)
-----
[![Build Status](https://travis-ci.org/tenbits/postmask-less.svg?branch=master)](https://travis-ci.org/tenbits/postmask-less)
[![NPM version](https://badge.fury.io/js/postmask-less.svg)](http://badge.fury.io/js/postmask-less)

Compiles functions in `mask` templates to es5

### Configurate

`mask.cfg('postmask-less', LessOptions);`

> Default: `{}`


### Runtime (_inprocess_)

Transform styles at runtime. Use this only in some demos and in dev, not for production.

###### Usage

```bash
npm i postmask-less --save-dev
```

```mask
style {
    @color: red;
    h4 {
        background: @color;
    }
}
h4 > 'Foo'
```

### Optimizer

Defines optimizers to compile style less content to css. Can be used as standalone module, but also as a plugin for `postmask`.


----
_(c) MIT License - Atma.js Project_