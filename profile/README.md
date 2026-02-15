<p align="center">
  <strong>Harvest</strong>
</p>

<h3 align="center">AI Product Boutique</h3>

<p align="center">
Harvest builds consumer and B2B software products that leverage AI capabilities. We spot emerging opportunities, rapidly validate product-market fit, and ship polished apps across web and mobile platforms. Our lean team combines human product judgment with AI-powered execution to move from idea to market faster than traditional development.
</p>

<p align="center"><em>A <strong>jeannAI</strong> company</em></p>

---

## Organizational Structure

Harvest operates as an **AI-native product boutique** — an 8-role team (9 nodes incl. holding context) built around the core product loop: **Spot → Screen → Build → Ship → Monetize**.

> **[Open interactive org chart](https://harvestbq.github.io/.github/organigram.html)** — zoomable, expandable D3 visualization with agent details

```mermaid
%%{init: {"flowchart": {"nodeSpacing": 30, "rankSpacing": 60}} }%%
flowchart TD
    classDef human fill:#2E8B57,color:#fff,stroke:#0F172A
    classDef hybrid fill:#0D5C63,color:#fff,stroke:#0F172A
    classDef ai fill:#00B894,color:#fff,stroke:#0F172A
    classDef holding fill:#1E1B4B,color:#fff,stroke:#0F172A

    %% Holding context
    CEO["CEO<br/><small>jeannAI</small>"]:::holding

    %% Harvest Leadership
    HMD["Harvest MD<br/><small>Human</small>"]:::human
    CEO --> HMD

    %% Product
    MI["Market Intel<br/><small>AI · SPOT</small>"]:::ai
    PE["Product Eval<br/><small>Hybrid · SCREEN</small>"]:::hybrid
    HMD --> MI
    HMD --> PE

    %% Build
    WE["Web Eng<br/><small>Hybrid · BUILD</small>"]:::hybrid
    ME["Mobile Eng<br/><small>Hybrid · BUILD</small>"]:::hybrid
    DES["UX/Product<br/><small>Hybrid · BUILD</small>"]:::hybrid
    HMD --> WE
    HMD --> ME
    HMD --> DES

    %% Ship & Monetize
    GS["Growth<br/><small>Hybrid · SHIP</small>"]:::hybrid
    HMD --> GS
    CI["Customer Intel<br/><small>AI · MONETIZE</small>"]:::ai
    GS --> CI
```

**Legend:** Human (1) · Hybrid (5) · AI (2) · Holding (1) · **9 nodes**

---

<p align="center">
  <sub><strong>Harvest</strong> — Spot. Build. Ship.</sub>
</p>
