# Adam Liscia

Software engineer in the New York area. Former classroom mathematics teacher.

I build and run production systems end to end — schema and API through nginx, systemd and
TLS. Three of the services below I designed, built and deployed to AWS on my own.

### What I'm building

**[nerdleagues.com](https://nerdleagues.com)** — a competitive Magic: The Gathering league
and deck platform. Flask, MySQL on RDS, Socket.IO, a production Anthropic API pipeline.
**620 registered users, 294 of them signed in within the last 90 days** *(2026-09-17)*.
Built with my brother; I've written most of the code and we've run weekly reviews on it for
two and a half years, across 98 merged pull requests.

**[nerdleagues.tv](https://nerdleagues.tv)** — a channel-surfing "TV network" for tabletop
gaming, aggregating hand-picked Twitch and YouTube creators across six games into one
persistent player. Official embeds only. **Built alone, empty repository to public TLS in
24 days**, including the RDS provisioning, data migration, systemd unit, nginx config and
certificates.

**[api.barcraft.social](https://api.barcraft.social)** — a cocktail application for working
bartenders. FastAPI + SQLAlchemy backend live under gunicorn and nginx, Expo/React Native
client serving web, iOS and Android from one codebase, API client generated from OpenAPI.
**300-test pytest suite**, 20 Alembic migrations, and a migration from PostgreSQL to MySQL
done in production.

**Nerd Leagues mobile** — React Native on Expo Router, **published to both the iOS App
Store and Google Play**. Sole author, and it ships its own Node.js/Express API that I wrote
and deployed to EC2 separately from the Flask backend.

### A note on the repo list below

Most of my work lives in private repositories, so the public list here is old and doesn't
represent it. The contribution graph is the more accurate picture. Happy to walk through
any of the codebases above in detail.

### Working with

`Python` `TypeScript` `JavaScript` `SQL` · `Flask` `FastAPI` `Node/Express` `SQLAlchemy`
`React` `React Native` `Expo` `Vite` · `MySQL` `PostgreSQL` · `AWS (EC2, RDS, S3)` `nginx`
`gunicorn` `systemd` `Let's Encrypt` `Cloudflare` · `Anthropic API`

### Before this

Seven years teaching mathematics and computer science — New York City Department of
Education, homeschool curriculum design, and 100+ private students. I taught Python before
I built in it. Mathematics degree, Stony Brook University.

📫 adamliscia@gmail.com · [LinkedIn](https://www.linkedin.com/in/adam-liscia-b73555138)
