# DROPZONE — Free Fire MAX Top-Up Storefront

## UPI payment setup
- UPI ID configured: `9083946648@fam`
- QR code included in the payment modal.
- Checkout opens a UPI payment link with the selected amount and lets the buyer send the order details + UTR to WhatsApp `+91 90839 46648`.

## Important: what is and is not live
- UPI payments can be initiated from compatible UPI apps. The QR identifies the supplied UPI ID; buyers should verify the payee name in their app before paying.
- This is **not** an automated payment gateway. The website cannot verify UPI payment on its own. Check the transaction in the receiving bank/UPI app before marking an order paid.
- WhatsApp order submission is a manual workflow; no order database or admin panel is connected.
- Diamond delivery is not integrated with an authorized supplier/API. Do not promise delivery until supplier access, stock, pricing and fulfilment are verified.
- Prices/discounts are prototype values and are not verified supplier prices. Confirm the actual cost and legitimate reference prices before publishing/advertising discounts.
- This is an independent storefront concept, not affiliated with or endorsed by Garena.

## Deploy
Upload `index.html` to your static hosting provider. The QR is embedded in the HTML, so no separate image file is required.
