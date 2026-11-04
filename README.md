<div align="center">

# Fırat Atalay

**Backend Software Engineer** · Java & Spring Boot · C# & ASP.NET Core · PostgreSQL · Docker

I build backend systems that keep their data correct under real-world pressure:<br>
**concurrent requests, multiple tenants and failing services.**

<a href="https://mrfiratatalay.github.io/en/"><img src="https://img.shields.io/badge/Portfolio-mrfiratatalay.github.io-0D1117?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
<a href="https://mrfiratatalay.github.io/cv/firat-atalay.pdf"><img src="https://img.shields.io/badge/CV-PDF-0D1117?style=for-the-badge&logo=googledocs&logoColor=white" alt="CV" /></a>
<a href="https://www.linkedin.com/in/f%C4%B1rat-atalay-2581142b6/"><img src="https://img.shields.io/badge/LinkedIn-F%C4%B1rat_Atalay-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik00Ljk4IDMuNWEyLjUgMi41IDAgMSAxIDAgNSAyLjUgMi41IDAgMCAxIDAtNXpNMyA5aDR2MTJIM3pNOSA5aDMuOHYxLjdoLjA1Yy41My0xIDEuODMtMi4wNSAzLjc3LTIuMDVDMjAuNCA4LjY1IDIxIDExLjIgMjEgMTQuNVYyMWgtNHYtNS44YzAtMS40LS4wMy0zLjItMS45NS0zLjItMS45NSAwLTIuMjUgMS41Mi0yLjI1IDMuMVYyMUg5eiIvPjwvc3ZnPg%3D%3D" alt="LinkedIn" /></a>
<a href="https://medium.com/@firatatalay"><img src="https://img.shields.io/badge/Medium-%40firatatalay-000000?style=for-the-badge&logo=medium&logoColor=white" alt="Medium" /></a>
<a href="mailto:firatatalay.cs@gmail.com"><img src="https://img.shields.io/badge/Email-firatatalay.cs%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

🟢 **Open to backend engineering roles** · Java/Spring Boot or C#/ASP.NET Core · Konya, Türkiye

</div>

| 🏆 Turkcell Code Night | 🎓 TÜBİTAK 2209-A | 💼 Elasoft | ✍️ Medium |
|---|---|---|---|
| 1st place in Trabzon and All-Star finalist, as team captain | Funded capstone project: EduConnect | Internship, then a full-semester placement on live products | Articles in Huawei Developer and Stackademic, several over 4K reads |

<details>
<summary><b>🇹🇷 Türkçe okumak için tıklayın</b></summary>

<br>

Merhaba, ben Fırat Atalay. Recep Tayyip Erdoğan Üniversitesi Bilgisayar Mühendisliği mezunuyum ve Konya'da yaşıyorum.
**Java/Spring Boot** ve **C#/ASP.NET Core** ile backend geliştiriyorum. En çok verinin her koşulda doğru kalmasını
önemsiyorum: aynı anda gelen istekler, birbirinden ayrılması gereken firmalar, çöken servisler.

- 🏆 Turkcell Code Night Trabzon'da **takım kaptanı** olarak birincilik ve All-Star finalistliği
- 🎓 **TÜBİTAK 2209-A** desteği alan bitirme projemiz EduConnect: Ayşe Mandıralı ile geliştirdik, takım kaptanı bendim
- 💼 **Elasoft**'ta yaz stajı ve ardından bir dönemlik uzun dönem staj; pull request'ler ve kıdemli mühendislerden kod incelemesi
- ✍️ **Medium**'da Huawei Developer ve Stackademic yayınlarında yer alan İngilizce teknik yazılar

Öne çıkan dört projem **Constructor ERP**, **Turkcell SkillHub**, **ZekAI** ve **EduConnect** canlı demo olarak
yayında; kayıt ya da şifre gerekmeden denenebilir. Her birinin reposunda kararları gerekçeleriyle anlatan bir `docs`
klasörü var. Tüm projelerimin ayrıntılı anlatımı [portfolyomda](https://mrfiratatalay.github.io). Java/Spring Boot ya da
C#/ASP.NET Core ile **backend rollerine açığım**: [e-posta](mailto:firatatalay.cs@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/f%C4%B1rat-atalay-2581142b6/) · [CV](https://mrfiratatalay.github.io/cv/firat-atalay.pdf)

</details>

## Flagship projects

All four run as live demos with no sign-up and no password, and each repository has a docs folder that explains
every decision along with its trade-offs.

<table>
<tr>
<td width="46%">
<a href="https://iskeleerp.vercel.app/demo"><img src="https://mrfiratatalay.github.io/images/projects/constructor-erp/kapak.webp" alt="Constructor ERP: subcontractor progress on the desktop and a site chat on the phone" /></a>
</td>
<td width="54%">
<h3>Constructor ERP</h3>
A multi-tenant SaaS that replaces WhatsApp groups for running construction sites. Product owner and full-stack
developer in a team of two.
<ul>
<li>PostgreSQL row-level security on top of service filters; the app refuses to start if a table is unprotected.</li>
<li>Server-side sessions that end instantly; only SHA-256 hashes of tokens are stored.</li>
<li>Build-enforced size limits; one module's backend went from 3,622 to 2,336 lines.</li>
</ul>
<b>Java 25 · Spring Boot 4 · PostgreSQL · Vue 3</b><br>
<a href="https://iskeleerp.vercel.app/demo">Live demo</a> ·
<a href="https://github.com/mrfiratatalay/constructor-erp">Code</a> ·
<a href="https://mrfiratatalay.github.io/en/projects/constructor-erp/">Case study</a>
</td>
</tr>
<tr>
<td width="54%">
<h3>Turkcell SkillHub 🏆</h3>
A gamified skills platform that won 1st place at Turkcell Code Night Trabzon with me as team captain, then
rewritten from scratch.
<ul>
<li>XP is an append-only ledger; rankings are derived with SQL window functions, so no score can drift.</li>
<li>Quizzes are graded on the server in one locked transaction, so a double submission pays nothing.</li>
<li>Claude's suggestions are checked against the learner's real progress, with a rule-based fallback.</li>
</ul>
<b>Java 25 · Spring Boot 4 · PostgreSQL · React 19</b><br>
<a href="https://skillhub-turkcell.vercel.app">Live demo</a> ·
<a href="https://github.com/mrfiratatalay/Turkcell-Skillhub">Code</a> ·
<a href="https://mrfiratatalay.github.io/en/projects/turkcell-skillhub/">Case study</a>
</td>
<td width="46%">
<a href="https://skillhub-turkcell.vercel.app"><img src="https://mrfiratatalay.github.io/images/projects/turkcell-skillhub/kapak.webp" alt="Turkcell SkillHub: the sky map and the Night Clock on the desktop and on a phone" /></a>
</td>
</tr>
<tr>
<td width="46%">
<a href="https://zekai-platformm.vercel.app/login"><img src="https://mrfiratatalay.github.io/images/projects/zekai/kapak.webp" alt="ZekAI: the customer simulation on the desktop and an analysis verdict on a phone" /></a>
</td>
<td width="54%">
<h3>ZekAI</h3>
An AI decision platform for both sides of e-commerce, built in six days at HackAthon'26 with me as team captain.
<ul>
<li>Gemini only scores and cites reviews; a pure rule engine makes the purchase call.</li>
<li>One structured call instead of seven agents; results cached by product fingerprint.</li>
<li>We also built the marketplace; one auth scheme takes JWTs and seller API keys.</li>
</ul>
<b>ASP.NET Core 10 · FastAPI · Gemini · Next.js 16</b><br>
<a href="https://zekai-platformm.vercel.app/login">Live demo</a> ·
<a href="https://github.com/mrfiratatalay/btk-zekai">Code</a> ·
<a href="https://mrfiratatalay.github.io/en/projects/zekai/">Case study</a>
</td>
</tr>
<tr>
<td width="54%">
<h3>EduConnect</h3>
Our TÜBİTAK 2209-A funded graduation thesis: an AI-assisted campus platform that Ayşe Mandıralı and I built, with me
as team captain.
<ul>
<li>A BERTurk model we fine-tuned routes each question to a 412-entry knowledge base; every answer shows its source.</li>
<li>The database settles races: refresh tokens rotate in one atomic UPDATE, and unique indexes stop double likes.</li>
<li>When the free database expired, I built a browser-side demo of the real API; the production build has none of it.</li>
</ul>
<b>ASP.NET Core 10 · PostgreSQL · BERTurk · React 19</b><br>
<a href="https://educonnect-tez.vercel.app">Live demo</a> ·
<a href="https://github.com/mrfiratatalay/educonnect-backend">Code</a> ·
<a href="https://mrfiratatalay.github.io/en/projects/educonnect/">Case study</a>
</td>
<td width="46%">
<a href="https://educonnect-tez.vercel.app"><img src="https://mrfiratatalay.github.io/images/projects/educonnect/kapak.webp" alt="EduConnect: the personalized feed on the desktop and EduAI answering with its source on a phone" /></a>
</td>
</tr>
</table>

## More projects

**[FraudCell](https://github.com/mrfiratatalay/FraudCell)** · *Turkcell Code Night 2026 All-Star final*<br>
An event-driven fraud operations platform: Identity, Transaction, AI and Gamification services behind a YARP gateway,
each with its own PostgreSQL database, talking over RabbitMQ. **My part:** transaction assessment with a transactional
outbox and inbox, role-based authorization, real-time notifications, and a fallback that keeps intake running when the
AI service is down. `ASP.NET Core 10` `RabbitMQ` `FastAPI` `PostgreSQL` ·
[Case study](https://mrfiratatalay.github.io/en/projects/fraudcell/)

Every project, with its story, screenshots and the reasoning behind each decision, is on
[my portfolio](https://mrfiratatalay.github.io/en/projects/).

## How I work

- **One source of truth.** I derive numbers from records instead of copying them into counters that drift.
- **Let the database guard the rules.** Row-level security, partial unique indexes and constraints back up the code.
- **Plan for races.** Row locks against double submissions; a sign-up race ends in a clean `409`, not a `500`.
- **Models advise, code decides.** An LLM returns scores and evidence; deterministic rules make the final call, so
  the same input always gets the same, explainable answer.
- **Fail soft, and say so.** When a model or a downstream service fails, a fallback keeps the product working and
  the screen tells the user.
- **Make it reviewable.** Pull requests and code review, rules enforced by the build, and docs that explain every trade-off.

## Tech stack

| Area | Tools |
|---|---|
| **Backend** | <img src="https://skillicons.dev/icons?i=java,spring,cs,dotnet,py,fastapi" height="40" alt="Java, Spring Boot, C#, .NET, Python, FastAPI" /> |
| **Data & messaging** | <img src="https://skillicons.dev/icons?i=postgres,mongodb,rabbitmq" height="40" alt="PostgreSQL, MongoDB, RabbitMQ" /> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,ts,vue,nextjs,tailwind" height="40" alt="React, TypeScript, Vue, Next.js, Tailwind CSS" /> |
| **Tooling** | <img src="https://skillicons.dev/icons?i=docker,git,github,postman" height="40" alt="Docker, Git, GitHub, Postman" /> |

**Also:** Entity Framework Core · Spring Security & JWT · Flyway · Microsoft SQL Server · YARP · Swagger/OpenAPI ·
Docker Compose · Server-Sent Events · SignalR · Gemini and Claude APIs · Hugging Face Transformers · xUnit ·
Testcontainers

**Practices:** REST API design · layered and clean architecture · CQRS · role-based access control · multi-tenancy ·
event-driven messaging with outbox/inbox · LLM integration with structured output and fallbacks

## Experience

**Software Development Intern** · Elasoft · Trabzon<br>
A 60-working-day summer internship, then a full-semester industry placement with the same team. I built backend and
full-stack features for a university community management system and an internal HR system with C#, ASP.NET Core,
EF Core, SQL Server and Vue.js: personnel and leave workflows, role-based access, validation and document export.
Every change went through a branch, a pull request and a senior engineer's code review.

**Part-Time Software Developer** · Recep Tayyip Erdoğan University · Rize<br>
Full-stack modules for internal university systems, built together with the non-technical staff who use them every day.

**Volunteer Software Developer** · Medyanes 360<br>
Joined after a full-stack case study and a live technical interview, then shipped frontend and backend features across
several products, including a language-learning platform.

**Education:** B.Sc. in Computer Engineering, Recep Tayyip Erdoğan University, 2021–2026

## Learning and writing

I write in English about backend and frontend development on [Medium](https://medium.com/@firatatalay); my articles
have been published in Huawei Developer's global and Türkiye publications and in Stackademic, and several passed 4K
reads. I also keep my weekly study notes on Java, Spring Boot and Docker in public on
[my site](https://mrfiratatalay.github.io/en/notes/).

<div align="center">

**Hiring a backend engineer?** [Email me](mailto:firatatalay.cs@gmail.com) ·
[LinkedIn](https://www.linkedin.com/in/f%C4%B1rat-atalay-2581142b6/) ·
[Download my CV](https://mrfiratatalay.github.io/cv/firat-atalay.pdf)

</div>
