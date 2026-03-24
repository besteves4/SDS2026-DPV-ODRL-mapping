# SDS2026-DPV-ODRL Mapping

This repository provides a collection of [ODRL](https://www.w3.org/TR/odrl-model/) policy examples aligned with the [Data Privacy Vocabulary (DPV)](https://w3id.org/dpv), using the [DPV-ODRL mapping profile](https://dev.dpvcg.org/mappings/odrl/). Each file represents a distinct policy scenario demonstrating how ODRL can be used to express permissions, prohibitions, and obligations using DPV concepts.

---

## 📂 Repository Structure

The repository is organised into thematic folders. Each folder groups related policy examples, and **each file corresponds to a single ODRL policy**.

---

## 📑 Contents Overview

### 📁 `data`

| File | Description | Link |
|------|-------------|------|
| `age.ttl` | Policy with an Age-based party refinement | [View](./data/age.ttl) |
| `data-source.ttl` | Policy with a Data Source constraint | [View](./data/data-source.ttl) |
| `data.ttl` | Policy with a Data asset instance | [View](./data/data.ttl) |
| `gender.ttl` | Policy with a Gender-based party refinement | [View](./data/gender.ttl) |
| `nationality.ttl` | Policy with a Nationality-based party refinement | [View](./data/nationality.ttl) |
| `personal-data.ttl` | Policy with a Personal Data-based asset refinement | [View](./data/personal-data.ttl) |

---

### 📁 `entities`

| File | Description | Link |
|------|-------------|------|
| `actor.ttl` | Policy with an Actor-based party refinement | [View](./entities/actor.ttl) |
| `agent.ttl` | Policy with an Agent-based party refinement | [View](./entities/agent.ttl) |
| `entity.ttl` | Policy with Entities instances | [View](./entities/entity.ttl) |
| `human-subject.ttl` | Policy with a Human Subject-based party refinement | [View](./entities/human-subject.ttl) |
| `legal-entity.ttl` | Policy with a Legal Entity-based party refinement | [View](./entities/legal-entity.ttl) |
| `organisation.ttl` | Policy with an Organisation-based party refinement | [View](./entities/organisation.ttl) |
| `party-collection.ttl` | Policy with an Entity-based party refinement and Purpose constraint | [View](./entities/party-collection.ttl) |
| `recipient.ttl` | Policy with a Recipient constraint | [View](./entities/recipient.ttl) |

---

### 📁 `legal`

| File | Description | Link |
|------|-------------|------|
| `gdpr-consent.ttl` | Policy with a GDPR Law and GDPR Art. 6 Consent Legal Basis constraints | [View](./legal/gdpr-consent.ttl) |

---

### 📁 `location`

| File | Description | Link |
|------|-------------|------|
| `location.ttl` | Policy with a Location constraint | [View](./location/location.ttl) |

---

### 📁 `processing`

| File | Description | Link |
|------|-------------|------|
| `action-refinement.ttl` | Policy with a Location refinement action | [View](./processing/action-refinement.ttl) |
| `processing.ttl` | Policy with a Processing action | [View](./processing/processing.ttl) |

---

### 📁 `purpose`

| File | Description | Link |
|------|-------------|------|
| `purpose.ttl` | Policy with a Purpose constraint | [View](./purpose/purpose.ttl) |

---

### 📁 `rights-justifications`

| File | Description | Link |
|------|-------------|------|
| `rights-justifications.ttl` | Policy with Right and Justification constraints for GDPR's Right to Erasure | [View](./rights-justifications/rights-justifications.ttl) |

---

### 📁 `risk`

| File | Description | Link |
|------|-------------|------|
| `risk.ttl` | Policy with a Risk constraint | [View](./risk/risk.ttl) |
| `severity.ttl` | Policy with a Severity constraint | [View](./risk/severity.ttl) |

---

### 📁 `sector`

| File | Description | Link |
|------|-------------|------|
| `sector.ttl` | Policy with a Sector constraint | [View](./sector/sector.ttl) |

---

### 📁 `status`

| File | Description | Link |
|------|-------------|------|
| `status.ttl` | Policy with a Status constraint | [View](./status/status.ttl) |

---

### 📁 `tech`

| File | Description | Link |
|------|-------------|------|
| `tech-constraint.ttl` | Policy with a Technology constraint | [View](./tech/tech-constraint.ttl) |
| `tech.ttl` | Policy with a Technology asset instance | [View](./tech/tech.ttl) |

---

### 📁 `temporal`

| File | Description | Link |
|------|-------------|------|
| `duration.ttl` | Policy with a Duration constraint | [View](./temporal/duration.ttl) |
| `frequency.ttl` | Policy with a Frequency constraint | [View](./temporal/frequency.ttl) |

---

### 📁 `tom`

| File | Description | Link |
|------|-------------|------|
| `tom.ttl` | Policy with a Technical and Organisational Measure constraint | [View](./tom/tom.ttl) |

---

## 🧩 About the Policy Examples

Each file in this repository:

- Represents a **self-contained ODRL policy**
- Uses **ODRL constructs** such as:
  - `odrl:permission`
  - `odrl:prohibition`
  - `odrl:obligation`
- Incorporates **DPV concepts** (e.g., purpose, personal data, processing)
- Uses the [DPV-ODRL mapping profile](https://dev.dpvcg.org/mappings/odrl/) to bring together both solutions
- Is typically expressed in RDF formats such as:
  - Turtle (`.ttl`)

---

## 🎯 Purpose

This repository aims to:

- Provide **reference implementations** of ODRL policies using DPV
- Demonstrate **semantic alignment between DPV and ODRL**
- Support **research and experimentation** in policy-based data governance
- Serve as a **teaching and demonstration resource**

---

## ➕ Adding New Examples

To contribute a new policy, create a PR with the following:

1. Add the file to the appropriate folder
2. Ensure:
   - One file = one policy
3. Update this README:
   - Add the file to the corresponding table
   - Include a short description

---

## 📄 Contact

- Beatriz Esteves (Postdoctoral Researcher at the KNoWs group, IDLab, UGent - imec)

[😺](https://github.com/besteves4)
[✉️](mailto:beatriz.esteves@ugent.be)

---

## 📄 License

[Attribution-ShareAlike 4.0 International](LICENSE.txt)