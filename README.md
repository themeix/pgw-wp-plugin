# Paystation Payment Gateway
1. Download a zip file to the current repository
2. Upload it to add new plugin from wordpress dashboard
3. Activate Paystation Payment Gateway
4. Change the Merchant ID & Password at Woocommerce > Payment > Paystation Payment Gateway > Setup.
5. Add 2 radio button in checkout page (Pay With Charge, Pay Without Charge) using 'Checkout Field Editor and Manager for WooCommerce' Plugin.
Both radio button name will be billing_charge_for_customer and value for each radio button will be as belows
[Radio Button Name : Pay With Charge    Button Value : 1]
[Radio Button Name : Pay Without Charge Button Value : 0]
Pay With Charge radio button should be checked by default.
6. Thats it.

Note 1: If you want that customer will bear the charge then No - 5 is mandatory to implement otherwise optional.
