# Review 2 build progress

November 8, 2026 — work in progress, not ready for submission. Due November 24, 2026 at 1 p.m. Eastern.

## Actual work and checks

Implemented static portfolio foundation with introduction, confirmed UI/application direction, navigation, source/evidence links and accurately labeled individual/group project sections. Local browser DOM inspection confirmed content/navigation. No public deployment, narrow-screen visual check or human browser observation yet. Container definition prepared but not built/tested.

## Dependencies

Server resource check: 2 CPU cores, 964 MB RAM, about 187 MB available during inspection, 17 GB disk free, no NVIDIA tool found. Hosted model inference recommended. No model installed and no server/proxy changes made. Existing containers reported unhealthy before this work; investigate actual boundary before deployment.

Candidate free-tier provider: Google Gemini 3.5 Flash-Lite generation and gemini-embedding-001 embeddings (768 dimensions with normalization); account quota/availability unverified. Official pricing and embedding docs inspected by AI. Keep billing disabled; no paid fallback. No API key received or stored in this repository.

Next: learner confirms unused hostnames and creates free-tier API access privately; prepare restricted server secret entry, check DNS/routes/baseline, deploy scoped services, import corpus and collect actual source/representation/query/answer/check evidence. Preserve all existing services. Plan-stage learner/source-review gaps remain as previously recorded.

[Build assignment](https://njit.instructure.com/courses/70733/assignments/769190) · [Provider pricing](https://ai.google.dev/gemini-api/docs/pricing) · [Embeddings](https://ai.google.dev/gemini-api/docs/embeddings).

## Deployment boundary update

Learner approved portfolio.bombayv.com and rag.bombayv.com if unused. No existing file route matched either hostname; both DNS lookups failed during this check. Existing CMS homepage and calculator health returned HTTP 200. No routes/containers changed. DNS A records and private free-tier API-key setup are pending.
