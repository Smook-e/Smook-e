## Hey, I'm Ahmed 

A Computer & Communication Engineering student at Alexandria University. I like understanding how things work under the hood, so I've been spending most of my time lately writing backend and systems-level code from scratch instead of just using the libraries.

## What I've been building:

🗄️ **[A relational database engine, in Go, from scratch.](https://github.com/Smook-e/Custom-Relational-Database)** Slotted-page storage, an LRU buffer pool, a type-agnostic B+Tree, and a hand-written SQL tokenizer/parser/executor sitting on top — full CRUD runs as actual parsed SQL, not direct function calls. It also enforces real constraints (foreign keys, NOT NULL, UNIQUE, DEFAULT/Serial). Indexed lookups benchmark ~12,660x faster than a full scan on a 1M-row table, and I found and fixed a nasty silent data-loss bug along the way (missing dirty-page flag, no error, no crash — just gone).

📦 **ProductTracker** — a product-monitoring backend in FastAPI, PostgreSQL, Redis, and Celery. Scraping runs as async background jobs via Celery + Redis instead of blocking API requests, with Celery Beat handling daily price checks automatically. Added Redis caching on the read path, which took throughput from ~53 to ~1280 req/s under load testing. Built with a Factory Pattern so new e-commerce sites can be plugged in without touching the core.

**Earlier stuff:** a Sudoku solver in Java, some frontend/MERN projects while I was still figuring out what I liked.


**Stack I use most:** Go, Python, C++, SQL, FastAPI, PostgreSQL, Redis, Docker

Feel free to poke around my repos, the DB engine README has benchmarks and design notes if you're into that kind of thing.
