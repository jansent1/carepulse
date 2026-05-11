# CarePulse
Een patiëntenbeheer systeem gebouwd met Next.js en TypeScript.
CarePulse stelt zorgverleners in staat om patiëntregistraties, afspraken en notificaties te beheren via een moderne web interface.

## Functionaliteiten

- Patiëntenregistratie en -beheer
- Afsprakenbeheer
- SMS-notificaties via Twilio
- Beveiligde opslag via Appwrite
- Responsief dashboard

## Tech stack

Next.js 14 — App Router
TypeScript — volledig getypeerd
Tailwind CSS — styling
shadcn/ui — componentbibliotheek
Appwrite — backend als service (database, authenticatie)
Twilio — SMS-notificaties

## Lokaal draaien
**Vereisten: Node.js, een Appwrite-instantie en een Twilio-account.**
```` bash
git clone https://github.com/jansent1/carepulse.git
cd carepulse
npm install
npm run dev
````
Maak een .env.local aan met je Appwrite- en Twilio-credentials (zie .env.example als die aanwezig is).
Open http://localhost:3000 in je browser.

## Leerpunten
Dit project was mijn eerste hands-on ervaring met Appwrite als BaaS en Twilio voor SMS-integratie. Het leerde me hoe je authenticatie en realtime data buiten je eigen backend om organiseert — nuttige kennis voor het begrijpen van hoe moderne webapplicaties omgaan met externe services en API-koppelingen.
