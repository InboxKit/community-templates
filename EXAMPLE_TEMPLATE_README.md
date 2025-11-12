# Order Confirmation Template

## Description
A clean, professional order confirmation email template perfect for e-commerce stores. Features a clear order summary, itemized list, pricing breakdown, and shipping details.

## Preview
![Desktop Preview](preview.png)

## Features
- **Order Summary Section** - Order number, date, and status
- **Product List** - Images, names, quantities, and prices
- **Price Breakdown** - Subtotal, shipping, tax, and total
- **Shipping Information** - Delivery address and tracking link
- **Brand Customization** - Easy to customize colors and logo
- **Fully Responsive** - Perfect on all devices
- **Accessible** - Proper semantic markup and alt text

## Tested In
- Gmail (Desktop & Mobile)
- Outlook 2016, 2019, Office 365
- Apple Mail (macOS & iOS)
- Yahoo Mail
- Thunderbird
- Samsung Email
- Windows Mail

## Variables

Replace these placeholders with your actual data:

### Customer Information
- `{{customer_name}}` - Customer's full name
- `{{customer_email}}` - Customer's email address

### Order Details
- `{{order_number}}` - Unique order number
- `{{order_date}}` - Order date (formatted)
- `{{order_status}}` - Order status (e.g., "Confirmed", "Processing")

### Items
For each product in the order:
- `{{product_name}}` - Product name
- `{{product_image}}` - Product image URL
- `{{product_quantity}}` - Quantity ordered
- `{{product_price}}` - Individual price
- `{{product_total}}` - Line total (quantity × price)

### Pricing
- `{{subtotal}}` - Order subtotal
- `{{shipping_cost}}` - Shipping fee
- `{{tax}}` - Tax amount
- `{{total}}` - Grand total

### Shipping
- `{{shipping_address}}` - Full shipping address
- `{{shipping_method}}` - Shipping method name
- `{{tracking_number}}` - Tracking number (optional)
- `{{tracking_url}}` - Tracking URL (optional)

### Company
- `{{company_name}}` - Your company name
- `{{company_logo}}` - Your logo URL
- `{{company_address}}` - Your business address
- `{{support_email}}` - Your support email
- `{{unsubscribe_url}}` - Unsubscribe link

## Usage Example

```javascript
// Node.js example using Nodemailer
const nodemailer = require('nodemailer');
const fs = require('fs');

// Load template
let template = fs.readFileSync('template.html', 'utf8');

// Replace variables
template = template
  .replace(/{{customer_name}}/g, order.customer.name)
  .replace(/{{order_number}}/g, order.id)
  .replace(/{{order_date}}/g, order.createdAt)
  // ... replace all variables

// Send email
await transporter.sendMail({
  from: 'orders@yourstore.com',
  to: order.customer.email,
  subject: `Order Confirmation #${order.id}`,
  html: template
});
```

## Customization

### Colors
Update these inline styles to match your brand:

- **Primary Color** (Buttons): `#1d4eff`
- **Text Color**: `#1f2937`
- **Secondary Text**: `#6b7280`
- **Border Color**: `#e5e7eb`
- **Background**: `#ffffff`

### Logo
Replace the logo URL in the header:
```html
<img src="{{company_logo}}" alt="{{company_name}}" style="height: 40px;" />
```

### Fonts
Currently uses system fonts for maximum compatibility:
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
```

## Technical Details

- **Width**: 600px (responsive on mobile)
- **HTML Tables**: Used for layout structure
- **Inline CSS**: All styles are inlined for email client compatibility
- **Media Queries**: Responsive breakpoints at 600px and below
- **Image Format**: PNG/JPG recommended
- **File Size**: ~15KB unminified

## Browser Support

**Desktop**
- Gmail
- Outlook 2016+
- Apple Mail
- Yahoo Mail
- Thunderbird
- AOL Mail

**Mobile**
- Gmail App (iOS/Android)
- Apple Mail (iOS)
- Samsung Email
- Outlook Mobile
- Yahoo Mail App

**Webmail**
- Gmail Web
- Outlook.com
- Yahoo Mail Web
- iCloud Mail

## Accessibility

This template follows WCAG 2.1 AA guidelines:

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for all images
- Sufficient color contrast (4.5:1 minimum)
- Clear focus indicators
- Descriptive link text

## License

MIT License - Free for commercial and personal use

## Author

**John Doe**
- Website: [johndoe.com](https://johndoe.com)
- GitHub: [@johndoe](https://github.com/johndoe)
- Email: john@johndoe.com

## Changelog

### v1.0.0 (2025-11-12)
- Initial release
- Responsive design
- Full order details
- Tracking link support

---

**Need help?** Open an issue or email support@inboxkit.com

