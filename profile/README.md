<h1 align="center">Projects</h1>

<p align="center">
  <sub>Modular Websites and Meetem.</sub>
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

<h2 id="newsgenerator">NewsGenerator</h2>

**A news briefing written for each reader.** Un briefing de presse sur mesure : on écrit avec ses
mots ce qu'on veut lire, et les médias sont lus à sa place.

NewsGenerator is a personalised news generator. All day it reads thousands of feeds in many
languages, groups the articles that tell the same fact into stories and the stories of one affair
into threads, then writes each reader a briefing from a profile written in their own words. Every
card shows the article's own key sentences as published (not rewritten, and a translation is
marked as one), who else tells the news, who denies it and where a party said it
itself. It says how widely a news is carried and how its article credits its sources, never
whether it is true.

It started at school as my TPI, the individual project that closes the vocational training, and
I kept building it afterwards. Its code is public, in its own organisation:
[Backend](https://github.com/TPI2026-NewsGenerator/NewsGenerator-Backend) ·
[Frontend](https://github.com/TPI2026-NewsGenerator/NewsGenerator-Frontend).

| Area            | What it does                                                                           |
| --------------- | -------------------------------------------------------------------------------------- |
| Reading         | Thousands of feeds read every minute, searches of Google News for each reader's interests, and the sources a reader adds |
| Understanding   | Multilingual vectors (bge-m3) group articles into stories and affairs; people and organisations are found and linked to Wikidata |
| Profile         | A profile in the reader's own words, split into interests by an AI that can ask a few questions first |
| Briefing        | The stories closest to the interests, chosen and checked by an AI: key passages, other angles, official sources, denials, an analysis on demand |
| Following       | Follow a club, a person, an organisation or an affair, with a timeline of its key events |
| API             | Keys for another system, which reads the news and the stories closest to a profile |

Express and Prisma over PostgreSQL with pgvector on the back, two small Python services for the
vectors and the names, Ollama for the AI, React with Vite and Tailwind on the front. It runs on
my own server, in Docker.

<p>
  <img alt="React" src="https://img.shields.io/badge/React-20232a?logo=react&logoColor=61dafb" />
  <img alt="Vite" src="https://img.shields.io/badge/Vite-646cff?logo=vite&logoColor=white" />
  <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-0f172a?logo=tailwindcss&logoColor=38bdf8" />
  <img alt="Express" src="https://img.shields.io/badge/Express-404d59?logo=express&logoColor=white" />
  <img alt="Prisma" src="https://img.shields.io/badge/Prisma-2d3748?logo=prisma&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-336791?logo=postgresql&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white" />
  <img alt="Ollama" src="https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ed?logo=docker&logoColor=white" />
</p>

---

## How I build

I work the same way on all three projects:

- **Architecture first.** I design the back end, the front end and the database myself before any
  feature: the boundaries, the data model, the rules. An AI then writes most of the implementation
  inside that frame, and I review it.
- **Rules are tested against the real thing.** Business rules and SQL run against a real database;
  only what is external (payments, mail, maps, the AI) is faked.
- **One gate for every change.** On Modular Websites and Meetem, lint, types, tests, secret and
  dependency scanning run in GitHub Actions, and nothing ships without passing. The more code an
  AI writes, the more this gate matters.
- **Decisions are written down, beside the code.** The code holds the logic; the reasons for a
  choice, what was rejected, and how it works, live in documentation next to it.

The application code of Modular Websites and Meetem is private. This organisation is their public face. NewsGenerator is the exception: its code
is public, in its own organisation.

<p align="center"><sub>Switzerland</sub></p>
