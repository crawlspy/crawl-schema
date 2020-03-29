# crawl-schema
Capturing picture schema.

> version: 1.0.0

## Url format

- single bracket
    
    string replace, exmpale {page} -> 10

    `{page}` `{keyword}` `{category}`

- double bracket
  
    operator support * / - +, simple trinocular operation support, use `eval` to implement.

    `{{page + 1}}` is ok   
    `{{page * 10}}` is ok


## Match the target using Filters

use `Vue filter` to implement.

version `1.0.0` support the lists of filters:

```js
    lastafter: (str, last, ins)=> {
        let index = str.lastIndexOf(last);
        return str.substring(0, index + 1) + ins + str.substring(index + 1,str.length)
    },
    get: (a, b) => {
        return a[b]
    },
    split: (str, split) => {
        return str.split(split)
    },
    replace: (str, a, b) => {
        return str.replace(a, b)
    }
```

if `type: 'html'`, filter input content is `cheerio` instance 

so, you can write the filter like the following.

```js
find('.wall-res').html() | split('x') | get(0)
```

```js
find('img').attr('data-src') | replace('th.wallhaven.cc/small','w.wallhaven.cc/full') | lastafter('/', 'wallhaven-')
```


## Properties

[See the Schemas documents](./docs/README.md)



## Examples

[Browser the `example` directory](./examples/)


## License

Copyright 2020 Terry Cai Incorporated. All rights reserved.
This file is licensed to you under the Apache License, Version 2.0 (the 'License');
you may not use this file except in compliance with the License. You may obtain a copy
of the License at http://www.apache.org/licenses/LICENSE-2.0