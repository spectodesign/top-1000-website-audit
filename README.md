# 🧠 Top 1000 Website Audit Dataset by Specto Design

This dataset provides a comprehensive audit of 1000 of the most visited websites in the world. It includes performance, usability, and accessibility metrics to assess mobile and desktop readiness.

## 📂 Dataset Overview

Each row corresponds to a single audited domain, and includes the following fields:

| Field                       | Description                                                                |
|-----------------------------|----------------------------------------------------------------------------|
| `id` / `Rank`               | Position based on total keywords ranked for on Google (1 = highest volume) |
| `site_url`                  | Homepage URL of the audited website                                        |
| `industry`                  | Categorized industry (e.g., News, Tech, Retail)                            |
| `mobile_friendly`           | Label for mobile UX quality (`FAST`, `AVERAGE`, `SLOW`, `Blocked`, etc.)   |
| `page_load_time_sec`        | Mobile load time in seconds                                                |
| `core_web_vitals_passed`    | Did the site pass Google's Core Web Vitals on mobile (`Yes` / `No`)        |
| `lighthouse_ran`            | Whether the Lighthouse audit ran successfully (`Yes` / `No`)               |
| `audited_by`                | Audit source attribution (e.g., `Specto Design`)                           |
| `desktop_score`             | Desktop Lighthouse performance score (0–100)                               |
| `desktop_page_load_time_sec`| Estimated desktop load time in seconds                                     |

> 🏆 **Top-ranked sites** (Rank 1–100) tend to be high-traffic domains with complex functionality — the audit data reflects these challenges in performance and optimization.


## 📊 Sample Record

| id | site_url              | industry     | mobile_friendly | page_load_time_sec | core_web_vitals_passed | lighthouse_ran | audited_by    | desktop_score | desktop_page_load_time_sec |
|----|------------------------|--------------|------------------|---------------------|--------------------------|----------------|----------------|----------------|------------------------------|
| 1  | https://www.youtube.com | Technology   | SLOW             | 6.8                 | No                      | Yes            | Specto Design | 44.0           | 3                            |

## 📈 Use Cases

- Benchmarking digital performance against industry leaders
- Identifying trends in mobile UX design
- Informing UX and SEO strategy for developers, marketers, and auditors
- Training datasets for research in web quality and performance

## 📥 Download

- **CSV**: [`dataset.csv`](https://www.spectodesign.com/assets/dataset.csv)
- **GitHub Repository**: [github.com/spectodesign/top-1000-website-audit](https://github.com/spectodesign/top-1000-website-audit)

## 🔖 License

This dataset is published under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). Please attribute Specto Design when using or sharing this dataset.

## 🏢 About

**Specto Design** is a UX, SEO, and performance-focused digital agency based in California. We help brands design fast, accessible, and impactful web experiences.

👉 Learn more at [spectodesign.com](https://www.spectodesign.com)
