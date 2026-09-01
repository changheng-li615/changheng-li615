# Hi, I'm Changheng Li

Software Engineering (Honours) graduate from Monash University, currently completing a Software Development Internship at Xugar.

I am interested in Software Engineering, Full-Stack Development and Frontend Development, with hands-on experience building web applications, backend services, Windows applications, monitoring systems and data-driven platforms.

Based in Melbourne, Australia, and currently open to Graduate Software Engineer, Junior Software Developer, Full-Stack Developer and Frontend Developer opportunities.

---

## Technical Skills

**Languages**
TypeScript, JavaScript, C#, Python, SQL, HTML, CSS

**Frontend**
React, Next.js, Tailwind CSS, WPF

**Backend**
Node.js, Express.js, .NET, REST APIs

**Databases & ORM**
PostgreSQL, Prisma ORM, MongoDB, Firebase

**Development & DevOps**
Git, GitHub, Docker, Docker Compose, GitHub Actions, VS Code

**Software Engineering**
Database Design, API Integration, Automated Testing, Debugging, Data Validation, CI/CD, Security, Production QA

---

## Featured Projects

### Endpoint Monitor

**C# · .NET · WPF · Next.js · TypeScript · PostgreSQL · Prisma · Docker**

A Windows endpoint monitoring platform combining a native desktop agent with a centralised web-based management system.

**Key Features**

* Windows WPF monitoring agent
* Running process and foreground application tracking
* Process start and stop event recording
* Scheduled screenshot capture
* Authenticated endpoint telemetry APIs
* Offline event storage with automatic synchronisation
* Device administration dashboard
* Remotely configurable monitoring policies and schedules

**Engineering Highlights**

* Designed secure device enrolment using unique installation identifiers and per-device secrets
* Protected local credentials using Windows DPAPI
* Implemented authenticated heartbeat, process, screenshot and device-event APIs
* Designed PostgreSQL and Prisma models for devices, telemetry, policies, screenshots and audit events
* Implemented retry and exponential-backoff behaviour for unreliable network conditions
* Added idempotency and event coalescing to reduce duplicate telemetry after reconnection
* Implemented private screenshot storage with file validation, SHA-256 hashing and path-traversal protection
* Added credential rotation and revocation support
* Designed the agent around a local-first architecture for reliable offline operation
* Built automated test suites across both the .NET agent and TypeScript backend

---

### Sports-Lens

**Next.js · TypeScript · Data Analytics · CSV Processing**

A web-based esports analytics platform for transforming match data into structured player, team and tournament statistics.

**Key Features**

* Player profiles and performance statistics
* Team and tournament analytics
* Player rankings and comparisons
* Radar-chart performance visualisation
* Historical statistics
* Annual player-rating system
* Structured CSV data imports

**Engineering Highlights**

* Built a unified aggregation pipeline for player and match statistics
* Developed a consistent and auditable player-rating system
* Implemented deterministic CSV validation and import behaviour
* Supported partially valid datasets while rejecting malformed requests
* Added file-size and data validation safeguards
* Separated raw imported data from calculated analytics
* Built reusable aggregation modules shared across rankings, player profiles and comparisons

---

### Wuxia Strategy Toolkit

**Next.js · TypeScript · Prisma · PostgreSQL · Docker · Konva**

A full-stack strategy management platform for organising players, battle rosters, teams and tactical plans.

**Key Features**

* Member management with search, filtering and tagging
* Battle roster management
* Team creation and player assignment
* CSV bulk importing
* Duplicate detection and validation
* Interactive tactical War Room
* Drag-and-drop team positioning
* Tactical arrows, markers, drawings and annotations
* Undo and redo support
* Persistent tactical board state
* PNG tactical plan export

**Engineering Highlights**

* Designed relational PostgreSQL models for members, aliases, battles, teams and tactical boards
* Implemented Unicode-normalised duplicate detection
* Added CSV preview and validation before database writes
* Built an interactive 1600 × 900 tactical canvas using Konva
* Implemented persistent JSON-based tactical state
* Added automated integration tests for core workflows
* Containerised the application and PostgreSQL environment using Docker

---

### WatchTower Monitoring Platform

**Next.js · TypeScript · Prisma · PostgreSQL · Docker**

An internal monitoring platform developed during my Xugar internship to centralise website, hosting and client monitoring information.

**My Contributions**

* Client and monitor management
* CSV-based data imports
* PostgreSQL and Prisma data modelling
* Integration synchronisation workflows
* Incident-management functionality
* Input validation and sanitisation
* Error and conflict handling
* Automated testing
* Docker-based development environments
* Read-only integration foundations for Synergy Wholesale, Sales Portal and WHMCS

Some Xugar internship source code is private and cannot be published publicly.

---

## Industry Experience

### Software Development Intern — Xugar

During my internship at Xugar, I have worked across full-stack development, internal tools, API integrations, monitoring systems, website QA and business platforms.

My work has included:

* Full-stack development with TypeScript, React and Next.js
* PostgreSQL and Prisma database development
* REST API development and integration
* Docker-based development environments
* Automated testing and validation
* External API integration
* Data sanitisation and error handling
* Debugging and production QA
* WordPress website maintenance
* HubSpot CRM workflow troubleshooting
* Windows and .NET application development

---

## About Me

I am particularly interested in building reliable, maintainable software and understanding how systems work across the full stack.

My recent work has given me practical experience with:

* Frontend and backend development
* Relational database design
* API architecture
* Desktop-to-server communication
* Data processing pipelines
* Automated testing
* Security and validation
* Dockerised development environments

I am currently looking for opportunities where I can continue developing as a software engineer while contributing to real production systems.

---

## Contact

**Email:** [changhengli615@gmail.com](mailto:changhengli615@gmail.com)

**Location:** Melbourne, Australia
