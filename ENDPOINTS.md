# SYNAPTEK LAB - POLICY ENDPOINTS REFERENCE

## 📋 Required Legal Endpoints

These are the three critical endpoints you requested for app/service integration:

---

### 1. PRIVACY POLICY
**Relative URL:** `/privacy-policy.html`

**Full URL Format:** `https://yourdomain.com/privacy-policy.html`

**Purpose:** Details how user data is collected, used, stored, and protected. GDPR compliant.

**Key Sections:**
- Information collection practices
- Data usage and storage
- User rights (access, correction, deletion)
- Cookie policy
- Contact information for privacy concerns

---

### 2. TERMS OF SERVICE
**Relative URL:** `/terms-of-service.html`

**Full URL Format:** `https://yourdomain.com/terms-of-service.html`

**Purpose:** Legal agreement outlining the rules, guidelines, and conditions for using Synaptek Lab services.

**Key Sections:**
- Acceptable use policy
- User responsibilities
- Service description
- Intellectual property rights
- Disclaimer of warranties
- Limitation of liability
- Educational disclaimer

---

### 3. DATA DELETION INSTRUCTIONS
**Relative URL:** `/data-deletion.html`

**Full URL Format:** `https://yourdomain.com/data-deletion.html`

**Purpose:** Step-by-step instructions for users to request deletion of their personal data.

**Key Sections:**
- What data can be deleted
- How to submit deletion request
- Processing timeline (30 days)
- Browser data clearing instructions
- Contact information: privacy@synapteklab.org

---

## 🔗 Additional Important Endpoints

### HOME PAGE
**URL:** `/` or `/index.html`
**Purpose:** Main landing page with features and CTAs

### AGENT STUDIO
**URL:** `/agent-studio.html`
**Purpose:** Interactive playground for building AI agents

### ABOUT US
**URL:** `/about.html`
**Purpose:** Information about Synaptek Lab's mission and values

### CONTACT
**URL:** `/contact.html`
**Purpose:** Contact form and communication channels

---

## 📧 Contact Email Addresses

Update these in your actual deployment:

- **General Inquiries:** info@synapteklab.org
- **Support:** support@synapteklab.org
- **Privacy Concerns:** privacy@synapteklab.org
- **Legal Matters:** legal@synapteklab.org

---

## 🌐 SEO Files

### ROBOTS.TXT
**URL:** `/robots.txt`
**Purpose:** Instructions for search engine crawlers

### SITEMAP
**URL:** `/sitemap.xml`
**Purpose:** XML sitemap for search engines

---

## 📱 Integration Examples

### For Mobile Apps (iOS/Android)
```swift
// iOS Example
let privacyURL = "https://yourdomain.com/privacy-policy.html"
let termsURL = "https://yourdomain.com/terms-of-service.html"
let deletionURL = "https://yourdomain.com/data-deletion.html"
```

```kotlin
// Android Example
val privacyURL = "https://yourdomain.com/privacy-policy.html"
val termsURL = "https://yourdomain.com/terms-of-service.html"
val deletionURL = "https://yourdomain.com/data-deletion.html"
```

### For Web Applications
```javascript
// JavaScript Example
const POLICY_URLS = {
  privacy: 'https://yourdomain.com/privacy-policy.html',
  terms: 'https://yourdomain.com/terms-of-service.html',
  deletion: 'https://yourdomain.com/data-deletion.html'
};
```

```html
<!-- HTML Footer Links -->
<footer>
  <a href="/privacy-policy.html">Privacy Policy</a>
  <a href="/terms-of-service.html">Terms of Service</a>
  <a href="/data-deletion.html">Data Deletion</a>
</footer>
```

---

## ⚙️ Before Deployment Checklist

- [ ] Update all "yourdomain.com" references with actual domain
- [ ] Update email addresses with actual addresses
- [ ] Test all links and navigation
- [ ] Verify robots.txt and sitemap.xml URLs
- [ ] Add SSL certificate (https://)
- [ ] Test on mobile devices
- [ ] Validate HTML and accessibility
- [ ] Set up contact form backend (if using the contact form)

---

## 🎯 Platform-Specific Requirements

### App Store (iOS)
Apple requires:
- Privacy Policy URL
- Terms of Service URL (optional but recommended)

### Google Play (Android)
Google requires:
- Privacy Policy URL (mandatory)
- Terms of Service URL (recommended)

### Facebook/Meta Integration
Requires:
- Privacy Policy URL
- Terms of Service URL
- Data Deletion Instructions URL

### OAuth Providers (Google, GitHub, etc.)
Usually require:
- Privacy Policy URL
- Terms of Service URL

---

## 📝 Quick Reference

| Policy | Endpoint | Status |
|--------|----------|--------|
| Privacy Policy | `/privacy-policy.html` | ✅ Ready |
| Terms of Service | `/terms-of-service.html` | ✅ Ready |
| Data Deletion | `/data-deletion.html` | ✅ Ready |

---

## 🔄 Maintenance

These pages should be reviewed and updated:
- **Privacy Policy:** Annually or when data practices change
- **Terms of Service:** Annually or when service terms change
- **Data Deletion:** Only if process changes

---

**Last Updated:** February 2, 2026

**Version:** 1.0

---

*For questions about these endpoints, contact: legal@synapteklab.org*
