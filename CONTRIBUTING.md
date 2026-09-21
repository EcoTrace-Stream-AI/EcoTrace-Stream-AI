# Contributing to EcoTrace-Stream AI 🌊

Thank you for your interest in contributing to **EcoTrace-Stream AI**! As an open-source project aligned with **Digital Public Goods (DPG)** standards and **UNFCCC AICA** climate mitigation guidelines, we welcome contributions from developers, data scientists, hydrologists, and environmental researchers worldwide.

---

## 📜 Code of Conduct

By participating in this project, you agree to maintain a respectful, collaborative, and inclusive environment. Please ensure all communication remains constructive, professional, and accessible to contributors of all backgrounds.

---

## 🎯 How You Can Contribute

We welcome contributions across several core areas of the platform:

1. **Hydrological & AI Machine Learning Models (`/models`):**
   * Improving GRU/RNN architectures for $C_{\text{max}}$ dynamic capacity estimation.
   * Enhancing 72-hour hydro-spatial plume dispersion predictions.
   * Refining biochemical equations converting $\text{BOD}_5$ spikes into avoided $\text{CH}_4$ carbon metrics ($\text{MT CO}_2\text{e}$).

2. **Data Ingestion Pipelines (`/ingestion`):**
   * Optimizing Copernicus Sentinel-1 SAR and Sentinel-2 optical image fetchers.
   * Expanding hardware drivers for submerged edge sensors (Dissolved Oxygen, Temperature, Flow Rate).

3. **API & Municipal Governance Tools (`/api`):**
   * Improving low-bandwidth SMS dispatching protocols for LDC municipal alerts.
   * Developing REST webhooks for off-site waste redirection receivers.

4. **Documentation & Localizations (`/docs`):**
   * Translating documentation, field guides, and API specs into French, Spanish, or regional LDC languages.

---

## 🔄 Development & Pull Request Workflow

1. **Fork & Clone:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/ecotrace-stream-ai.git](https://github.com/YOUR-USERNAME/ecotrace-stream-ai.git)
   cd ecotrace-stream-ai
