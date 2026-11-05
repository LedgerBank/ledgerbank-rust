# ledgerbank-rust: scope

- Design an asynchronous typed Rust client for the public contract.
- Represent money exactly and preserve an intent's idempotency key.
- Cover pagination, structured errors, webhook verification and sandbox use.
- Define crate releases, docs.rs documentation and minimum supported Rust.

## Boundaries

Public interfaces must not expose provider credentials, internal operator surfaces, customer data or privileged configuration. Product agents use scoped capabilities; development-agent orchestration has a separate role.
