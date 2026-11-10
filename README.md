# Marouan Boumchahate

**Full-Stack Software Engineer, Backend-Focused | System Design, API Design, Reliability** <br>
Istanbul, Türkiye · Open to remote roles worldwide

I build full-stack systems from A to Z: database schema, APIs, web or mobile client, testing and deployment. My strongest focus is the backend and how it behaves under load and failure: concurrency, query performance and reliability. BSc in Computer Engineering from Fenerbahçe University (GPA 3.90/4.00, ranked 1st in the Faculty of Engineering & Architecture).

[Portfolio](https://www.marouan.me/) · [LinkedIn](https://www.linkedin.com/in/marouan-boumchahate/) · [Email](mailto:marouanboumchahate@gmail.com)

---

## Engineering focus

- **End-to-end delivery:** designing, building and deploying a full product alone or in a team, from PostgreSQL and Redis through Node.js and .NET APIs to React and React Native clients, shipped with Docker.
- **System design and trade-offs:** splitting data between PostgreSQL and on-chain storage in S2dent to cut gas cost by 30%.
- **APIs and data:** 30+ endpoints in HouseHub with JWT, refresh tokens and RBAC; normalized schemas and zero-downtime migrations with Alembic.
- **Concurrency and reliability:** retry logic with exponential backoff, jitter and nested SQL savepoints in an open-source storage engine.
- **Performance:** composite indexes and cursor pagination that cut search latency by 45% across 50,000+ records.
- **Testing:** unit and integration suites with xUnit and pytest, including regression tests for multi-threaded race conditions.
- **Shipping:** Docker and Docker Compose, CI/CD with GitHub Actions, deployment to an Ubuntu VPS.

## Selected work

| Project | What it is | Engineering highlights |
| :--- | :--- | :--- |
| [**Kinto** (pull request #3790)](https://github.com/Kinto/kinto/pull/3790) | Open-source storage engine, contribution | Fixed a timestamp collision flaw in concurrent writes without breaking API contracts. 96% fewer write failures, p95 latency from 80ms to 33ms. |
| [**S2dent**](https://github.com/marouan-boumchahate/S2dent) | Academic credential platform (React, Node.js, PostgreSQL, Redis, Solidity) | Built end to end in a team of three, as core backend engineer, and deployed with Docker on an Ubuntu VPS. 35+ endpoints, 12+ tables, Redis worker queue that cut API latency by 23%. |
| [**HouseHub**](https://github.com/marouan-boumchahate/Househub) | Housing and roommate platform backend (.NET 8, PostgreSQL, Redis) | Clean Architecture, JWT and RBAC, OTP flow with Redis key expiration, xUnit test suite. |
| [**ToDo-FastAPI**](https://github.com/marouan-boumchahate/ToDo-FastAPI) | Async task microservice (FastAPI, PostgreSQL, Docker) | Alembic migrations, JWT OAuth2, pytest and pytest-asyncio coverage. |

## Experience

**Software Development Intern, Scramblebit** · Jul 2025 to Aug 2025
Built 23+ REST APIs in Laravel for e-commerce and POS workflows. Cut peak transaction failures by 28% with server-side validation and transactional integrity, and cut reporting query latency by 38% with composite indexes and eager loading.

## Stack

C#, .NET, TypeScript, Node.js, Python, FastAPI, PostgreSQL, SQL Server, MySQL, Redis, Docker, GitHub Actions, React, React Native

## Contact

Email: marouanboumchahate@gmail.com · Portfolio: [marouan.me](https://www.marouan.me/)
