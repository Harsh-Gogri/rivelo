# Rivelo

**Share your details in one tap. No typing, no searching.**

Rivelo is a networking app that turns your contact details and links into customizable home screen widgets. Tap a widget and it reveals a QR code. The person in front of you scans it with their normal camera and gets your details instantly.

> **Status: design phase.** Product scope, flows and the home screen design are done. The app is not built yet.

## Why the name

Rivelo is a coined name built around the idea of **revealing**. That is the core moment of the product: your widget looks like a small, personal tile on your home screen, and with one tap it reveals the QR code that holds your details.

## The problem

Exchanging contact details in person is still clumsy. You dictate a number, spell an email, or hunt for the right profile. AirDrop only works when both people have iPhones. Everyone else ends up typing.

## What it does

- **Create Tiles** for the things you share most. A Tile is the in-app object you create and customize.
- **Customize** each Tile with an image or effect so it reflects your personal brand.
- **Place a Tile on your home screen** as a real widget.
- **Tap the widget** to reveal your QR code. The other person scans it with their camera, with no app install needed on their side.

### Terminology

| Term | Meaning |
|---|---|
| **Tile** | The in-app object you create and customize. |
| **Widget** | The home screen version of a Tile. A Tile becomes a widget once you place it on your home screen. |

## MVP (Android only)

The first version focuses on a few distinct categories:

- **Email**
- **Contact** (name, phone, company and more, as one contact card)
- **Website** (portfolio, business page, booking link, review link)
- **Socials** (LinkedIn, Instagram, X, Facebook, YouTube, Substack, Medium and more)

Also in the MVP:

- Sign in with Google, with Tiles synced to your account so they survive a reinstall
- Android home screen widgets with tap-to-reveal
- Free, fully unlocked

## Roadmap

Planned stages after the Android MVP, in order:

1. **iOS:** bring Rivelo to iPhone, with widgets.
2. **Profile Card:** all your categories in one place, as a single Tile and a hosted page you can share with a link.
3. **B2B:** organizations with an admin console and settings, for teams that want consistent, manageable contact cards.
4. **AI networking:** recording and AI assistance for the conversations you have while networking.

## Planned tech stack

- React Native with Expo, built with the help of an AI coding agent
- Supabase for authentication, database and sync
- Native Android widgets (Glance), with WidgetKit for iOS later
- EAS for cloud builds and store submission

## Design preview

![Thumbnail](./assets/images/thumbnail)
