<h1 align="center">Fab Org</h1>

<p align="center">
  <strong>Two products, built in-house in Switzerland.</strong><br />
  Deux projets, construits de A à Z en Suisse.
</p>

<p align="center">
  <a href="#prismea">Prismea</a> · <a href="#meetem">Meetem</a>
</p>

---

<h2 id="prismea">
  <img src="assets/logo.png" alt="" width="28" align="center" /> Prismea
</h2>

**Swiss trading-card retail, built in-house.** Boutique TCG suisse — Pokémon, One Piece, scellé,
singles et cartes gradées.

<a href="https://prismea.ch">prismea.ch</a> · <a href="https://discord.gg/k9jXt7UW4C">Discord</a>
· <a href="https://www.instagram.com/prismea_">Instagram</a> ·
<a href="https://www.tiktok.com/@prismea_">TikTok</a>

Prismea is a trading-card shop based in Yverdon-les-Bains. We sell sealed product, singles and
graded slabs, buy collections back from customers, and handle grading submissions on their
behalf. We build and run our own storefront rather than renting one: pricing against live market
data, reserving stock honestly during checkout and valuing a collection are exactly the parts an
off-the-shelf platform treats as generic.

| Area           | What it does                                                                     |
| -------------- | -------------------------------------------------------------------------------- |
| Storefront     | Catalogue with faceted search, galleries, price-trend history, graded-card detail |
| Checkout       | Guest and account checkout, card / TWINT / PayPal, stock reserved atomically     |
| Rachat         | Collections submitted card by card or as a lot, live valuations, tracked offers  |
| Grading        | Submission intake and status tracking through to the returned grade              |
| Loyalty        | Points earned per order, spendable at checkout                                   |
| Back office    | Catalogue, CSV and scan import, orders, customers, buyback and grading queues    |

Next.js on the front, Express and Prisma over PostgreSQL on the back, sharing schema and
business-rule packages.

<p>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white" />
  <img alt="Express" src="https://img.shields.io/badge/Express-404d59?logo=express&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2d3748?logo=prisma&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white" />
  <img alt="Stripe" src="https://img.shields.io/badge/Stripe-635bff?logo=stripe&logoColor=white" />
</p>

Customers: support@prismea.ch, or find us on Discord.

---

<h2 id="meetem">Meetem</h2>

**A social map to meet people for real.** Une carte pour voir qui est autour de toi et se
retrouver pour de vrai.

Meetem is a mobile app (iOS and Android) built around a live map: friends who are free right
now, meets to join — a drink, a dinner, a board-game night — and the public places they happen
in. Privacy comes first: nobody is shown where you are unless you choose to, a position is only
ever shared blurred, and a meet's exact address is revealed only to the people taking part.
Meetem is in development.

<p>
  <img alt="React Native" src="https://img.shields.io/badge/React_Native-20232a?logo=react&logoColor=61dafb" />
  <img alt="Expo" src="https://img.shields.io/badge/Expo-000020?logo=expo&logoColor=white" />
  <img alt="NestJS" src="https://img.shields.io/badge/NestJS-e0234e?logo=nestjs&logoColor=white" />
  <img alt="PostGIS" src="https://img.shields.io/badge/PostGIS-336791?logo=postgresql&logoColor=white" />
  <img alt="Redis" src="https://img.shields.io/badge/Redis-dc382d?logo=redis&logoColor=white" />
  <img alt="Mapbox" src="https://img.shields.io/badge/Mapbox-000000?logo=mapbox&logoColor=white" />
</p>

---

## How we build

Both projects hold themselves to the same rules:

- **Nothing is trusted from the client.** Prices, totals and who may see what are decided on the
  server.
- **Tests run against the real thing:** a real database, over HTTP, without mocks.
- **Every change passes one gate** (lint, types, tests, secret and dependency scanning) before
  it ships.
- **The reasoning lives with the code,** in decision records next to it.

The application code is private: it runs a live shop and holds personal data. This organisation
is their public face.

<p align="center"><sub>Switzerland</sub></p>
