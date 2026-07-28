# Hi, I'm Nasser 

Backend Software Engineer passionate about **database internals, storage engines, distributed systems, and high-performance backend infrastructure**.

I enjoy building software beyond typical CRUD applications—implementing the algorithms and systems that power modern databases and backend infrastructure from the ground up. I'm particularly interested in understanding how production systems work internally and recreating them from first principles.

---

# What I'm Interested In

- Database Internals
- Storage Engines
- Systems Programming
- Backend Architecture
- Distributed Systems
- Performance Engineering
- System Design

---

# Tech Stack

### Languages

**Go • Python • Java • C/C++ • SQL • JavaScript/TypeScript**

### Backend

**FastAPI • PostgreSQL • Redis • Celery • SQLAlchemy • Node.js/Express**

### Systems & Tools

**Docker • Docker Compose • Linux • Git • Postman**

---

# Featured Projects

##  Relational Database Engine *(Go)*

A relational database engine built completely from scratch in Go, recreating the core components found inside modern database systems such as PostgreSQL and SQLite.

### Highlights

- Implemented a **slotted-page storage engine** using 4KB pages with variable-length row storage.
- Built a **recursive, type-agnostic B+Tree** supporting logarithmic lookups across millions of records.
- Designed an **LRU buffer pool manager** with dirty-page tracking and **O(1)** page eviction.
- Implemented binary serialization, metadata management, free-space tracking, and page allocation.
- Added strict binary type validation supporting multiple integer sizes and variable-length strings.
- Achieved **12,600× faster indexed lookups** than full table scans on a 1M-row benchmark.
- Optimized warm page accesses to be **118× faster** than cache misses through the custom buffer pool.

### Current Focus

- SQL parser and query execution engine
- UPDATE / DELETE support
- Query optimization
- Concurrency control
- Transactions

**Focus:** Database Internals • Storage Engines • Systems Programming • Performance Engineering

---

##  ProductTracker

A distributed backend platform for automated product monitoring built with FastAPI, PostgreSQL, Redis, Celery, and Docker.

### Highlights

- Designed an extensible scraping architecture using the **Factory Pattern** to support multiple e-commerce websites.
- Built an asynchronous task processing pipeline using **Celery** and **Redis**.
- Automated scheduled product tracking with **Celery Beat**.
- Improved API throughput by **24×** using Redis caching under load testing.
- Designed a normalized relational database schema to eliminate redundant scraping operations.
- Containerized the complete multi-service architecture using Docker Compose.

**Focus:** Backend Engineering • Distributed Systems • Caching • Performance Optimization

---

##  iPhone 15 Pro Clone

An Apple-inspired interactive landing page built with React, Three.js, and GSAP.

### Highlights

- Interactive 3D product visualization
- Smooth scroll-based animations
- Responsive UI with optimized rendering
- Improved Lighthouse performance score from **52 → 88**

**Focus:** Frontend Performance • UI Engineering

---

##  Sudoku Engine

A Java desktop application featuring an optimized Sudoku solver and puzzle generator.

### Highlights

- Object-oriented architecture following the MVC pattern
- Iterator and Flyweight design patterns
- Interactive GUI with undo history
- Difficulty-based puzzle generation

**Focus:** Algorithms • Design Patterns • Java

---

# Currently Exploring

- Query execution engines
- Database query optimization
- Transaction processing
- Concurrency control
- Distributed systems
- System design


---

## Let's Connect

- LinkedIn: https://www.linkedin.com/in/ahmed-naser-230471203
