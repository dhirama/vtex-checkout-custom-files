# vtex-checkout-custom-files
Sample custom files for VTEX Checkout alternative

### Simplified Flow
![store-theme-default](https://github.com/dhirama/vtex-checkout-custom-files/raw/main/placeorder_flow.png)
> **Note:** Each step has its own errors that should be handled properly.

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

### Interface Samples (VTEX IO Checkout)
**Project Reference:**
https://github.com/vtex-apps/checkout
https://github.com/vtex-apps/checkout-payment/blob/master/react/CreditCard.tsx

![PCI Payment Container - Option w/ stored card](https://github.com/dhirama/vtex-checkout-custom-files/raw/main/saved_card.png)
![PCI Payment Container - Default Form](https://github.com/dhirama/vtex-checkout-custom-files/raw/main/default_form.png)
![PCI Payment Container - Installment Options](https://github.com/dhirama/vtex-checkout-custom-files/raw/main/installments.png)
