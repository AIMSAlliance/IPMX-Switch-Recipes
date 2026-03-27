# IPMX Switch Recipes

Vendor-neutral, community-driven switch configuration recipes for IPMX deployments.  
Reproducible configurations validated through contributor input and community review.

---

## Purpose

The IPMX Switch Recipes repository provides practical, real-world configuration guidance for deploying IPMX systems on network switches.

While IPMX is built on open standards such as SMPTE ST 2110 and AMWA NMOS, successfully deploying interoperable systems depends heavily on correct network configuration. This repository addresses that gap by documenting **what works in practice** across different switch platforms, firmware versions, and deployment scenarios.

This is not a specification and does not replace existing standards.  
Instead, it is a **living, implementation-focused companion** to those standards.

---

## What This Repository Contains

This repository contains **switch recipes**: structured, reproducible configuration guides for enabling IPMX functionality on specific switch models.

Each recipe focuses on:

- Multicast behavior (e.g., IGMP snooping and querier)
- Timing (e.g., PTP where applicable)
- QoS and traffic handling
- Practical deployment considerations

Recipes are:
- **Vendor-neutral in tone**
- **Reproducible**
- **Grounded in real-world validation**
- **Continuously refined over time**

---

## What Is a “Recipe”?

A recipe is a **living document for a specific switch model**, describing how that switch behaves in an IPMX environment.

Rather than being a one-time configuration example, a recipe is designed to evolve as:

- Firmware versions change
- Features are added or modified
- New deployment scenarios are tested
- Community feedback is incorporated

Each recipe includes:

- A **baseline configuration** (minimum known working setup)
- **Optional configurations** (e.g., PTP, QoS)
- A **compatibility matrix** tracking firmware behavior
- **Known working scenarios** based on real deployments
- Documented **differences across firmware versions**

This structure allows a single recipe to remain useful over time without fragmenting into multiple conflicting documents.

---

## Repository Structure
```
/templates/switch-recipe-template.md
/recipes
/
README.md
CONTRIBUTING.md
LICENSE
```
- **One file per switch model**
- Recipes are organized by vendor
- Contributions are made by updating existing recipes whenever possible

---

## Design Principles

This repository is built on a few key principles:

### 1. Practical over theoretical
Recipes describe **what to configure and what outcome to expect**, not why the underlying standards exist.

### 2. Reproducibility
Each recipe must provide enough detail for another engineer to achieve the same result.

### 3. Neutrality
Content must remain free of:
- Marketing language
- Vendor comparisons
- Subjective claims

### 4. Transparency over authority
Recipes are not centrally certified or endorsed.  
Instead, they are **open to scrutiny, refinement, and validation by the community**.

### 5. Evolution without fragmentation
A recipe grows over time rather than being replaced.  
Firmware differences, options, and edge cases are documented within the same file.

---

## Who Should Use This Repository?

This repository is intended for:

- System integrators deploying IPMX systems
- AV professionals working with IP-based media
- Network engineers supporting media workflows
- Manufacturers validating interoperability
- Educators and trainers

---

## Who Can Contribute?

Contributions are open to:

- Individual engineers and integrators
- Manufacturers and vendors
- Consultants and system designers
- Members of AIMS, AMWA, VSF, and the broader community

All contributors must follow the repository template and contribution guidelines.

---

## Working with Switch Manufacturers

Switch manufacturers are encouraged to participate.

There are several ways manufacturers can engage:

- Contribute validated configurations for their platforms
- Review and refine existing recipes
- Provide clarity on firmware-specific behavior
- Help ensure accuracy of advanced features (e.g., PTP, QoS handling)

However, all contributions must adhere to the repository’s neutrality and structure requirements.

This repository is not a marketing platform.  
It is a **shared technical resource**.

---

## Contribution Model

This repository follows a **community-driven, pull request-based model**:

- Contributions are submitted via pull request
- All changes are reviewed for:
  - Clarity
  - Reproducibility
  - Neutral tone
- Contributors must state how configurations were validated

Validation may include:
- Lab testing
- Interoperability testing events
- Real-world deployments

Over time, community feedback (issues, revisions, additional scenarios) strengthens each recipe.

---

## Scope and Limitations

This repository:

- Documents **switch configuration behavior only**
- Does not define IPMX requirements
- Does not replace formal certification or testing programs
- Does not guarantee interoperability

It is intended to **accelerate deployment and improve shared understanding**, not to serve as an authoritative standard.

---

## Open Questions and Future Direction

As this repository evolves, several areas may require further alignment:

- What does a template look like?
- How to best represent validation levels (e.g., lab vs production vs test events)
- Whether to introduce lightweight tagging (e.g., “verified”, “in progress”)
- How to coordinate contributions with manufacturers at scale
- How to integrate with training and educational materials
- Whether to expand into related areas (e.g., reference topologies)

These topics will be explored collaboratively with the AIMS community.

---

## License

This repository is licensed under the Creative Commons Attribution–NoDerivatives 4.0 International License (CC BY-ND 4.0).

You are free to share and use these materials with attribution.  
You may not modify and redistribute them outside this repository.

All contributions become part of this repository under the same license.

---

## Summary

IPMX Switch Recipes is a shared, evolving knowledge base for making IPMX systems work in the real world.

It bridges the gap between standards and deployment by capturing:
- What configurations are required
- How switches behave in practice
- How those behaviors change over time

Its value comes from:
- Structure
- Transparency
- Community participation

And its success depends on:
- Consistent contributions
- Careful curation
- A shared commitment to clarity and neutrality
