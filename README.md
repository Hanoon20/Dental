# Mishary Dental Care — Premium Demo Website

A responsive React + Vite premium dental clinic demonstration website. Includes a homepage, services directory, individual service pages, about, appointment request, contact, FAQ and mobile navigation.

## Local development

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Netlify deployment

1. Push the folder to a GitHub repository.
2. Import the repository into Netlify.
3. Build command: `npm run build`; publish directory: `dist`.
4. `netlify.toml` contains the required SPA redirects.

## Customize before going live

Edit `src/config.js` with real clinic details and a WhatsApp Business number in international digits-only format (for example `947XXXXXXXX`). **A test WhatsApp number is configured**. Booking submissions open a WhatsApp message draft addressed to the test number; the user must send it. Replace it with the clinic's approved number before launch. Change the demo disclaimer/footer when converting this project to a real website, but only after verifying all claims, services and clinical information.

The current brand is a temporary typographic logo. Replace `Brand()` in `src/main.jsx` with the clinic's approved logo later. Replace the remote stock photography with licensed clinic images before public launch. Treat all site copy as demonstration content — no real dentist credentials, clinic address, reviews, outcomes or patient count have been claimed.

## Privacy

The website does not store form data, does not have a backend, and does not automatically send WhatsApp messages. After configuring the WhatsApp number, the booking button opens a user-controlled WhatsApp message draft. The clinic must separately confirm appointments. Do not put medical history or sensitive medical notes in a third-party message without an appropriate clinical/privacy process.
