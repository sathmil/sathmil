# hi, i'm sathmi

i'm a computer science student at stanford building systems that help people find meaning in complex, overwhelming information — search engines, recommendation systems, and interfaces grounded in how people actually think and decide.

before i began building software, i was a storyteller. i founded who we are to amplify underrepresented voices, conducted anthropological research, and explored how individual experiences reveal broader patterns about identity, culture, and resilience. today, i bring that same perspective to technology: whether i'm working with product reviews, legal documents, or human narratives, i'm interested in the same question —

**how do you build systems that surface signal from noise without losing the people and stories behind the data?**

## featured projects

### [tried & told](https://github.com/sathmil/tried-told)
a full-text search engine, built from scratch, for discovering first-person product reviews across the web.

- built a disk-backed inverted index from first principles, with delta/varint-compressed postings, positional phrase search, and segment-based garbage collection
- developed a crash-resumable crawler with write-ahead-log recovery, bloom-filter deduplication, and simhash near-duplicate detection; sourced 835 first-person reviews from 45 sites
- implemented hybrid retrieval — bm25 fused with an hnsw approximate-nearest-neighbor index over dense embeddings via reciprocal rank fusion — served through a go search api
- validated with 163 automated tests and a running design log of architectural tradeoffs

no search library — every layer, from storage to ranking, built and reasoned through by hand.

### [stackd](https://github.com/sathmil/stackd)
a social discovery platform that turns fragmented, scattered reviews of supplements, functional foods, and wellness products into structured, personal recommendations.

- designed a postgres schema where every product variant — down to individual flavors — is scored independently, with supabase auth and row-level security enforcing per-user access
- built a multi-dimensional rating system (taste, effectiveness, ingredient quality, value) and a social graph that surfaces friends' ratings first
- developed catalog search, filtering, and ranked-list discovery with a react/typescript frontend

[explore the live app →](https://www.getstackd.app/)

## other work

- **veris** (dpl holdings) — an ai-powered workspace helping judicial professionals navigate case files and draft grounded responses, built on fastapi, qdrant hybrid search, azure openai, and a next.js frontend, designed around preserving the context and human circumstances behind each case
- **who we are** — founder of a storytelling platform amplifying 50+ narratives from contributors across 7+ countries, featured in the sunday times

## the thread connecting my work

my projects span different domains, but they're grounded in the same purpose: building the infrastructure — indexes, schemas, ranking, retrieval — that lets people navigate information that's technically available but practically overwhelming.

i'm especially interested in:
- semantic search, retrieval, and recommendation systems
- human-centered ai and intelligent interfaces
- computational approaches to stories and human experience
- products that translate complex systems into meaningful decisions

## connect

[linkedin](https://www.linkedin.com/in/sathmiliyanage) · sathmi@stanford.edu
