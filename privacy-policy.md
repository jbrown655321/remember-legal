# Privacy Policy

**Last updated: July 19, 2026**

Aligned Systems ("we," "our," or "us") operates the Remember mobile application (the "App"). This Privacy Policy explains how we collect, use, and protect your information.

## Information We Collect

### Account Information
When you create an account, we collect:
- Email address (for email sign-up) or authentication tokens (for Apple/Google Sign In)
- Display name (optional, provided during onboarding)

### Content You Create
The App stores content you voluntarily provide, including:
- Text entries (memories, notes, lists, reminders)
- Photos you choose to upload
- Thread/category names and organization

### AI-Processed Data
To provide intelligent features, the App processes your entries using OpenAI's API to:
- Generate titles and summaries
- Extract people, places, emotions, and facts
- Create searchable embeddings for the Ask feature
- Detect reminder dates and thread suggestions

This processing happens through our secure Supabase Edge Function proxy. We do not send your data directly to third-party AI services from your device.

### Automatically Collected Data
- We do **not** collect analytics, device identifiers, or usage tracking data
- We do **not** use advertising SDKs
- We do **not** sell or share your data with third parties

## How We Store Your Data

- Your data is stored securely in Supabase (built on PostgreSQL) with row-level security, ensuring only you can access your data
- Photos are stored in Supabase Storage with authenticated access controls
- All data transmission uses HTTPS encryption
- Local data is cached on your device using Apple's SwiftData framework

## How We Use Your Data

Your data is used solely to:
- Provide the App's core functionality (storing and organizing your memories)
- Power AI features (extraction, search, insights)
- Sync your data across your devices
- Send notifications you've configured (reminders, daily prompts)

We do **not** use your data for:
- Advertising or marketing to third parties
- Training AI models
- Profiling or behavioral targeting

## Third-Party Services

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| Supabase | Authentication, database, file storage | Account info, entries, photos |
| OpenAI (via Edge Function) | AI text processing | Entry text (no personal identifiers) |
| Apple Sign In | Authentication | Apple ID token |
| Google Sign In | Authentication | Google ID token |

## Data Retention and Deletion

- Your data is retained as long as your account is active
- You can export all your data as JSON at any time from Settings
- You can delete your entire account and all associated data from Settings > Delete Account
- Upon account deletion, all entries, threads, knowledge, photos, and authentication data are permanently removed from our servers

## Children's Privacy

The App is not directed at children under 13. We do not knowingly collect personal information from children under 13.

## Your Rights

You have the right to:
- **Access** your data (via the App or Export feature)
- **Correct** your data (edit any entry or thread)
- **Delete** your data (Delete Account in Settings)
- **Export** your data (Export Data in Settings)

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of significant changes through the App or via email.

## Contact Us

If you have questions about this Privacy Policy, contact us at:

**Email**: support@alignedsystems.com

---

Aligned Systems
