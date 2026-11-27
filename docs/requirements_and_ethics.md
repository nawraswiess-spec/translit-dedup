# Initial Requirements and Ethical Safeguards (Unit 3 Baseline)
- Scope: Offline CSV ingestion, Arabic-to-Latin normalization, phonetic blocking, probabilistic scoring, and local FastAPI queue.
- Consent and Lawful Basis: Requires verified intake consent (consent_verified=true) and bilateral partner Data-Sharing Agreement authorization.
- Security Controls (Planned for Unit 6): Fernet (AES-128-CBC + HMAC-SHA256) at-rest encryption, session-token authentication, and append-only hash-chained audit logs.
