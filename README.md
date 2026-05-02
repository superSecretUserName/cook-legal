# Privacy Policy — Cook: An Experiment

**Last updated:** May 1, 2026

Cook: An Experiment ("the app") is a cooking coach app for iOS. This policy describes what data the app collects, how it's used, and who it's shared with.

## What the app collects

**Account information.** The app uses Sign in with Apple for authentication. Apple provides a unique user identifier, and optionally your name and email address if you choose to share them. The app does not store your Apple ID password.

**Profile information.** During onboarding, the app asks about your cooking skill level, dietary restrictions, food preferences, and kitchen equipment. You can edit this information at any time in the Profile tab.

**Recipe content.** Recipes you add — including titles, ingredients, steps, tags, and notes — are stored on your device. If you add a recipe by photographing a cookbook or pasting text, that content is processed to extract structured recipe data.

**Chat messages.** Conversations you have with the cooking coach about your recipes are stored on your device.

## How the app uses your data

**On-device storage.** All profile, recipe, and chat data is stored locally on your device using Core Data.

**iCloud sync.** If iCloud is enabled on your device, your data syncs across your Apple devices via CloudKit. Apple manages this sync infrastructure. See [Apple's iCloud privacy overview](https://support.apple.com/en-us/102651) for details.

**AI processing.** Recipe extraction, chat, and onboarding use Anthropic's Claude API to process your requests. When you use these features, the relevant content (recipe text or photo, chat messages, your profile context) is sent to Anthropic's servers for processing. Anthropic's data handling is governed by their [privacy policy](https://www.anthropic.com/privacy). The app sends only the content needed to fulfill your request — it does not send your full recipe library or chat history.

## What the app does not do

- The app does not sell your data.
- The app does not show ads.
- The app does not track you across other apps or websites.
- The app does not collect analytics or usage telemetry in this beta version.

## Data retention

Your data stays on your device (and in iCloud if enabled) until you delete it. Deleting a recipe archives it locally rather than destroying it. Signing out clears your local session. Uninstalling the app removes all local data; iCloud data can be managed through your device's iCloud settings.

Data sent to Anthropic for AI processing is handled according to Anthropic's data retention policies. The app uses Anthropic's API, which does not use submitted data for model training.

## Third-party services

| Service | Purpose | Data shared |
|---------|---------|-------------|
| Apple (Sign in with Apple) | Authentication | Apple user identifier |
| Apple (CloudKit) | Device sync | All app data (encrypted in transit and at rest) |
| Anthropic (Claude API) | AI features | Recipe content, chat messages, profile context per request |

## Children's privacy

The app is not directed at children under 13 and does not knowingly collect data from children.

## Contact

If you have questions about this policy, contact Daniel Schultz at [your email address].

## Changes

This policy may be updated as the app develops. Material changes will be communicated through TestFlight release notes.
