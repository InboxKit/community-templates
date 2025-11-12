# Contributing to InboxKit Community Templates

Thank you for your interest in contributing to the InboxKit community template library!

## Rewards

When your template is accepted and merged, you'll receive **50% Off lifetime access** to InboxKit, including:
- Access to all templates and counting
- AI-powered customization assistant
- All future templates and updates

## Submission Guidelines

### What We're Looking For

**High-Quality Email Templates:**
- Clean, semantic HTML code
- Responsive design (mobile-friendly)
- Tested in major email clients (Gmail, Outlook, Apple Mail, etc.)
- Accessible (proper alt text, semantic markup)
- Well-commented code
- No inline JavaScript (email clients don't support it)

**Template Categories:**
- Transactional (receipts, confirmations, password resets, etc.)
- Marketing (promotions, announcements, product launches)
- Newsletter (content digests, updates, bulletins)
- E-commerce (abandoned cart, order updates, shipping notifications)

### What We Don't Accept

- Templates copied from other sources without permission
- Templates with broken layouts or rendering issues
- Templates that don't work in major email clients
- Templates with excessive inline styles or messy code
- Templates using deprecated HTML/CSS
- Templates that aren't mobile-responsive

## How to Submit

### 1. Fork the Repository

Click the "Fork" button at the top right of this repository.

### 2. Create a New Branch

```bash
git checkout -b feature/your-template-name
```

### 3. Add Your Template

Create a new folder in the appropriate category:

```
templates/
├── transactional/
│   └── your-template-name/
│       ├── template.html
│       ├── preview.png
│       └── README.md
```

**Required Files:**

**`template.html`** - Your email template
- Use inline CSS (email clients require it)
- Include proper DOCTYPE and meta tags
- Test in major email clients
- Add comments to explain sections

**`preview.png`** - Screenshot of your template
- Desktop and mobile views (combined or separate)
- At least 1200px wide
- PNG or JPG format
- Show the template rendered in an email client

**`README.md`** - Template documentation
```markdown
# Template Name

## Description
Brief description of the template and its use case.

## Preview
![Preview](preview.png)

## Features
- Feature 1
- Feature 2
- Feature 3

## Tested In
- Gmail (Desktop & Mobile)
- Outlook 2019
- Apple Mail
- Yahoo Mail
- Thunderbird

## Variables
List any dynamic content placeholders:
- `{{company_name}}` - Company name
- `{{order_number}}` - Order number
- etc.

## Author
Your Name - [Your Website/GitHub](link)

## License
MIT License - Free for commercial and personal use
```

### 4. Submit a Pull Request

Once you've added your template and all required files:

1. Commit your changes:
```bash
git add .
git commit -m "Add [template-name] email template"
```

2. Push to your fork:
```bash
git push origin feature/your-template-name
```

3. Open a Pull Request on GitHub
4. Fill out the PR template completely
5. Wait for review

## Review Process

1. **Automated Checks** - We'll run automated tests for HTML validation and accessibility
2. **Manual Review** - Our team will review your code quality, design, and functionality
3. **Testing** - We'll test the template in major email clients
4. **Feedback** - We may request changes or improvements
5. **Approval** - Once approved, we'll merge your PR and contact you about lifetime access

**Review Time:** Usually 3-7 business days

## Design Best Practices

### Layout
- Use tables for layout (email clients require it)
- Keep width at 600px for desktop
- Use responsive media queries
- Test on mobile devices

### CSS
- Use inline styles for most properties
- Keep `<style>` tag for media queries
- Avoid external CSS files
- Use hex colors, not named colors

### Images
- Always include `alt` text
- Use absolute URLs (or placeholders)
- Optimize file sizes
- Provide retina versions (@2x)

### Content
- Keep subject lines under 50 characters
- Use clear call-to-action buttons
- Ensure good contrast ratios (WCAG AA)
- Test with real content

## Email Client Testing

We recommend testing in:
- **Gmail** (Desktop, iOS, Android)
- **Outlook** (2016, 2019, Office 365)
- **Apple Mail** (macOS, iOS)
- **Yahoo Mail**
- **Thunderbird**

**Testing Tools:**
- [Litmus](https://litmus.com/)
- [Email on Acid](https://www.emailonacid.com/)
- [Mailtrap](https://mailtrap.io/)
- [Testi@](https://testi.at/)

## Code of Conduct

- Be respectful and professional
- Provide constructive feedback
- Help others improve their submissions
- Follow our contribution guidelines
- Don't submit low-quality or copied work

## License

By submitting a template, you agree to license it under the MIT License, allowing InboxKit and the community to use, modify, and distribute it freely.

You retain copyright to your work and will be credited as the author.

## Questions?

- **Email:** support@inboxkit.com
- **Issues:** Open an issue in this repository
- **Website:** [inboxkit.com/support](https://inboxkit.com/support)

---

Thank you for contributing to InboxKit! Your work helps developers around the world create better email experiences. 🚀

