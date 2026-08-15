# Xmip repository defaults

This special public repository supplies account-wide GitHub defaults for public Xmip repositories owned by [IlleNilsson](https://github.com/IlleNilsson) when a repository does not define its own file.

The authoritative Xmip integration and architecture repository remains [IlleNilsson/Xmip](https://github.com/IlleNilsson/Xmip).

## Authoritative sources

- [Architecture specification](https://github.com/IlleNilsson/Xmip/blob/main/docs/Xmip-Architecture-Specification-v1.1.md)
- [Architecture manifest](https://github.com/IlleNilsson/Xmip/blob/main/xmip-architecture.json)
- [Governance](https://github.com/IlleNilsson/Xmip/blob/main/GOVERNANCE.md)

## Scope

This repository contains contribution, security, support, issue and pull-request defaults. It contains no Xmip product source.

The reusable Rust verification workflow is versioned through the `v1` branch. It runs only when another repository calls it or when a person manually dispatches it. It has no push, pull-request or scheduled trigger.

Its ordered verification stages are formatting, semantic analysis, linting, compilation and linking, and test execution. Packaging and publishing are intentionally absent.
