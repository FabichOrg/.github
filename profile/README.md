<h1 align="center">Projects</h1>

<p align="center">
  <sub>Modular Websites and Meetem.<br />
  Modular Websites et Meetem.</sub>
</p>

<p align="center">
  <a href="#modular-websites">Modular Websites</a> · <a href="#meetem">Meetem</a>
</p>

---

<h2 id="modular-websites">Modular Websites</h2>

**One platform, many online shops.** Une plateforme pour exploiter des boutiques en ligne :
un seul code, une seule version, et des boutiques qui ne se ressemblent pas.

Modular Websites is a modular e-commerce platform for Swiss merchants. Every shop runs the same
code and the same release, and what makes two shops differ is data, never code: its identity, the
modules it switches on, its languages, the vocabulary of its catalogue and its look. A merchant's
request becomes a feature for every shop, or it is declined. Optional means absent: a module a
shop has not enabled does not exist for its visitors.

Prismea, a Swiss trading-card shop, is the first shop running on it: [prismea.ch](https://prismea.ch).

| Area            | What it does                                                                           |
| --------------- | -------------------------------------------------------------------------------------- |
| Shops           | Each shop has its own identity, domain, colours, type faces, header and transactional mails |
| Modules         | A core of commerce, plus optional modules: promotions, loyalty, reviews, pre-orders, supplier catalogues, campaigns, accounting |
| Storefront      | Catalogue with faceted search, variants, galleries, and its own vocabulary of conditions and properties |
| Checkout        | Guest and account checkout, card and TWINT through Stripe, stock held while the customer pays |
| Languages       | Content translated beside the original; a language is written before it is enabled    |
| Accounting      | VAT, numbered receipts, an append-only ledger and its reports                          |
| Back office     | Catalogue, orders, customers, returns, shipping labels, and a shop's settings          |
| Trading-card pack | Optional, for shops that sell cards: Cardmarket prices, grading batches, collection buyback |

Next.js on the front, Express and Prisma over PostgreSQL on the back, sharing schema and
business-rule packages.

<p>
  <img alt="Next.js" src="https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white" />
  <img alt="Express" src="https://img.shields.io/badge/Express-404d59?logo=express&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2d3748?logo=prisma&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white" />
  <img alt="Stripe" src="https://img.shields.io/badge/Stripe-635bff?logo=stripe&logoColor=white" />
</p>

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

## How I build

I hold both projects to the same rules:

- **Nothing is trusted from the client.** Prices, totals and who may see what are decided on the
  server.
- **Tests run against the real thing:** a real database, over HTTP, without mocks.
- **Every change passes one gate** (lint, types, tests, secret and dependency scanning) before
  it ships.
- **The reasoning lives with the code,** in decision records next to it.

The application code is private: it runs live shops and holds personal data. This organisation
is their public face.

<p align="center"><sub>Switzerland</sub></p>
