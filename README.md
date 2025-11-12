# InboxKit Community Templates

Welcome to the InboxKit Community Templates repository! This is an open-source collection of high-quality, production-ready email templates contributed by developers worldwide.

## Get 50% off InboxKit lifetime access

Submit a template and get **50% off InboxKit lifetime access** when your contribution is accepted, including:

- Access to all 100+ premium templates
- AI-powered customization assistant  
- All future templates and updates
- Priority support

## Template Library

Browse our growing collection of community-contributed email templates:

### Transactional
Professional templates for transactional emails like receipts, confirmations, password resets, and notifications.

### Marketing  
Eye-catching templates for promotional campaigns, product launches, and marketing announcements.

### Newsletter
Clean, readable templates for newsletters, content digests, and regular updates.

### E-commerce
Conversion-focused templates for abandoned carts, order confirmations, shipping updates, and more.

## Quick Start

### Using Templates

1. Browse the `templates/` directory by category
2. Find a template that fits your needs
3. Copy the HTML from `template.html`
4. Customize the content and variables
5. Test in your preferred email client
6. Deploy!

### Contributing Templates

**Want to contribute? Here's how:**

1. Star this repository
2. Fork the repository
3. Read the [Contributing Guidelines](CONTRIBUTING.md)
4. Add your template in the appropriate category
5. Submit a Pull Request
6. Get free lifetime InboxKit access when approved!

[**→ Read Full Contributing Guide**](CONTRIBUTING.md)

## Submission Requirements

Your template must include:

- **`template.html`** - Clean, responsive email template
- **`preview.png`** - Screenshot of the rendered template  
- **`README.md`** - Documentation and usage instructions

**Quality Standards:**
- Mobile-responsive design
- Tested in major email clients (Gmail, Outlook, Apple Mail)
- Clean, well-commented HTML
- Inline CSS (email best practices)
- Accessible markup

## Template Structure

```
templates/
├── transactional/
│   ├── order-confirmation/
│   │   ├── template.html
│   │   ├── preview.png
│   │   └── README.md
│   └── password-reset/
│       ├── template.html
│       ├── preview.png
│       └── README.md
├── marketing/
├── newsletter/
└── ecommerce/
```

## Testing

All templates should be tested in:

- Gmail (Desktop, iOS, Android)
- Outlook (2016, 2019, Office 365)
- Apple Mail (macOS, iOS)
- Yahoo Mail
- Thunderbird

** Recommended Testing Tools:**
- [Litmus](https://litmus.com/)
- [Email on Acid](https://www.emailonacid.com/)
- [Mailtrap](https://mailtrap.io/)

## Best Practices

### HTML Structure
```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta name="format-detection" content="telephone=no" />
  <meta name="x-apple-disable-message-reformatting" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <title>Email Subject/Title</title>
  
  <style type="text/css">
    /* Responsive/media query styles here */
  </style>
</head>
<body style="margin: 0; padding: 0;">
  <!-- Email content -->
</body>
</html>
```

### CSS Guidelines
- Use inline styles for most properties
- Keep `<style>` tag for media queries only
- Avoid `!important` when possible
- Use tables for layout structure
- Keep max-width at 600px

### Image Guidelines
- Always include `alt` text
- Use absolute URLs
- Optimize file sizes
- Provide @2x versions for retina

## Resources

### Email Development
- [Email Client CSS Support](https://www.caniemail.com/)
- [Really Good Emails](https://reallygoodemails.com/)
- [HTML Email](https://htmlemail.io/)
- [Email Markup Consortium](https://emailmarkup.org/)

### Design Inspiration
- [Milled](https://milled.com/)
- [Email Love](https://emaillove.com/)
- [One Page Love](https://onepagelove.com/tag/email)

### Tools
- [Premailer](https://premailer.dialect.ca/) - Inline CSS
- [HTML Email Check](https://www.htmlemailcheck.com/) - Validation
- [PutsMail](https://putsmail.com/) - Test emails

## Community

- [Discussions](https://github.com/inboxkit/community-templates/discussions)
- [Report Issues](https://github.com/inboxkit/community-templates/issues)
- [Email Support](mailto:support@inboxkit.com)
- [InboxKit Website](https://inboxkit.com)

## License

All templates in this repository are licensed under the [MIT License](LICENSE).

You're free to:
- Use templates in commercial projects
- Modify and adapt templates
- Use in client projects
- Include in your products

You cannot:
- Resell templates as-is
- Create competing template libraries
- Remove author attribution

## Contributors

Thank you to all our amazing contributors! View the [Contributors Page](https://github.com/inboxkit/community-templates/graphs/contributors) to see everyone who has helped grow this library.

### Top Contributors

<!-- This will be auto-populated -->

## Statistics

![GitHub Stars](https://img.shields.io/github/stars/inboxkit/community-templates?style=social)
![GitHub Forks](https://img.shields.io/github/forks/inboxkit/community-templates?style=social)
![GitHub Issues](https://img.shields.io/github/issues/inboxkit/community-templates)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/inboxkit/community-templates)

---

**Ready to contribute?** [Read the Contributing Guide →](CONTRIBUTING.md)

**Need help?** [Contact Support →](mailto:support@inboxkit.com)

Made with ❤️ by the InboxKit community

