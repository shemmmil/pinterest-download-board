# Privacy Policy for Pinterest Board Downloader

**Last Updated:** November 26, 2025  
**Effective Date:** November 26, 2025

## Overview

Pinterest Board Downloader ("the Extension") is committed to protecting your privacy. This Privacy Policy explains how the Extension handles information when you use it.

## Information Collection

### What We DON'T Collect

The Extension **does NOT collect, store, or transmit** any personal information, including but not limited to:

- ❌ Personal identification information
- ❌ Browsing history
- ❌ Email addresses
- ❌ User credentials
- ❌ Analytics or tracking data
- ❌ Cookies or similar technologies

### What We DO Process (Locally Only)

The Extension processes the following data **locally in your browser only**:

- ✅ Current Pinterest board URL (to identify which board to download)
- ✅ Public pin data from Pinterest (images, videos, titles)
- ✅ Downloaded files (stored directly to your Downloads folder)
- ✅ Anonymous user ID (stored in browser's localStorage for analytics purposes)

**Important:** All processing happens entirely within your browser. Only anonymous usage analytics are sent to our analytics service (see Analytics section below).

## Data Storage

- **Local Storage:** The Extension stores only an anonymous user ID (UUID) in your browser's localStorage for analytics purposes. This ID is randomly generated and cannot be used to identify you.
- **Downloads:** Files are saved directly to your browser's Downloads folder
- **No Cloud Storage:** No personal data is uploaded to any cloud service
- **Analytics Database:** Only anonymous usage statistics are stored in our analytics database (see Analytics section)

## Data Transmission

- **Pinterest.com:** The Extension communicates with Pinterest.com to fetch public board data and download images/videos
- **Analytics Service (Supabase):** The Extension sends anonymous usage analytics to our analytics service. This includes:

  - Anonymous user ID (randomly generated UUID, not linked to your identity)
  - Event type (e.g., "download_started", "modal_opened")
  - Format selected (ZIP or PDF)
  - Number of pins (for statistical purposes only)
  - Timestamp of the event

  **No personal information is transmitted.** The analytics data cannot be used to identify you or track your browsing activity outside of Pinterest.

- **No Third Parties:** No data is shared with third-party services except for the analytics service mentioned above

## Permissions Explanation

The Extension requires the following permissions:

### `activeTab`

**Purpose:** Access the current Pinterest tab to read board information  
**Data Access:** Only the current Pinterest board URL and page content  
**Usage:** Required to identify which board to download

### `host_permissions` (pinterest.com and pinimg.com)

**Purpose:** Access Pinterest.com content and media files  
**Data Access:** Public board data (images, videos, titles)  
**Usage:** Required to download pins from Pinterest boards

### `host_permissions` (supabase.co)

**Purpose:** Send anonymous usage analytics  
**Data Access:** Only anonymous usage statistics (event type, format, pin count, anonymous user ID)  
**Usage:** Required for analytics to improve the extension. No personal data is transmitted.

## Children's Privacy

The Extension does not knowingly collect information from children under 13 years of age. If you are under 13, please do not use this Extension.

## Analytics

The Extension collects anonymous usage analytics to understand how the extension is used and improve it. The analytics data includes:

- **Anonymous User ID:** A randomly generated UUID stored in your browser's localStorage. This ID cannot be used to identify you.
- **Event Types:** Types of actions performed (e.g., opening the modal, starting a download)
- **Format Selection:** Whether ZIP or PDF format was selected
- **Pin Counts:** Number of pins processed (for statistical purposes only)
- **Timestamps:** When events occurred

**What is NOT collected:**

- Personal identification information
- Pinterest account information
- Browsing history outside of Pinterest
- IP addresses or location data
- Any content of pins or boards

Analytics data is stored securely in our Supabase database and is only used for statistical analysis. You cannot be identified from this data.

## Third-Party Services

The Extension interacts with:

- **Pinterest.com** - to fetch public board data and download media files
- **Supabase (supabase.co)** - to store anonymous usage analytics
- **Your Browser** - to save downloaded files and store anonymous user ID

No other third-party services are used.

## Data Security

- All data processing happens locally in your browser
- Only anonymous usage analytics are transmitted to our analytics service (Supabase)
- Downloaded files are saved directly to your device
- Anonymous analytics data is stored securely in our Supabase database with Row Level Security (RLS) policies
- No personal data is stored on external servers

## Your Rights

The Extension collects only anonymous usage analytics. You have the following rights:

- **Access:** You can view the anonymous user ID stored in your browser's localStorage (check browser DevTools → Application → Local Storage)
- **Delete:** You can clear your browser's localStorage to remove the anonymous user ID. A new anonymous ID will be generated on next use
- **Opt-out:** Analytics collection is automatic but does not affect extension functionality. If you prefer not to send analytics, you can block requests to `*.supabase.co` using browser extensions or network settings

Since no personal data is collected, there is no personal data to modify or export.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. Any changes will be posted on this page with an updated "Last Updated" date.

## Contact Us

If you have any questions about this Privacy Policy, please contact us:

- **Email:** shemmmil1996@gmail.com

## Compliance

This Extension complies with:

- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)

## Consent

By using the Extension, you consent to this Privacy Policy.

---

**Summary:**

- ✅ No personal data collection
- ✅ Only anonymous usage analytics (cannot identify you)
- ✅ All content processing happens locally
- ✅ Anonymous analytics stored securely
- ✅ Open source code
- ✅ Full transparency

**Your privacy is our priority.**
