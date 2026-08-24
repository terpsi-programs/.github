# Terpsi · Programs

### Institutional program operations — skins over a shared core, data that stays in the room.

> How little can the server be permitted to know, and how narrow can its interface be, such that its full compromise is survivable?

**Terpsi · Programs** is the face for ward records, rosters, schedules, fees, and adjudication — the software a band director, camp, or district runs when **minors' education records** are on the line. FERPA and COPPA are not features here; they are the product shape.

The scaling pattern is **template first, skins second**: one `terpsi-core` contract, many domain skins (`terpsi-music`, quiet-corner, …). SMB vs Enterprise is a deploy profile, not a fork of the codebase.

---

## Design posture

- **On-premise hub** holds plaintext with zero inbound ports where possible.
- **Untrusted relay** shuttles opaque blobs between mailbox IDs for guardians off-network.
- **Edge devices** hold an encrypted replica of their own slice.
- **No published rankings** that strain ward-record promises — depth charts and OML lists are charter forks, not "more repos."

Learning corpora and citation tools live under [hornbook-knowledge](https://github.com/hornbook-knowledge) (UTETY, Jeles). Terpsi holds **program ops**, not the reading room.

---

## Status

Org wiring is live; product repos promote here as skins clear the bar. Design work for the first skin (`terpsi-music`) is in flight locally — architecture docs before application code.

---

## Part of something larger

Terpsi is the **Terpsi · Programs** face of **[Die-Namic-Systems](https://github.com/Die-Namic-Systems)** — verification at the center ([Nestor](https://github.com/Die-Namic-Systems/Nestor)), with sibling faces for memory ([willow-memory](https://github.com/willow-memory)), learning ([hornbook-knowledge](https://github.com/hornbook-knowledge)), public data ([almanac-data](https://github.com/almanac-data)), household affairs ([homestead-affairs](https://github.com/homestead-affairs)), and craft ([forge-play](https://github.com/forge-play)).

---

## Licensing

Per-repository LICENSE files are authoritative. Program software handling minors' records will ship with privacy architecture documented before first field install.

---

<sub>Programs, not profiles on children. ΔΣ = 42.</sub>
