# Cisco Secure Email Encryption Service (CRES) - User Guide

A comprehensive guide for users to understand how to read and access encrypted emails using Cisco's CRES system.

## 📋 Contents

This repository contains complete user documentation for CRES with the following files:

### Documentation Files

1. **CRES_USER_GUIDE.html** ⭐ **START HERE**
   - Beautiful, interactive HTML guide
   - Professional styling with color-coded sections
   - Easy to read and navigate
   - Includes security reminders and FAQs
   - Open in any web browser

2. **CRES_USER_GUIDE.md**
   - Markdown version of the complete guide
   - Suitable for GitHub, GitLab, or Confluence
   - Can be converted to PDF using tools like Pandoc
   - Complete 7-step walkthrough

3. **IMAGE_MASKING_GUIDE.md**
   - Reference guide showing which images contain sensitive information
   - Instructions for masking email addresses in screenshots
   - Recommended replacement values for masking

4. **README.md** (this file)
   - Overview of the entire guide package
   - Instructions for use and deployment

## 🎯 Quick Start

**For End Users:**
1. Open `CRES_USER_GUIDE.html` in your web browser
2. Follow the 7 simple steps to read your encrypted email
3. Check the troubleshooting section if you need help

**For Documentation Teams:**
1. Use `CRES_USER_GUIDE.md` to post on your internal wiki/intranet
2. Customize the guide with your organization's support contact information
3. Use `CRES_USER_GUIDE.html` for web-based documentation portals

## 📱 Viewing Options

### Option 1: HTML Guide (Recommended)
```bash
# Simply open in browser
open CRES_USER_GUIDE.html
```
Or drag and drop the file into your web browser.

### Option 2: Markdown Guide
View on GitHub, GitLab, Confluence, or any markdown viewer.

### Option 3: Convert to PDF
Using Pandoc:
```bash
pandoc CRES_USER_GUIDE.md -o CRES_USER_GUIDE.pdf
```

## 📸 Working with Screenshots

The guide references the 9 original screenshots (01.jpg - 09.jpg) showing the complete CRES workflow.

**To use with masked images:**
1. Review `IMAGE_MASKING_GUIDE.md` for which images need masking
2. Use any image editor to mask sensitive email addresses:
   - **Option A:** Manual masking with Photoshop, GIMP, or online tools
   - **Option B:** Python script with Pillow library
   - **Option C:** Online privacy tools

**Email addresses to mask:**
- `leftycoffee50@gmail.com` → `user@example.com` or `[USER_EMAIL]`
- `ketcheon@cisco.com` → `sender@example.com` or `[SENDER_EMAIL]`

## 📖 Guide Structure

The complete guide covers 7 steps:

```
Step 1: Receive a Secure Email Notification
   ↓
Step 2: Login or Register
   ↓
Step 3: New User Registration (if needed)
   ↓
Step 4: Account Activation Confirmation
   ↓
Step 5: Open Account Activation Email
   ↓
Step 6: Confirm Email Address
   ↓
Step 7: Access Your Encrypted Email
```

## 🔒 Key Features

- ✅ Complete 7-step workflow
- ✅ Security best practices highlighted
- ✅ Comprehensive troubleshooting section
- ✅ FAQ format for quick answers
- ✅ Password requirements clearly stated
- ✅ Mobile access instructions
- ✅ Professional styling and layout
- ✅ Printable format

## 🛠️ Customization

To customize for your organization:

1. **HTML Version:**
   - Open `CRES_USER_GUIDE.html` in a text editor
   - Replace "Cisco" with your company name (optional)
   - Update contact information in the "Need Help?" section
   - Modify colors in the `<style>` section if desired
   - Save and use on your intranet

2. **Markdown Version:**
   - Edit `CRES_USER_GUIDE.md` directly
   - Add your organization's support contact details
   - Update any company-specific information
   - Commit to your repository

## 📋 Deployment Options

### Option 1: GitHub Pages
1. Push files to GitHub repository
2. Enable GitHub Pages in repository settings
3. Access guide at `https://your-org.github.io/repo-name/`

### Option 2: Internal Wiki
1. Export HTML or convert to PDF
2. Upload to your internal wiki (Confluence, MediaWiki, etc.)
3. Share the URL with your organization

### Option 3: Email/Portal
1. Export to PDF using Pandoc
2. Attach to welcome emails
3. Post on employee portals
4. Include in onboarding materials

### Option 4: Print
1. Open HTML in browser
2. Print to PDF (Cmd+P → Save as PDF)
3. Print physical copies for office bulletin boards

## 🐛 Troubleshooting Common Issues

**Message link expired:** Contact sender for a new link

**Not registered:** Click "Register" to create an account

**Email not received:** Check junk/spam folder

**Mobile display issues:** Forward to mobile@res.cisco.com

**Forgot password:** Click "Forgot password?" on login page

See `CRES_USER_GUIDE.html` or `CRES_USER_GUIDE.md` for detailed troubleshooting.

## 📝 Notes

- Original screenshots: 01.jpg through 09.jpg
- All email addresses in original screenshots should be masked before sharing publicly
- Guide is current as of 2025
- Compatible with CRES (Cisco Secure Email Encryption Service)

## 📄 License

This documentation is provided as-is for users of Cisco Secure Email Encryption Service.
Cisco Systems, Inc. © 2011-2025. All rights reserved.

## ✅ Checklist for Implementation

- [ ] Review both HTML and Markdown versions
- [ ] Mask sensitive email addresses in screenshots if using images
- [ ] Customize support contact information (if needed)
- [ ] Choose deployment method (GitHub, Wiki, Email, etc.)
- [ ] Test HTML guide in multiple browsers
- [ ] Share with your organization
- [ ] Collect feedback and update as needed

---

**Ready to use?** Start with `CRES_USER_GUIDE.html` - it's the most user-friendly format!

For questions or to provide feedback, contact your IT/Documentation team.
