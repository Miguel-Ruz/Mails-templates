# TikketFy Email Templates

A collection of professional email templates designed for the TikketFy platform, optimized for SendGrid and email client compatibility.

## 📧 Templates Included

### 1. **OTP Template** (`otp.html`)
- Password reset functionality
- Clean, professional design
- QR code support for authentication

### 2. **Ticket Template** (`ticket.html`)
- Event ticket delivery
- Multiple ticket support with loop functionality
- Download links for each ticket

### 3. **End of Day Report** (`eod.html`)
- Sales report sharing
- Download functionality for reports
- Professional business communication

### 4. **Sales Tools** (`saletool.html`)
- Sales tool activation
- Personal sales link integration
- Dashboard preview integration

## 🎨 Design Features

- **Consistent Branding**: All templates use TikketFy's visual identity
- **Responsive Design**: Optimized for mobile and desktop email clients
- **Professional Layout**: Clean, modern design with proper spacing
- **Color Scheme**: Consistent with TikketFy brand colors
- **Typography**: Web-safe fonts for maximum compatibility

## 🛠 Technical Specifications

### Email Client Compatibility
- ✅ Gmail
- ✅ Outlook (all versions)
- ✅ Apple Mail
- ✅ Thunderbird
- ✅ Mobile email clients

### SendGrid Optimization
- Inline CSS for maximum compatibility
- Table-based layout structure
- Optimized image handling
- Proper meta tags and preheader text

### File Structure
```
Mails/
├── Assets/
│   ├── Sidebar-Logo_example.svg
│   ├── Sidebar-Logo_example-withe.svg
│   ├── Sidebar-Logo_example.png
│   ├── Thumbail.png
│   └── Ticket send.png
├── otp.html
├── ticket.html
├── eod.html
├── saletool.html
└── README.md
```

## 🚀 Usage

1. **Customize Content**: Modify the HTML content according to your needs
2. **Update Links**: Replace placeholder URLs with actual links
3. **Personalize Variables**: Use SendGrid dynamic content tags
4. **Test**: Preview in various email clients before sending
5. **Deploy**: Upload to SendGrid or your email service provider

## 🔧 Customization

### Dynamic Content Tags
- `{{name}}` - Recipient's name
- `{{email}}` - Recipient's email
- `{{view_in_browser_url}}` - Web version link
- `{{codigo}}` - OTP code (for password reset)
- `{{tickets}}` - Ticket loop (for ticket template)

### Branding Updates
- Logo files are located in the `Assets/` folder
- Colors can be modified in the inline CSS
- Font families can be updated for brand consistency

## 📱 Responsive Design

All templates include:
- Mobile-first approach
- Flexible table layouts
- Optimized image sizing
- Touch-friendly button sizes

## 🎯 Best Practices

- **Image Optimization**: Use compressed images for faster loading
- **Alt Text**: Always include descriptive alt text for images
- **Testing**: Test across multiple email clients before deployment
- **Accessibility**: Ensure proper contrast ratios and readable fonts
- **Performance**: Keep email size under 100KB for optimal delivery

## 📞 Support

For questions or support regarding these email templates:
- **Email**: help@tikketfy.com
- **Documentation**: Refer to SendGrid's email template guidelines

## 📄 License

© 2024 TikketFy. All rights reserved.

---

*Built with ❤️ for the TikketFy platform*
