# Mobiliario Paty — Website Demo

[Español](README.es.md)

Responsive commercial website concept for **Mobiliario Paty**, an event furniture, tent, and equipment rental business serving Saltillo and nearby municipalities.

The demo presents the business's services in a clearer format and helps potential clients prepare an organized inquiry before continuing the conversation on WhatsApp.

## Live Demo

**[View the deployed website](https://resilient-madeleine-0dbb7b.netlify.app)**

## Main Features

- Responsive layout for mobile, tablet, and desktop devices
- Service and inventory presentation for different event needs
- Interactive event planner with date, location, guest count, and service selection
- Preformatted WhatsApp inquiry generated from the visitor's answers
- Photo gallery and three-step service process
- Mobile navigation and persistent WhatsApp contact button
- Semantic HTML, keyboard focus states, skip navigation, and reduced-motion support
- Open Graph metadata and a basic search description
- No framework, package manager, build process, or external JavaScript dependency

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Netlify for deployment

## Project Structure

```text
mobiliario-paty-demo/
├── assets/
│   ├── carpa-evento.jpg
│   ├── carpa-grande.jpg
│   ├── hero-evento.jpg
│   └── montaje-mesas.jpg
├── index.html
├── README.md
└── README.es.md
```

## Run Locally

No installation is required. Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/josecontactdev-cloud/mobiliario-paty-demo.git
cd mobiliario-paty-demo
```

For a local development server, you can use Python:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## How the WhatsApp Flow Works

1. The visitor enters their name, event type, date, location, and estimated guest count.
2. They select the services they are interested in and can add extra details.
3. The website prepares a structured message and opens WhatsApp.
4. The visitor reviews the message before choosing whether to send it.

The demo does not calculate prices, confirm availability, submit information automatically, or create a reservation.

## Current Scope

This repository contains a front-end concept created for commercial validation. Business information, photographs, services, coverage, and final copy must be reviewed and approved by Mobiliario Paty before production use.

## Possible Next Steps

- Replace concept content with the business's official information
- Add a complete inventory and package catalog
- Connect analytics to measure inquiry conversions
- Add structured data and production SEO metadata
- Connect a content management system for easier updates
- Add availability or lead-management integrations if required

## Author

Developed by [José](https://github.com/josecontactdev-cloud).

## Usage Notice

This is a commercial demonstration. The repository does not include an open-source license, and its content and visual assets should not be reused without the corresponding permission.
