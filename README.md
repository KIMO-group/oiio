## OIIO

# How to install?

Add script to you page from script
```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/kimo-group/oiio/oiio.js"></script>
```

# How to use?

## In browser
Init plugin
```js

initOiioPayWidget({
  recipient: '<your-address>',
})

```

# All config parametrs

```js

{
  selector: '.js-waves-pay-button',
  endpoint: '',
  debug: false,
  node_url: '',
  provider: '',
  language: 'en'
}

```

#### recipient
You wallet address, required parametr

#### selector
You button selector, default .js-waves-pay-button

#### endpoit
You endpoit url, if you need get success payment data, default ''

#### debug
debug mode, for testing in testnet, default false

#### node_url
Custom NODE URL, if you use custom node, fill in this field, default ''

#### provider
Custom provider web, if you use custom provider, fill in this field, default ''

#### language
The language that will be used in the widget to save user data, default 'en'

Made by creative design and development team KIMO
