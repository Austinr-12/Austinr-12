<div align="center"> <h1>Austin Ramirez</h1> <h3>Full-Stack Development • AI/ML • Systems Programming</h3> <p> Austin, TX • Class of 2027 • University of Texas at Austin </p> <p> <a href="https://www.linkedin.com/in/austin-ramirez-43745b327/">LinkedIn</a> • <a href="mailto:austin.ramirez1@outlook.com">Email</a> • <a href="https://github.com/Austinr-12">GitHub</a> </p> </div>
👋 About Me

I am a Computer Science student at UT Austin (minor in Statistics & Data Science) who builds full-stack applications and AI systems, and is equally at home in low-level C. Most recently I built a retrieval-augmented generation app with a measured hybrid-search pipeline; before that, scheduling, virtual memory, and a multithreaded file system in Pintos.

Currently building: a QLoRA fine-tune of a small open-weight model to replace GPT-4o-mini as the answer generator in my RAG app.

🛠 Tech Stack
Domain	Technologies
Languages	Python, TypeScript, JavaScript, Java, C, SQL, ARM assembly
AI/ML & Data	RAG, embeddings, vector search (pgvector, HNSW), hybrid retrieval, retrieval evaluation (hit@K, MRR), OpenAI API, Vercel AI SDK, NumPy, pandas
Frontend	React, Next.js, Tailwind CSS, Redux Toolkit, shadcn/ui
Backend	Node.js, Express, Prisma, REST APIs, PostgreSQL, PostGIS, zod
Cloud	AWS (Cognito, S3, EC2, Amplify), Supabase, Vercel, Upstash Redis
DevOps & Tools	Git, GitHub Actions, Vitest, supertest, VS Code, GDB, Valgrind, Linux/Unix
🚀 Featured Projects

🔎 RAG Knowledge Base Next.js, TypeScript, PostgreSQL/pgvector, Prisma, OpenAI, Clerk

A multi-tenant retrieval-augmented Q&A app: upload PDF, text, or markdown documents and get streamed answers with verbatim citations from your own sources. Hybrid retrieval (pgvector cosine + Postgres full-text search fused with Reciprocal Rank Fusion) raised hit@5 from 0.92 → 1.00 and MRR from 0.86 → 0.94 on a 12-question eval harness. Rate limiting, per-user quotas, prompt-injection sanitization, and 45 unit tests.

🏠 Rentiful — Rental Marketplace Next.js, Express, Prisma, PostgreSQL/PostGIS, AWS (Cognito, S3, EC2), Mapbox

A two-sided rental platform with map-based geospatial search and tenant/manager dashboards. Production-hardened: JWKS-verified Cognito auth, ownership checks on every user-keyed route, zod validation, N+1 fixes, 75 Vitest/supertest tests, GitHub Actions CI, and a git-history rewrite that took the repo from 11,260 → 155 tracked files.

⚙️ Pintos Operating System C, x86 • CS 439 Operating Systems

Priority scheduling with nested donation, user-program system calls, demand-paged virtual memory (lazy loading, stack growth, mmap/munmap, clock eviction), and a multilevel-indexed file system with per-inode locking and subdirectories. Course project — source not public.

🧮 Pipelined CPU Emulator + Cache Simulator C, ARM (A64 subset) assembly • CS 429 Computer Architecture

A cycle-accurate 5-stage pipeline (fetch → decode → execute → memory → writeback) for a 25-instruction A64 subset with stall, squash, and forwarding hazard control, plus a configurable write-back LRU cache simulator integrated into the memory stage. Course project — source not public.

🧠 Dynamic Memory Allocator C • CS 429 Computer Architecture

malloc/free with binned explicit free lists, splitting, coalescing, 16-byte alignment, and a heap-consistency checker. Passed all 28 trace-driven benchmarks at ~70% space utilization and ~10K ops/ms throughput. Course project — source not public.

🤝 Community
Member: Hispanic Association of Computer Scientists (HACS), UT Austin — Aug 2024 to present
<div align="center"> <sub>Designed by Austin Ramirez • 2026</sub> </div>
