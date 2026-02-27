# Best-Parts Map

| Layer                      | Best LLM for This Layer | What to Extract (key paragraph/section) |
|----------------------------|-------------------------|-----------------------------------------|
| Layer 1: Data Foundation   | 3                       | "Netflix logs... tokenized interaction sequences... tokenization/compression scheme that preserves signal while keeping sequences short." |
| Layer 2: Statistics & Analysis | 3                    | "Interleaving... attributing user engagement back to the ranker... avoiding biased comparisons (position effects)." |
| Layer 3: ML Models         | 3                       | "Personalized ranking... matrix factorization (SVD-style) and RBMs... balancing accuracy with diversity/freshness." |
| Layer 4: LLM / Generative AI | 2/3 tie                | "Foundation model... autoregressive next-token... sparse attention, KV caching." (Merged depth) |
| Layer 5: Deployment & Infra| 3                       | "EVCache... p99 latency low... volatile TTL/eviction." |
| Layer 6: System Design & Scale | 3                    | "Titus... seven regionally isolated stacks... Open Connect Appliances." |
| Overall Analysis / Hardest Problem | 3                 | "Layer 3 critical... interaction event schema + tokenization." |
| Writing Style / Structure  | 3                       | Precise markdown sections, inline citations avoided per rules. |
