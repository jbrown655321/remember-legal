# Privacy Policy

**Last updated: July 19, 2026**

Aligned Systems LLC ("we," "our," or "us"), a Tennessee limited liability company, operates the Remember mobile application (the "App"). This Privacy Policy explains how we collect, use, disclose, and protect your information.

## Information We Collect

### Account Information
When you create an account, we collect:
- Email address (for email sign-up) or authentication-provider identifiers (for Apple/Google Sign In)
- Display name (optional, provided during onboarding)
- User ID (generated upon account creation)

### Content You Create
The App stores content you voluntarily provide, including:
- Text entries (memories, notes, lists, reminders)
- Photos you choose to upload
- Thread/category names and organization

### AI-Processed Data
To provide intelligent features, the App submits portions of your entries to OpenAI's API (via a secure server-side proxy) for processing. This content **may include personal information** contained in your entries, such as names, locations, and other details you write about. We do not intentionally transmit account credentials or use your content to identify you for advertising purposes.

AI processing generates:
- Titles, summaries, and extracted facts
- People, places, emotions, and relationship data
- Searchable vector embeddings
- Reminder dates and thread suggestions

### Automatically Collected Information
- **Device and app information**: operating system version and app version, collected incidentally through standard platform operation
- **Push notification tokens**: if you enable notifications
- **IP address and server logs**: collected incidentally by our hosting infrastructure (Supabase)
- **Subscription status and purchase history**: managed by Apple through StoreKit
- **Crash and diagnostic information**: if enabled through Apple's standard crash reporting

### Information We Do NOT Collect
- We do not use advertising SDKs or collect advertising identifiers
- We do not collect location data
- We do not collect contacts, health, or financial data
- We do not engage in cross-context behavioral advertising or tracking

## How We Store Your Data

We use reasonable administrative, technical, and physical safeguards to protect your information. However, no method of transmission or storage is completely secure, and we cannot guarantee absolute security.

- Your data is stored in Supabase (built on PostgreSQL) with access controls, including row-level security, designed to prevent one user from accessing another user's data
- Authorized personnel and service providers may access data when reasonably necessary for support, security, legal compliance, or operation of the App
- Photos are stored in Supabase Storage with authenticated access controls
- All data transmission uses HTTPS encryption
- Local data is cached on your device using Apple's SwiftData framework

## How We Use Your Data

Your data is used solely to:
- Provide the App's core functionality (storing and organizing your entries)
- Power AI features (extraction, search, insights)
- Sync your data across your devices
- Send notifications you've configured (reminders, daily prompts)
- Process subscriptions and purchases
- Respond to support requests
- Comply with legal obligations

## How We Disclose Your Data

We do not sell personal information or share it for cross-context behavioral advertising. We disclose information to service providers as necessary to operate the App, as described below.

We may also disclose information:
- To comply with applicable law, regulation, legal process, or governmental request
- To protect the safety, rights, or property of our users, ourselves, or the public
- In connection with a merger, acquisition, or sale of assets (you would be notified of any change in ownership or control)
- With your direction or consent

## Third-Party Services

| Service | Purpose | Data Shared |
|---------|---------|-------------|
| Supabase | Authentication, database, file storage, server logs | Account info, entries, photos, IP addresses |
| OpenAI (via server proxy) | AI text processing | Entry text, which may contain personal information |
| Apple Sign In | Authentication | Apple ID token, email or relay email |
| Google Sign In | Authentication | Google ID token, email, display name |
| Apple App Store / StoreKit | Subscription management | Purchase and subscription status |
| Apple Push Notification service | Notifications | Push notification tokens |

**OpenAI data handling**: Under OpenAI's API data usage policy, API inputs and outputs are not used to train OpenAI's models by default. OpenAI may retain API data for up to 30 days for abuse monitoring purposes. We recommend reviewing [OpenAI's API data usage policies](https://openai.com/policies/api-data-usage-policies) for current details.

**International transfers**: Our service providers may process data in the United States and other countries. By using the App, you consent to the transfer of your information to these locations.

## Data Retention

- **Account and content data**: retained as long as your account is active
- **Server logs**: retained by Supabase according to their standard retention policies
- **AI-provider records**: OpenAI may retain API data for up to 30 days for abuse monitoring
- **Backup data**: may persist in automated backups for a limited period after deletion
- **Purchase records**: retained by Apple according to their policies
- **Support communications**: retained as long as reasonably necessary

## Data Deletion

You can delete your entire account and all associated data from Settings > Delete Account. Upon deletion:
- Your entries, threads, knowledge, photos, and authentication data are deleted from our active systems
- Some information may temporarily persist in automated backups or service-provider logs before being purged according to standard retention schedules
- AI-provider abuse-monitoring logs are retained and deleted according to OpenAI's policies
- We cannot delete records retained by Apple for purchase and subscription management

We authenticate deletion requests through your active app session. You must be signed in to delete your account.

## Data Export

You can export all your data as JSON at any time from Settings > Export Data.

## Children's Privacy

The App is not directed at children under 13, and users under 13 may not create accounts. We do not knowingly collect personal information from children under 13. If we learn that we have collected information from a child under 13, we will promptly delete that information. If you believe a child under 13 has provided us with personal information, please contact us.

## Your Rights

Depending on your jurisdiction, you may have the right to:
- **Access** your data (via the App or Export feature)
- **Correct** your data (edit any entry or thread within the App)
- **Delete** your data (Delete Account in Settings)
- **Export** your data (Export Data in Settings)
- **Object** to or restrict certain processing

To exercise these rights, use the in-app features or contact us at the email below. We will respond to verifiable requests within a reasonable timeframe. We will not discriminate against you for exercising your rights.

### California Residents
Under the California Consumer Privacy Act (CCPA), California residents have additional rights regarding their personal information, including the right to know what personal information is collected, the right to delete, and the right to opt out of the sale of personal information. We do not sell personal information. To exercise your rights, contact us or use the in-app features described above.

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of material changes through the App or via email. The "Last updated" date at the top indicates when the policy was last revised. Continued use of the App after changes constitutes acceptance of the updated policy.

## Contact Us

If you have questions about this Privacy Policy, contact us at:

**Aligned Systems LLC**
**Email**: support@alignedsystems.com

---

Aligned Systems LLC
