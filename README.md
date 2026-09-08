# Hi, I'm Lewicki

### Software Engineer · Backend · Android · AI · Automation · Infrastructure

I am a software engineer focused on building complete applications and systems rather than working on isolated features.

My main technologies are **Java, Kotlin, Spring Boot, PostgreSQL, Docker and Linux**. I also work with Android development, AI/ML integrations, automation and network infrastructure.

I usually work across several parts of a project at the same time: application architecture, backend services, databases, integrations, automation, deployment and infrastructure.

I like solving practical problems and turning repetitive work into software.

---

## What I Work With

### Backend

I primarily develop backend applications with **Java and Spring Boot**.

My experience includes:

* REST APIs
* Spring Boot
* WebClient
* JPA and Hibernate
* PostgreSQL
* Flyway
* Database design and migrations
* Asynchronous processing
* External API integrations
* Service-to-service communication

I prefer simple and predictable backend architecture, with clear separation between business logic, infrastructure and external integrations.

---

### Android

I develop Android applications with **Kotlin** and work with Android components beyond the standard UI layer.

Areas I have worked with include:

* Android Services
* Foreground Services
* `VpnService`
* Accessibility Services
* Overlays
* Background processing
* Runtime permissions
* Notifications
* Application lifecycle
* Device identification
* License activation
* Communication with backend APIs

Some of my Android projects require direct interaction with the operating system and network layer rather than being conventional mobile applications.

---

### AI and Machine Learning

I use AI as part of software systems rather than building applications that are only wrappers around an LLM.

I have worked with:

* LLM APIs
* Structured JSON generation
* Intent classification
* Embeddings
* Semantic similarity
* Vector search
* Multilingual models
* ONNX Runtime
* Local inference
* Semantic duplicate detection
* AI-assisted scheduling
* Recommendation systems

One of the systems I have worked on processes natural-language input and converts it into structured tasks, meetings, reminders and notes.

A typical processing pipeline looks like:

```text
User Input
    |
    v
Intent Classification
    |
    v
Semantic Analysis
    |
    v
AI Processing
    |
    v
Business Logic
    |
    v
PostgreSQL
    |
    v
Action
```

I generally prefer combining AI with deterministic application logic instead of giving an AI model complete control over the application.

---

## Automation

Automation is a recurring part of my projects.

I build software that can monitor information, process it, make decisions and perform actions without requiring constant user interaction.

I have worked with automation involving:

* Telegram
* GitHub
* Social platforms
* External APIs
* Content discovery
* Account discovery
* Recommendation systems
* Scoring and ranking
* Automated workflows
* Autonomous agents

For systems that need to make decisions, I often use scoring rather than simple yes/no rules.

```text
Input
  |
  v
Analysis
  |
  v
Multiple Signals
  |
  v
Score
  |
  v
Decision
  |
  v
Action
```

This makes it possible to combine different sources of information and adjust the behavior of the system without rewriting the whole decision process.

---

## Infrastructure

I also work with the infrastructure required to run the applications I build.

My experience includes:

* Linux
* Ubuntu
* Docker
* Docker Compose
* Apache
* Reverse proxies
* SSH
* VPN routing
* SOCKS and HTTP proxies
* Container networking
* Server deployment
* Backups
* System recovery
* Disk migration
* Monitoring
* Log analysis
* Network troubleshooting

I am particularly interested in networking and how applications communicate across different layers.

For example, a request may pass through:

```text
Application
    |
    v
Reverse Proxy
    |
    v
Docker Network
    |
    v
Backend
   / \
  /   \
 v     v
DB    External API
```

For more complex systems, different containers may use different routes, proxies or VPN gateways.

---

## Docker

I use Docker to build reproducible application environments and separate individual services.

A typical project may contain:

```text
Frontend
    |
    v
Reverse Proxy
    |
    v
Backend
   / \
  /   \
 v     v
DB    AI Services
```

Depending on the project, additional containers can handle:

* Background workers
* Scheduled tasks
* Proxies
* VPN routing
* AI services
* Supporting infrastructure components

This approach makes it easier to isolate services, reproduce environments and manage deployments.

---

## System Design

I prefer thinking about an application as a system rather than a collection of individual features.

When designing a project, I usually consider:

* How services communicate
* Where data is stored
* How failures are handled
* How background jobs are processed
* How external APIs are isolated
* How the application is monitored
* How it will be deployed
* How it can be backed up and recovered
* What happens when part of the system becomes unavailable

This is especially important for applications that combine backend services, databases, AI processing, automation and external APIs.

---

## Projects

Some of the areas I have worked on include:

### AI Productivity Systems

Applications that use natural-language input to create and manage structured tasks, meetings, reminders and notes.

The systems combine:

* LLM processing
* Intent classification
* Embeddings
* Semantic search
* PostgreSQL
* Automated workflows

---

### Telegram Automation

Automation systems for monitoring and processing Telegram content and performing actions based on configurable rules.

These systems can combine content discovery, filtering, scoring, scheduling and automated actions.

---

### GitHub Automation

Tools for working with GitHub data, repository discovery, user analysis, scoring and automated workflows.

Areas include:

* Repository discovery
* User analysis
* Automated workflows
* Scoring systems
* GitHub API integrations
* Developer tooling

---

### Android Applications

Applications that use Android system services, VPN functionality, accessibility features, background processing and communication with backend services.

Some applications interact directly with Android system capabilities and the network layer rather than functioning as conventional mobile applications.

---

### Infrastructure

Docker-based environments containing:

* Backend services
* Databases
* Reverse proxies
* VPN gateways
* Workers
* AI services
* Supporting infrastructure

The goal is to build environments that are reproducible, maintainable and recoverable.

---

## Technology

### Languages

`Java` `Kotlin` `Python` `SQL` `Bash`

### Backend

`Spring Boot` `REST API` `WebClient` `JPA` `Hibernate`

### Databases

`PostgreSQL` `PGVector` `Flyway`

### AI / ML

`LLM APIs` `Embeddings` `Semantic Search` `ONNX Runtime`

`Hugging Face Tokenizers` `Vector Search` `Intent Classification`

### Android

`Kotlin` `Android SDK` `VpnService` `AccessibilityService`

`Foreground Services` `Overlays`

### Infrastructure

`Linux` `Ubuntu` `Docker` `Docker Compose`

`Apache` `SSH` `VPN` `Reverse Proxy` `rsync`

### Development

`Git` `GitHub` `Gradle` `Maven` `IntelliJ IDEA`

---

## Currently Working With

My current interests are mainly around the combination of:

```text
Backend
   +
AI
   +
Automation
   +
Infrastructure
```

Some of the areas I am exploring:

* AI agents
* Autonomous software
* Local AI inference
* Semantic search
* Intelligent automation
* Distributed applications
* Network-aware applications
* Developer tools
* Android system-level applications
* AI-assisted productivity
* Scalable backend architectures

---

## Open Source

I am interested in building and sharing software related to:

* Backend development
* Artificial intelligence
* Automation
* GitHub
* Telegram
* Android
* Infrastructure
* Developer tools

My repositories contain both complete applications and smaller experiments used to explore particular technologies or approaches.

---

## How I Approach Problems

I usually start with a practical question:

> Can this be automated?

Then I look at the rest of the system:

> Can it be made simpler?

> Can it be made more reliable?

> Can the decision-making be improved?

> Can it scale beyond the original use case?

This approach is probably the common theme across most of the software I build.

---

## Contact

* **GitHub:** [github.com/devlewicki](https://github.com/devlewicki)
* **Website:** [lewickiy.ru](https://lewickiy.ru)
* **Telegram:** [@mlewicki](https://t.me/mlewicki)

---

**Software engineering, automation and systems that solve real problems.**
