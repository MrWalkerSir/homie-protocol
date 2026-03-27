# HomIE Protocol
### Human Identity Engine

*An open trust protocol for AI agents*

---

## What is HomIE?

HomIE is the trust layer for the agentic internet.

Protocols like ANP, A2A, and AGNTCY solve how AI agents find and talk to each other. Nobody solved whether they should trust each other. HomIE fills that gap.

Think of it as the Google star review system for AI agents — except the reviews write themselves and cannot be faked. Every time an agent completes a transaction with a vendor or another agent, it automatically contributes a signed record to the shared mesh. Those records aggregate into HomIE scores any agent can query before engaging.

HomIE also introduces **metacommunication** — agents broadcasting real-time probability signals about the likelihood of a transaction completing successfully. Not what is happening. Not why. Just how likely it is to succeed, updated continuously as circumstances change.

---

## The one-sentence version

ANP, A2A, and AGNTCY tell agents how to talk to each other. HomIE tells them whether to.

---

## Read the whitepaper

The v0.1 specification is available here in this repo.

It covers:
- The full scoring algorithm — asymmetric decay, diminishing returns, extreme reviewer penalty
- The metacommunication protocol
- The verified transaction handshake
- Three attack types and how HomIE addresses each
- The mesh architecture
- Roadmap from v0.1 spec to v1.0 open standard

---

## Current status

**v0.1 is complete.** This document is the specification.

The reference implementation — hosted API, identity registry, client libraries, OpenClaw skill — is the v0.2 community target. We are actively looking for collaborators.

---

## We need your help

If you want to build the reference implementation, this is the call.

Specifically looking for:
- Backend developer for the REST API and event storage layer
- JavaScript client library
- Python client library
- OpenClaw community member to build the HomIE skill

Open an issue if you want to contribute. All credit shared openly.

---

## The community calls it Homie

We're not going to pretend that isn't perfect.

---

## License

Public domain. No rights reserved. Anyone may implement, extend, or build upon the HomIE Protocol without restriction, attribution requirement, or license fee.

---

*Andrew Walker — Independent Researcher*
*homie-protocol.org*

