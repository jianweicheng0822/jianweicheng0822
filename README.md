## Hi, I'm Jianwei 👋

Backend developer in Salt Lake City, UT. I build and run production web services with **Java and Spring Boot**: REST APIs, PostgreSQL/MySQL, Redis caching, automated testing, and CI/CD to AWS.

B.S. in Computer Science, University of Utah (2024).

### Projects

**[LoL Tracker](https://github.com/jianweicheng0822/lol-tracker)** · [live](https://loltracker.lol)  
League of Legends analytics platform on Spring Boot, PostgreSQL and Redis.
- A scheduled pipeline has collected 140K+ matches and 35K+ LP snapshots for 1,200+ players
- A Redis cache serves 65% of Riot API lookups, cutting match-history loads from ~700 ms to ~200 ms
- Zero-downtime blue/green deploys to AWS EC2 (0 of 1,000+ requests failed during a measured deploy), gated on 900+ automated tests

**[JobFlow](https://github.com/jianweicheng0822/JobFlow)** · [live](https://jobflow.lumis.software)  
Multi-user job application tracker: Spring Boot REST API on MySQL.
- Spring Security with JWT and Google/GitHub OAuth2; every query is scoped to the signed-in user
- Load-tested with k6 and traced a latency spike to connection-pool exhaustion: p95 from 1,903 ms to 102 ms
- Keyless deploys to AWS EC2 via GitHub Actions OIDC and SSM, with automatic rollback

**[Learning Management System](https://github.com/jianweicheng0822/learning-management-system)**  
ASP.NET Core MVC app with role-based access for admins, instructors and students; submissions stored in AWS S3 behind pre-signed links.

**[NeetCode Solutions](https://github.com/jianweicheng0822/neetcode-submissions)**  
Data structures and algorithms practice in Java, synced automatically from NeetCode.io.

### Tech

**Languages:** Java, C#, SQL, TypeScript  
**Backend:** Spring Boot, Spring Security, Spring Data JPA, ASP.NET Core, Entity Framework Core  
**Data & Cloud:** PostgreSQL, MySQL, Redis, AWS (EC2, S3, SSM), Docker, Nginx, GitHub Actions  
**Testing:** JUnit 5, Mockito, Testcontainers, Playwright

### Contact

[LinkedIn](https://www.linkedin.com/in/jianwei-cheng)
