# vtex-checkout-custom-files
Sample custom files for VTEX Checkout alternative

### Example URL
https://pocvtex.myvtex.com/checkout/cart/add/?sku=2000729&qty=1&seller=1&sc=3

### Post-robot

Events: 
```
{
  'setup',
  'showCardErrors',
  'resetCardFormData',
  'updateAddressId',
  'isCardValid',
  'getCardLastDigits'
}
```
Listeners:
```
{
  'paymentSystem'
}
```
