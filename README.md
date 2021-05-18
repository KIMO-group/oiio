## OIIO

# How to install?

Add the script to your page in a footer
```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/kimo-group/oiio/oiio.min.js"></script>
```

# How to use?

Initialize the plugin
```html
<script>
  initOiioPayWidget({
    recipient: '<your-address>',
  })
</script>
```

Then add a pay button in the right place

```html
<button
  class="js-oiio-pay-button"
  data-amount="<product-price>"
  data-name="<product-name>"
>
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
Your wallet address, required parameter

#### selector
Your button selector, default .js-oiio-pay-button

#### endpoit
Your endpoint url, if you need get success payment data, default ''  
If you have added an endpoint url, the data will be sent there in the following form:
```json
{
  "blockchain_response": {
    "<transaction response>"
  },
  "product": "<product-name>",
  "amount": "<amount>",
  "client": "<client telegram or email>"
}
```

#### debug
Debug mode for testing in testnet, default false

#### node_url
Custom NODE URL, if you use custom node, fill in this field, default ''

#### provider
Custom provider web, if you use custom provider, fill in this field, default ''

#### language
The language that will be used in the widget to save user data, default 'en'

Made by creative design and development team KIMO