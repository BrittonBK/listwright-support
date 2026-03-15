# ListWright Privacy Policy

**Last Updated: March 14, 2026**

## Overview

ListWright is a task management app that uses Claude AI (by Anthropic) to help you organize your tasks. Your privacy is important to us. This policy explains what data ListWright handles and how.

## Data Storage

All of your data is stored on your device using Apple's SwiftData framework. This includes:

- **Task data** — titles, descriptions, due dates, categories, action items, reminders, and deferral history
- **Profile data** — your name, roles, work schedule, and the personal context generated during onboarding
- **AI interaction history** — Claude's responses, task suggestions, and any clarification questions and your answers

ListWright does not have its own servers, databases, or cloud storage. We do not collect, store, or have access to any of your data.

## iCloud Sync (Optional)

ListWright offers optional iCloud sync to keep your tasks in sync across your iOS devices. This feature is **off by default** and must be explicitly enabled by you during initial setup or in Settings.

When iCloud sync is enabled, your task data, profile data, and AI interaction history (as described in Data Storage above) are stored in your personal iCloud account using Apple's CloudKit. This data is managed entirely by Apple under their iCloud terms and privacy policy. ListWright does not operate the sync infrastructure — Apple does.

The following data is **never synced** and remains only on the local device:

- Your **Anthropic API key** (stored in the device Keychain)
- **Device-specific state** such as notification scheduling and activity timestamps
- **Offline queue items** (pending task submissions made while offline)
- **API usage logs** (token counts and estimated costs for your reference)

You can disable iCloud sync at any time in Settings. When disabled, your data remains on your device and is no longer uploaded to iCloud.

## Anthropic API Key

ListWright uses a bring-your-own-key (BYOK) model. You provide your own Anthropic API key to enable AI features. Your API key is stored securely on your device using Apple's Keychain Services. We never transmit, collect, or have access to your API key.

## Data Sent to Anthropic

When you use AI-powered features (task creation, Plan for Tomorrow, Ask Claude), data is sent directly from your device to Anthropic's API servers to be processed by Claude. This includes your task-related text, your personal context (generated during onboarding), and relevant existing task data for context. This communication occurs over encrypted HTTPS connections.

The data sent to Anthropic is governed by **Anthropic's Usage Policy and Privacy Policy** (https://www.anthropic.com/privacy). ListWright does not act as an intermediary — your device communicates directly with Anthropic's servers using your own API key.

We encourage you to review Anthropic's privacy policy to understand how they handle data sent to their API.

## Data We Collect

**None.** ListWright does not collect, transmit, or store any personal data, analytics, usage metrics, crash reports, or device identifiers on our own servers. We have no servers and no way to receive data from your device. If you enable iCloud sync, your data is stored in your personal iCloud account, managed by Apple.

## Third-Party Services

The only third-party service ListWright communicates with is the Anthropic API, and only when you initiate an AI-powered action. No advertising networks, analytics services, or tracking tools are used.

## Notifications

ListWright may request permission to send local notifications for task reminders and planning prompts. These notifications are generated and scheduled entirely on your device. No notification data is sent externally.

## Children's Privacy

ListWright is not directed at children under 13 and does not knowingly collect any data from children.

## Changes to This Policy

If we update this privacy policy, we will post the revised version here with an updated date. Continued use of the app constitutes acceptance of any changes.

## Contact

If you have questions about this privacy policy, please contact:

**Email:** britton@brittonkilpatrick.com

---

*This privacy policy applies to the ListWright iOS app.*
