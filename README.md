# Hi, I'm Changheng Li

Graduated **Software Engineering (Honours)** student at Monash University
Currently completing a **Software Development Internship at Xugar**
Interested in **Software Engineering, Full-Stack and Frontend Development**
Based in Melbourne, Australia
Open to **Graduate Software Engineer, Junior Developer and Internship opportunities**

**Tech Stack**

Languages
TypeScript · JavaScript · C# · Python · SQL · HTML · CSS

Frontend
React · Next.js · Tailwind CSS · WPF

Backend
Node.js · Next.js · Express.js · .NET

Databases & ORM
PostgreSQL · Prisma · MongoDB · Firebase

Development & DevOps
Git · GitHub · Docker · Docker Compose · GitHub Actions · VS Code

Software Engineering
REST APIs · Database Design · API Integration · Automated Testing · Debugging · Data Validation · CI/CD · Security · Production QA

**Featured Projects
Endpoint Monitor**

C# · .NET · WPF · Next.js · TypeScript · PostgreSQL · Prisma · Docker

A Windows endpoint monitoring platform combining a native desktop agent with a centralised web-based management system.

What it does
Runs a lightweight Windows WPF monitoring agent
Tracks running applications and foreground processes
Records process start/stop events
Captures scheduled screenshots
Sends endpoint telemetry to authenticated backend APIs
Supports offline operation through a durable local queue
Synchronises queued events when network connectivity returns
Provides an administrative dashboard for viewing registered devices and activity
Supports remotely configurable monitoring policies and schedules
Engineering Highlights
Built secure device enrollment using unique installation IDs and per-device secrets
Protected device credentials on Windows using DPAPI
Implemented authenticated heartbeat, process, screenshot and device-event APIs
Designed PostgreSQL/Prisma models for devices, telemetry, policies, screenshots and audit events
Implemented retry and exponential-backoff behaviour for unreliable network conditions
Added idempotency and event coalescing to prevent duplicate telemetry during reconnection
Implemented private screenshot storage with file signature and size validation, SHA-256 hashing and path-traversal protection
Added credential rotation and revocation support
Designed the agent around a local-first, network-second architecture
Containerised backend infrastructure using Docker and PostgreSQL
Built automated test suites across both the .NET agent and TypeScript backend

**Sports-Lens**

Next.js · TypeScript · Data Analytics · CSV Processing

A web-based esports analytics platform designed to transform match data into structured player, team and tournament statistics.

Features
Player profiles and performance statistics
Team analytics
Match and tournament pages
Player rankings
Player-to-player comparisons
Radar-chart performance visualisation
Statistical tables and historical performance analysis
Annual player rating system
Structured CSV match-data importing
Engineering Highlights
Built a unified aggregation and calculation pipeline for player statistics
Developed an auditable player-rating system rather than calculating metrics independently throughout the UI
Added deterministic CSV validation and import behaviour
Supported complete and partially valid imports while rejecting malformed requests
Added validation for oversized uploads
Separated raw imported match data from calculated analytics
Built reusable calculation and aggregation modules shared across rankings, profiles and comparisons

**Wuxia Strategy Toolkit**

Next.js · TypeScript · Prisma · PostgreSQL · Docker · Konva

A full-stack strategy-management platform for organising players, battle rosters, teams and tactical plans.

Features
Member management with search, filtering and tags
Battle and roster management
Team creation and assignment
CSV bulk importing
Duplicate detection and validation
Interactive tactical War Room
Drag-and-drop team tokens
Tactical arrows, markers, drawings and annotations
Undo/redo support
Persistent tactical-board state
PNG tactical-plan exporting
Engineering Highlights
Designed relational PostgreSQL models for members, aliases, battles, teams and tactical boards
Implemented Unicode-normalised duplicate detection
Added safe CSV preview and validation before database writes
Created an interactive 1600×900 tactical canvas using Konva
Implemented persistent JSON-based tactical state
Added automated integration tests for core application workflows
Containerised the application and PostgreSQL environment with Docker

**WatchTower Monitoring Platform**

Next.js · TypeScript · Prisma · PostgreSQL · Docker

An internal monitoring platform developed during my Xugar internship to centralise website and client monitoring information.

My Work
Client and monitor management
CSV-based data imports
Prisma/PostgreSQL data modelling
Integration synchronisation records
Incident-management workflows
Input validation and sanitisation
Error and conflict handling
Automated testing
Docker development environments

I also worked on foundations for read-only integrations with external business systems including Synergy Wholesale, Sales Portal and WHMCS.

Some Xugar internship source code is private and cannot be published publicly.

**Industry Experience
Software Development Intern — Xugar**

During my internship I have worked across software development, internal tooling, API integration, website QA and business systems.

My work has included:

Full-stack TypeScript development
Next.js and React applications
PostgreSQL and Prisma
REST APIs
Docker environments
Automated testing
External API integration
Data validation and sanitisation
Debugging and production QA
WordPress
HubSpot CRM workflows
Windows/.NET development

**Contact**

📧 changhengli615@gmail.com

I'm currently looking for Graduate Software Engineer, Junior Software Developer, Full-Stack Developer and Frontend Developer opportunities in Australia.
