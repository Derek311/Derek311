### Hi, I'm Derek 👋

Backend and full-stack developer with 4 years of full-time industry experience —
Java/Spring on a national healthcare platform in China, and ongoing production
C#/.NET work for an Australian company. Currently completing a Master of IT at
the University of Waikato in New Zealand.

I care about production-grade code, durable patterns, and writing things that
other developers can read without a meeting.

---

#### What I work with

**Backend** · Java, Spring Boot, Spring Cloud, MyBatis · C#, ASP.NET Core, ABP Framework, EF Core
**Frontend** · Vue 2 / Vue 3, React, TypeScript · Next.js, MapLibre
**Data** · Oracle, MySQL, SQL Server, PostgreSQL / PostGIS · query optimisation, AWR-driven SQL tuning
**Spatial** · ArcGIS Pro, ArcPy, pgRouting · Python
**DevOps** · Docker, Linux, Nginx, Azure DevOps, GitLab + Jenkins
**AI in practice** · OpenAI API in production (token + cost accounting) · Claude Code, Cursor
**Practice** · REST APIs, Stripe payments, JWT auth, role-based access, pull-request workflow

#### Currently

🗺️ Building [`walkreach`]— a walkability
tool for Hamilton. Computes what a location reaches on foot in 5/10/15 minutes
along the street network rather than in a straight line, using PostGIS and
pgRouting over a 37,500-edge OpenStreetMap graph.

🔀 Contributing to [Mealie](https://github.com/mealie-recipes/mealie), an established
open-source recipe manager — working to the project's own conventions and review
process, with changes merged upstream into main.

🎓 Master of IT @ University of Waikato (Feb 2026 – Apr 2027). A+ in both graduate
GIS papers; final project scripted end to end in Python/ArcPy.

💼 Open to 2026/27 summer internships in New Zealand, and to graduate roles from
Apr 2027 when I become eligible for a Post-Study Work Visa.

#### Some things I've built

**[Hungry Rescue Map](https://hungry-rescue-map.vercel.app)** — restaurant busyness
map for Auckland CBD on live Google Places data. University group project; I built
the data layer, including the panel that explains why each estimate was given, so
users can judge the number rather than accept it.

**Stripe payments (T1Education)** — hosted Checkout sessions, signature-verified
webhooks with correct retry semantics, and single-row CAS idempotency so replayed
events never double-post, with gateway records mapped back to the internal order
ledger. Also replaced an inherited token scheme that hardcoded its key and never
enforced its own expiry, migrating to HS256 JWT.

#### Background

- **Apr 2021 – Feb 2025** · Java Developer, Neusoft Group, China
Engineered backend services for a national healthcare claim and settlement platform
serving ~80,000 pharmacies across 3+ provincial deployments; owned specific modules
in the shared product core. Diagnosed slow settlement APIs through Oracle AWR
analysis, and resolved a multi-node cache inconsistency via Nginx upstream
sticky-session routing — a config change rather than a code change.

- **Sep 2025 – present** · Software Developer (remote), MPoint / T1Education, Australia
Architected the T1Education Spring Boot backend from scratch. Built an OpenAI-backed
treatment analysis service into a mature .NET / ABP healthcare SaaS, with token and
cost accounting to keep responses within model limits.

---

📫 <liudi311@outlook.com> · [LinkedIn](https://linkedin.com/in/derek-di-liu) · Hamilton, New Zealand
