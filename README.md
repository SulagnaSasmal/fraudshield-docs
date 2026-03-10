# FraudShield AI Engine — Documentation

Enterprise documentation for FraudShield AI Engine — an enterprise-grade real-time fraud detection platform for financial institutions. Covers the risk scoring model, model inputs, configuration, operational tuning, AML integration, and API reference.

## Live Demo

Hosted on GitHub Pages: `sulagnasasmal.github.io/fraudshield-docs/`

## Pages

| Page | Topic |
|------|-------|
| `index.html` | Introduction — platform overview, architecture, component summary |
| `risk-model.html` | Risk Scoring Model — ensemble model, score bands, decisioning logic |
| `model-inputs.html` | Model Input Features — behavioral, transactional, device, and network signals |
| `configuration.html` | Model Configuration — risk weights, policy settings, environment config |
| `threshold-tuning.html` | Threshold Tuning — score cutoffs, precision/recall tradeoffs, A/B testing |
| `false-positives.html` | False Positive Handling — suppression rules, analyst feedback, model retraining triggers |
| `retraining.html` | Model Retraining Cycle — data pipeline, validation, champion/challenger deployment |
| `case-management.html` | Alert Investigation & Case Management — queue management, SLA, disposition workflow |
| `customer-risk.html` | Customer Risk & AML Integration — CDD/EDD triggers, NICE Actimize integration |
| `fraud-typologies.html` | Fraud Typology Reference — payment fraud, ATO, first-party fraud, money mules |
| `api-integration.html` | API Integration Guide — scoring endpoint, webhook events, SDK quickstart |
| `audit-explainability.html` | Audit Logs & Explainability — decision audit trail, SHAP values, regulatory readiness |

## Tech Stack

- HTML (94%), CSS (6%)
- No frameworks, no build pipeline
- MadCap Flare-inspired enterprise documentation theme

## Dark / Light Mode

All pages support dark and light themes via a toggle button (◐ / ☀) in the header. Theme preference persists in `localStorage`. System `prefers-color-scheme` is respected on first visit.

## Status

**Domain Documentation — Complete**

| Section | Status |
|---------|--------|
| Platform introduction & architecture | Complete |
| Risk scoring model documentation | Complete |
| Model inputs & feature reference | Complete |
| Configuration guide | Complete |
| Threshold tuning procedures | Complete |
| False positive management | Complete |
| Model retraining cycle | Complete |
| Case management & alert workflow | Complete |
| Customer risk & AML integration | Complete |
| Fraud typology reference | Complete |
| API integration guide | Complete |
| Audit logs & explainability | Complete |
| Dark / light theme support | Complete |

## Future Enhancements

- NICE Actimize SAM/WLF platform-specific integration guides
- Real-time transaction monitoring configuration deep-dive
- Network analytics and graph-based fraud detection section
- Deployment and infrastructure runbook (on-premises vs. cloud SaaS)

## Usage

Open `index.html` in any browser, or deploy to GitHub Pages. No build step required.
