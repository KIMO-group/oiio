## OIIO

# How to install?

Add script to you page
```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/kimo-group/oiio/oiio.min.js"></script>
```

# How to use?

Init plugin
```html
<script>
  initOiioPayWidget({
    recipient: '<your-address>',
  })
</script>
```

And add button

```html
<button
  class="js-oiio-pay-button"
  data-amount="<product-price>"
  data-name="<product-name>">
  My product
</button>
```

# All config parametrs

```js

{
  selector: '.js-oiio-pay-button',
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
You button selector, default .js-oiio-pay-button

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
